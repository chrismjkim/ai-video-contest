---
type: production-pipeline
status: active
updated: 2026-08-26
---

# 멀티에이전트 Shot 제작 흐름

## 상태 흐름

`draft → review → prompt-ready → generation-ready → evaluating → selected → locked`

어느 단계에서든 인간 결정 누락, Canon 충돌, 규정 충돌이 있으면 `blocked`로 둔다. 해결 후 직전 단계로 돌아간다.

- `prompt-ready`: 검토를 종합해 프롬프트 후보와 합격 기준이 준비됨
- `generation-ready`: 인간이 프롬프트와 비용 발생 생성 실행을 승인함
- `selected`: 사용할 Run이 선택됨
- `locked`: 인접 Shot 편집 기준으로 잠김. 변경하려면 영향 검토 필요

## 1. Shot Brief

`templates/SHOT.md`로 다음을 명시한다.

- 근거 Canon·Decision·규정 링크
- 서사적 기능과 관객이 알아야 하거나 느껴야 할 것
- 시작 상태와 종료 상태
- continuity in/out
- 잠긴 사실, 허용 가능한 변형, 미결 블로커
- 합격 기준

필수 인간 사실이나 서사 기능이 없으면 에이전트가 대신 정하지 않고 `blocked`로 둔다.

## 2. Orchestrator 위임

Orchestrator는 관련 문서와 인접 Shot/Run만 포함한 작업 패킷을 만들고 다음 관점을 필요에 따라 병렬 검토한다.

1. 서사 기능 + 연출·연기
2. 카메라 + 미장센·조명
3. 편집 + 공간·시선·동작 연속성
4. AI 생성 가능성 + 인물·의상·소품·환경 consistency

각 검토자는 `확인한 제약 / 관찰 / 위험 / 권고와 대안 / 가정 / 충돌 / 미결 질문 / verdict`를 반환한다. 전문 검토자는 Canon이나 같은 Shot 파일을 직접 병렬 수정하지 않는다.

## 3. 종합과 프롬프트

Orchestrator는 검토 간 충돌을 숨기지 않고 Shot에 기록한다.

- 규정·Canon·accepted Decision과 충돌하면 그 상위 근거를 따른다.
- 새 창작 결정이 필요하면 인간에게 회부한다.
- 기술적 트레이드오프는 대안과 영향을 함께 제시한다.
- 최종 후보에는 정확한 프롬프트, 부정 제약, 대상 플랫폼·모델, 설정, 참조 자산 버전, 합격 기준을 둔다.

Shot의 승인 프롬프트를 `generation-ready`로 바꾸는 것은 인간 승인 게이트다.

## 4. 생성과 평가

생성할 때마다 새 `RUN-SH-001-001` 문서를 만든다.

1. 실제 입력한 프롬프트와 설정을 그대로 스냅샷한다.
2. 출력 경로 또는 URL과 플랫폼 작업 ID를 기록한다.
3. 합격 기준과 continuity를 기준으로 관찰을 기록한다.
4. 관찰된 결함과 원인 가설을 분리한다.
5. 다음 실험에서 바꿀 핵심 변수 하나를 정한다.
6. `selected`, `rejected`, `failed` 중 판정한다.

같은 프롬프트의 단순 재생성이면 `generation-ready`로, 연출·연속성 설계가 바뀌어야 하면 `review`로 돌아간다.

## 5. 학습 승격

반복되거나 영향이 큰 결과만 [[knowledge/PROJECT_PRACTICES]]의 후보로 올린다. 관련 Run, 적용 범위, 반례, 인간 승인 Decision 없이는 `accepted-practice`로 만들지 않는다.

## 중단 조건

- 필요한 Canon 또는 인간 의도가 없음
- 공모전 규정과 기획이 충돌함
- 검토 결과가 서로 모순되고 객관적 우선순위가 없음
- 유료 생성, 외부 업로드, 권리 동의 등 새 승인이 필요함
- 참조 에셋의 권리나 버전을 확인할 수 없음

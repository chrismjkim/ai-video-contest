---
type: shot-index
status: active
updated: 2026-08-26
---

# Shot 인덱스

현재 등록된 Shot은 없다. 이 표는 작업 큐이자 인접 컷 연속성 지도다. 실제 Shot 문서는 `production/shots/`에 둔다.

| 순서 | Shot ID | 서사 기능 | 상태 | 이전/다음 Shot | 담당 | 현재 프롬프트 버전 | 선택 Run | 블로커 |
|---:|---|---|---|---|---|---|---|---|

## 상태

- `draft`: Brief 작성 중
- `review`: 멀티에이전트 검토 중
- `prompt-ready`: 검토 종합과 프롬프트 후보 준비 완료
- `generation-ready`: 인간 생성 승인 완료
- `evaluating`: 생성 결과 평가 중
- `selected`: 사용할 Run 선택
- `locked`: 인접 컷 기준으로 잠김
- `blocked`: 인간 결정·규정·에셋 등 선행 조건 필요

새 Shot은 `templates/SHOT.md`를 복사해 만든 뒤 이 인덱스에 추가한다. 순서가 바뀌어도 Shot ID는 바꾸지 않는다.


---
type: home
status: active
updated: 2026-09-03
---

# AI 숏드라마 프로젝트 홈

이 폴더 전체를 Obsidian Vault로 연다. 사람은 이 문서에서 시작하고, 에이전트는 `AGENTS.md`에서 시작한다. 별도 Obsidian 플러그인은 필요하지 않으며 기존 `.obsidian/` 설정은 프로젝트 지식으로 취급하지 않는다.

## 현재 단계

- 워크스페이스 초기화
- 확정된 창작 Canon: 없음
- 다음 핵심 작업: 공모전 원문 재확인, 팀 역할 합의, 스토리 탐색과 첫 Decision 기록

## 지식 지도

| 필요한 정보 | 단일 원본 |
|---|---|
| 프로젝트 목적·현재 범위 | [[project/PROJECT_BRIEF]] |
| 현재 확정된 스토리·캐릭터·연출 | [[project/CANON]] |
| 아직 결정하지 않은 질문 | [[project/OPEN_QUESTIONS]] |
| 제안·폐기 아이디어 | [[project/IDEA_REGISTER]] |
| 공모전 규정과 검증 대기 항목 | [[knowledge/CONTEST_RULES]] |
| Higgsfield·AI Video 프로젝트 학습 | [[knowledge/PROJECT_PRACTICES]] |
| 원본 이미지 레퍼런스와 관리 규칙 | [[assets/references/README]] |
| 멀티에이전트 제작 흐름 | [[production/PIPELINE]] |
| 전체 Shot 현황 | [[production/SHOT_INDEX]] |

## 기록 루틴

1. 회의는 `templates/MEETING.md`로 기록한다.
2. 회의에서 결론이 나면 `templates/DECISION.md`로 별도 Decision을 만든다.
3. 승인된 Decision과 함께 `PROJECT_BRIEF.md`, `CANON.md`, `OPEN_QUESTIONS.md` 중 영향받는 단일 원본을 갱신한다.
4. 채택하지 않은 아이디어도 이유와 재검토 조건을 `IDEA_REGISTER.md` 또는 `templates/IDEA.md`에 남긴다.
5. 컷이 정해지면 `templates/SHOT.md`를 복사하고 `SHOT_INDEX.md`에 한 줄을 추가한다.
6. 실제 생성마다 `templates/RUN.md`를 복사한다. 결과가 나빠도 삭제하지 않는다.
7. 여러 Run에서 반복 확인된 학습만 `PROJECT_PRACTICES.md` 승격 후보로 올린다.

## 폴더 책임

- `project/`: 인간의 프로젝트 맥락, 회의, 결정, Canon, 미결 질문
- `knowledge/`: 출처가 있는 외부 규정과 프로젝트에서 검증된 특수 지식
- `production/`: Shot, 프롬프트, 멀티에이전트 검토, 생성 Run
- `assets/references/`: Git LFS로 저장·공유하는 원본 이미지 레퍼런스
- `templates/`: 반복 기록용 최소 골격

원본 참조 이미지는 `assets/references/`에서 관리한다. 생성 영상과 기타 대용량 출력의 저장·백업 정책은 아직 정하지 않았으므로, 정책 확정 전에는 Run에 현재 경로 또는 URL만 기록한다.

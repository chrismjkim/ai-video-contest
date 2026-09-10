---
type: shot-index
status: active
updated: 2026-08-26
---

# Shot 인덱스

[[production/PROLOGUE_SHOTLIST_DRAFT]]의 72개 세부 컷(S01–S72)을 스킬의 Seedance 생성 단위(4~7컷·약 20~40초)에 맞춰 9개 Shot으로 묶었다. 이 표는 작업 큐이자 인접 컷 연속성 지도다. 실제 Shot 문서는 `production/shots/`에 둔다.

| 순서 | Shot ID | 서사 기능 | 상태 | 이전/다음 Shot | 담당 | 현재 프롬프트 버전 | 선택 Run | 블로커 |
|---:|---|---|---|---|---|---|---|---|
| 1 | [[production/shots/SH-001-서하의-기원]] | 서하의 기원 (S01–S07, 0:00–0:22) | prompt-ready | - / SH-002 | 미정 | v1 | - | 없음 |
| 2 | [[production/shots/SH-002-판정과-형체-리빌]] | 판정과 형체 리빌 (S08–S15, 0:22–1:02) | prompt-ready | SH-001 / SH-003 | 미정 | v1 | - | 없음 |
| 3 | [[production/shots/SH-003-호흡붕괴와-성급한-살풀이]] | 호흡 붕괴와 성급한 살풀이 (S16–S24, 1:02–1:40) | prompt-ready | SH-002 / SH-004 | 미정 | v1 | - | 없음 |
| 4 | [[production/shots/SH-004-살아있는-선배]] | 살아 있는 선배 (S25–S31, 1:40–2:07) | prompt-ready | SH-003 / SH-005 | 미정 | v1 | - | 없음 |
| 5 | [[production/shots/SH-005-박예린-낮은-잠식도]] | 박예린, 낮은 잠식도 (S32–S43, 2:07–2:40) | prompt-ready | SH-004 / SH-006 | 미정 | v1 | - | 없음 |
| 6 | [[production/shots/SH-006-장례와-시간압축]] | 장례와 시간 압축 (S44–S52, 2:40–3:13) | prompt-ready | SH-005 / SH-007 | 미정 | v1 | - | 없음 |
| 7 | [[production/shots/SH-007-예린의-귀환]] | 예린의 귀환 (S53–S58, 3:13–3:32) | prompt-ready | SH-006 / SH-008 | 미정 | v1 | - | 없음 |
| 8 | [[production/shots/SH-008-예린-뒤의-서하]] | 예린 뒤의 서하 (S59–S66, 3:32–4:06) | prompt-ready | SH-007 / SH-009 | 미정 | v1 | - | 없음 |
| 9 | [[production/shots/SH-009-잠식도-상승과-클리프행어]] | 잠식도 상승과 클리프행어 (S67–S72, 4:06–4:24) | prompt-ready | SH-008 / - | 미정 | v1 | - | 없음 |

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


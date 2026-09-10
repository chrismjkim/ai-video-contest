---
type: prop-index
status: active
updated: 2026-09-10
---

# 소품 인덱스

`[[production/PROLOGUE_SHOTLIST_DRAFT]]` §5에서 레퍼런스가 없다고 표시된 소품을 정리한 인덱스다. 각 문서의 디자인 제안은 `proposed`이며, 인간이 승인해야 `accepted`로 바뀐다.

| 순서 | Prop ID | 소품 | 관련 Shot | 레퍼런스 | 상태 | 비고 |
|---:|---|---|---|---|---|---|
| 1 | PROP-001 | 어머니 영정 사진(흐림 처리) | S01 | [[assets/references/props/PROP-001-어머니-영정-사진/어머니_영정_사진_Reference]] | accepted | 얼굴 비식별 설계, DEC-011 승인 |
| 2 | PROP-002 | 서하의 조직 외투 | ~~S07 이후~~ | [[assets/references/props/PROP-002-서하-조직-외투/서하_조직_외투_Reference]] | rejected | DEC-011로 생략 확정 — 기존 교복 레퍼런스만 사용 |
| 3 | PROP-003 | 살풀이 도구(흰 수건 + 신칼) | S06, S07, S10, S21–23 | [[assets/references/props/PROP-003-살풀이-매듭-도구/살풀이_매듭_도구_Reference]] | accepted | DEC-011 승인, 참조 이미지 확보됨. 방울소리+암전 전환 포함 |
| 4 | PROP-004 | 조직 판정 화면 UI (데스크 모니터형) | S08 | [[assets/references/props/PROP-004-조직-판정-화면-UI/조직_판정_화면_Reference]] | accepted | DEC-012로 디바이스를 패드→데스크 모니터 변경. LOC-006 기존 이미지 스타일 참조. "오염도/무형관리국" 용어 확인 필요 |
| 5 | PROP-005 | 조직 관측 화면 UI (데스크 모니터형) | S40, S67, S68 | [[assets/references/props/PROP-005-조직-관측-화면-UI/조직_관측_화면_Reference]] | accepted | DEC-012로 디바이스를 패드→데스크 모니터 변경. PROP-004와 동일 UI 시스템 공유 필요 |
| 6 | PROP-006 | 박정호 유류품(지갑만) | S34 | [[assets/references/props/PROP-006-박정호-유류품/박정호_유류품_Reference]] | accepted | 휴대전화·열쇠 제외, 지갑만. 실제 지갑 사진 참조(개인정보 텍스트는 재현 안 함) |
| 7 | PROP-007 | 가족사진(박정호+박예린) | S35, S38 | [[assets/references/props/PROP-007-가족사진/가족사진_Reference]] | accepted | 승인된 박정호·박예린 레퍼런스를 그대로 identity anchor로 사용 |

## 사용 규칙

1. 각 문서의 디자인 제안은 승인 전까지 `proposed`다. 인간이 승인하면 새 Decision을 만들고 이 인덱스와 관련 문서를 갱신한다(1~5번은 [[project/decisions/DEC-011-소품디자인-확정]] + PROP-004/005 디바이스는 [[project/decisions/DEC-012-조직화면-디바이스-데스크모니터-변경]]으로 완료).
2. PROP-004·PROP-005는 같은 조직 데스크 모니터 UI 체계(`LOC-006-조직-사무실` 기존 이미지 스타일)이므로 반드시 동일한 디바이스·타이포그래피·색상·레이아웃을 공유해야 한다(스킬 §9 Prop Continuity System).
3. PROP-004·PROP-005는 화면 텍스트에 "오염도"가 아닌 Canon 용어 "잠식도"를 쓴다. "무형관리국" 조직명은 채택하지 않으며, 조직의 정식 이름은 여전히 미정이다.
4. 승인된 소품은 관련 Shot 제작 시 `templates/SHOT.md`의 "AI consistency 잠금"에 링크한다.

## 상태 요약 (2026-09-10 기준)

7개 소품 전부 확정 완료: PROP-001, 003, 004, 005, 006, 007 `accepted` / PROP-002 `rejected`(불필요). Phase 2(정식 Shot 생성) 진행에 소품 관련 블로커는 남아 있지 않다.

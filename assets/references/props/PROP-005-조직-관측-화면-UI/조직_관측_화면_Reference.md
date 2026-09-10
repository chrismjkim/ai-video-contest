---
id: PROP-005-REF
type: prop-reference
status: accepted
related_shots:
  - S40
  - S67
  - S68
related:
  - "[[assets/references/props/PROP-004-조직-판정-화면-UI/조직_판정_화면_Reference]]"
  - "[[production/locations/LOC-006-조직-사무실]]"
  - "[[assets/references/environments/LOC-006-조직-사무실/조직_사무실_Reference]]"
  - "[[project/decisions/DEC-011-소품디자인-확정]]"
  - "[[project/decisions/DEC-012-조직화면-디바이스-데스크모니터-변경]]"
created: 2026-09-10
updated: 2026-09-10
---

# 조직 관측 화면 UI 소품 레퍼런스

> **2026-09-10 확정(패드)**: ~~[[project/decisions/DEC-011-소품디자인-확정]]으로 PROP-004와 동일하게 패드(태블릿)로 확정~~
>
> **2026-09-10 변경(데스크 모니터)**: [[project/decisions/DEC-012-조직화면-디바이스-데스크모니터-변경]]으로 대체. PROP-004와 동일하게 `LOC-006-조직-사무실` 기존 이미지의 데스크 모니터를 스타일 레퍼런스로 쓰되, 텍스트는 "오염도"가 아닌 Canon 용어 "잠식도"를 사용한다.

## 설계 의도

IDEA-005 S40: "신규 관측 — 박예린 / 잠식도 3% / 관찰". S67–S68에서 같은 화면이 반복되며 숫자만 3%→4%로 갱신된다(스킬 §9 Prop Continuity 핵심 사례 — 상태 변화를 명확히 추적해야 함).

**[[assets/references/props/PROP-004-조직-판정-화면-UI/조직_판정_화면_Reference]]와 동일한 UI 시스템(타이포그래피·색상·레이아웃)을 공유해야 한다.** 차이는 필드 값과 상태 라벨뿐이어야 한다 — 박정호 화면은 "단살 승인"(빨강/경고), 박예린 화면은 "관찰"(더 낮은 위험도를 나타내는 색, 제안: 앰버 또는 청록)로 구분해 시각적으로도 위험도 차이를 암시할 수 있다.

## 필수 키워드

- PROP-004와 동일한 `dark minimalist surveillance dashboard UI` 기반
- `fields: 신규 관측 라벨, 이름(박예린), 잠식도 게이지(3% → 4%), 상태 라벨("관찰")`
- `lower-intensity accent color than PROP-004's warning red` (제안: amber/cyan)
- `identical typography, layout grid, and screen frame as PROP-004`

## 이미지 생성용 영문 프롬프트 v1 (시안, S40 3% 버전, 데스크 모니터 화면)

```text
A close-up insert of a dark desk monitor screen, same visual system as the host judgment screen (identical dark charcoal/navy background, typography, and layout grid from the existing LOC-006 organization office reference), now showing a "신규 관측"(new observation) record with a name field "박예린", a circular gauge for "잠식도" filled to only 3%, and a lower-intensity amber "관찰"(observing) status label instead of a red warning; same restrained grounded interface design, no real-world brand logos, no large organization name visible in this close-up crop, subtle screen glow, straight-on screen close-up insert; no watermark.
```

## 이미지 생성용 영문 프롬프트 v2 (시안, S68 4% 갱신 버전)

```text
Identical monitor, UI system, and framing as v1, but the circular gauge for "잠식도" now reads 4% instead of 3%, with a subtle fresh-update visual cue (e.g. a brief highlight or glow on the changed digit) to indicate the number just updated; same amber "관찰" status label, same layout and typography; no watermark.
```

## 생성 설정

- 모델: 미정 (PROP-004와 동일 파이프라인·동일 세션에서 제작 권장 — 일관성 확보)
- 참조 자산: [[assets/references/environments/LOC-006-조직-사무실/조직_사무실_Reference]] 폴더의 기존 생성 이미지 + PROP-004 확정본

## 인간 승인 (2026-09-10)

- "잠식도" 용어 확정, "무형관리국" 조직명 미채택 확정. 근거: [[project/decisions/DEC-012-조직화면-디바이스-데스크모니터-변경]] 추가 승인

## 미결 사항

- PROP-004의 UI 디자인이 먼저 확정되어야 이 문서의 시안도 최종 확정할 수 있다 (의존 관계).
- 3%→4% 갱신을 한 화면 안의 애니메이션으로 처리할지, 두 개의 별도 스틸 인서트로 처리할지 결정 필요.

---
id: PROP-004-REF
type: prop-reference
status: accepted
related_shots:
  - S08
related:
  - "[[assets/references/props/PROP-005-조직-관측-화면-UI/조직_관측_화면_Reference]]"
  - "[[production/locations/LOC-006-조직-사무실]]"
  - "[[assets/references/environments/LOC-006-조직-사무실/조직_사무실_Reference]]"
  - "[[project/decisions/DEC-011-소품디자인-확정]]"
  - "[[project/decisions/DEC-012-조직화면-디바이스-데스크모니터-변경]]"
created: 2026-09-10
updated: 2026-09-10
---

# 조직 판정 화면 UI 소품 레퍼런스

> **2026-09-10 확정(패드)**: ~~[[project/decisions/DEC-011-소품디자인-확정]]으로 디바이스 형태를 패드(태블릿)로 확정~~
>
> **2026-09-10 변경(데스크 모니터)**: [[project/decisions/DEC-012-조직화면-디바이스-데스크모니터-변경]]으로 위 패드 결정을 대체한다. `LOC-006-조직-사무실` 폴더의 기존 생성 이미지([[assets/references/environments/LOC-006-조직-사무실/조직_사무실_Reference]])의 데스크 듀얼 모니터를 비주얼·UI 스타일 레퍼런스로 채택한다.
>
> **주의(DEC-012에서 확인된 불일치)**: 기존 LOC-006 이미지 화면에는 "오염도"라는 용어가 쓰여 있으나 Canon 확정 용어는 **"잠식도"**다. 아래 프롬프트는 비주얼 스타일만 참고하고 텍스트는 Canon 용어를 따른다. 또한 그 이미지 배경에 "무형관리국"이라는 조직명이 노출되어 있으나 이는 Canon에 없는 미확정 이름이다 — 인간 확인 필요.

## 설계 의도

IDEA-005 S08: 조직 기록 화면 "숙주 박정호 / 잠식도 96% / 단살 승인". `LOCATION_INDEX.md`도 LOC-006 조직 사무실 항목에서 "기록 UI의 실제 디자인 미정"을 블로커로 이미 표시하고 있다.

**주의**: UI 화면 자체는 실사 촬영형 AI 이미지 생성보다 **UI/모션그래픽 디자인 작업**에 더 가깝다. 아래는 LOC-006 기존 이미지 스타일을 따르는 화면 클로즈업 인서트용 AI 이미지 생성 프롬프트로 1차 시안을 제안하지만, 화면 내부 UI 그래픽 자체는 별도 그래픽 툴(예: Figma, After Effects)로 제작 후 합성하는 편이 텍스트 가독성·재사용성 면에서 더 안정적일 수 있다.

**PROP-005(조직 관측 화면)와 반드시 같은 디바이스(데스크 모니터)·UI 체계(타이포그래피·색상·레이아웃 그리드)를 공유해야 한다.** 스킬 §9(Prop Continuity)에 따라 같은 조직 시스템이 화면마다 다르게 보이면 연속성이 깨진다. 두 화면 모두 [[assets/references/environments/LOC-006-조직-사무실/조직_사무실_Reference]]에 이미 존재하는 데스크·모니터 세트를 그대로 재사용한다(신규 디바이스 디자인 불필요).

## 필수 키워드

- `dark desk monitor(s)`, `same monitor setup as LOC-006 organization office reference`
- `dark minimalist dashboard UI`, `left panel with circular gauge + photo + text fields`, `geometric sans-serif Korean typography`
- `dark charcoal/navy UI background`, `red accent color for high-risk warning states`
- `fields: 숙주(HOST) 이름 박정호, 잠식도(%) 원형 게이지 96%, 판정 상태 라벨 "단살 승인"` — **"오염도"가 아니라 Canon 용어 "잠식도" 사용**
- `screen close-up insert on the monitor`, `no real brand logos`, `no readable organization name in frame` (조직명 미확정 — §설계 의도 참고)

## 이미지 생성용 영문 프롬프트 v1 (시안, 데스크 모니터 화면 클로즈업)

```text
A close-up insert of a dark desk monitor screen, matching the visual style of an existing dark-themed Korean occult-investigation operations office dashboard (dark charcoal/navy background, clean geometric sans-serif Korean typography, a left panel with a circular percentage gauge and a small photo thumbnail, red accent color for high-risk states), now showing a host record: name field "박정호", a circular gauge for "잠식도" filled to 96% in red, and a warning label reading "단살 승인"(execution approved); restrained grounded interface design, no real-world brand logos, no large organization name or slogan visible in this close-up crop, subtle screen glow; shot as a straight-on screen close-up insert; no watermark.
```

## 생성 설정

- 모델: 미정 (UI 그래픽 자체는 별도 그래픽 툴 권장 — §설계 의도 참고)
- 참조 자산: [[assets/references/environments/LOC-006-조직-사무실/조직_사무실_Reference]] 폴더의 기존 생성 이미지(비주얼 스타일 참고, 텍스트는 그대로 복사하지 않음)

## 인간 승인 (2026-09-10)

- "잠식도" 용어 확정, "무형관리국" 조직명 미채택 확정. 근거: [[project/decisions/DEC-012-조직화면-디바이스-데스크모니터-변경]] 추가 승인

## 미결 사항

- UI 제작 방식: AI 이미지 생성 vs 실제 그래픽 디자인 툴 — 결정 필요
- 단살 판정 기준선(SCENARIO_DRAFT §5: 잠식도 80~90% 이상)을 화면에 수치로 노출할지 여부

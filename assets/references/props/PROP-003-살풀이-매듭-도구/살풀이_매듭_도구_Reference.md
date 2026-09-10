---
id: PROP-003-REF
type: prop-reference
status: accepted
related_shots:
  - S06
  - S07
  - S10
  - S21
  - S22
  - S23
related:
  - "[[project/SCENARIO_DRAFT]]"
  - "[[project/decisions/DEC-010-시나리오-핵심설정-장르톤-프롤로그샷수-확정]]"
  - "[[project/decisions/DEC-011-소품디자인-확정]]"
created: 2026-09-10
updated: 2026-09-10
---

# 살풀이 도구 소품 레퍼런스 — 흰 수건 + 신칼

> **2026-09-10 확정**: [[project/decisions/DEC-011-소품디자인-확정]]으로 아래 방향 A가 구체화되어 확정됐다. 참조 이미지 2장을 이 폴더에 저장함: [[assets/references/props/PROP-003-살풀이-매듭-도구/수건_레퍼런스.png]](살풀이춤 흰 수건 퍼포먼스), [[assets/references/props/PROP-003-살풀이-매듭-도구/신칼_레퍼런스.png]](초승달형 신칼 한 쌍 — 오른손에는 한 자루만 사용).

## 확정된 설계

- **왼손**: 살풀이춤 스타일의 긴 흰 수건(비단/명주 재질 느낌). 손목이나 손에 쥐고 허공에 뻗거나 휘날리는 동작에 사용
- **오른손**: 초승달 모양으로 휜 날의 전통 무속 낫칼(신칼류) 한 자루. 나무 손잡이, 은색 금속 장식 링, 무광 회색 도신
- **연출 제약(중요)**: 칼로 직접 베는 동작·상해는 화면에 나오지 않는다. 살풀이 절정 시점에는 **방울 소리**가 울리고 **화면이 검은색으로 전환**되며 다음 장면으로 넘어간다 — 이 전환 자체가 살풀이 집행의 시각·청각적 "완료 신호"로 스킬 §9(Prop Continuity)·§20(Handling Violence)에 맞춰 반복 사용 가능

## 필수 키워드 — 흰 수건 (왼손)

- `long flowing white silk-like cloth (sugeon)`, `traditional Korean ritual dance cloth`
- `held and thrown into the air with the left hand`, `dynamic fabric motion`
- `worn white/ivory hanbok-adjacent sleeve reference optional`
- `stage-lit dramatic single light source, dark background`

## 필수 키워드 — 신칼 (오른손)

- `traditional Korean shamanic ritual knife (sin-kal)`, `crescent-moon curved blade`
- `matte gray steel blade`, `dark wood handle`, `silver metal ferrule ring`
- `single blade held in the right hand`, `no visible cutting motion, no blood, no wound`
- `product-style or in-hand close-up insert`

## 이미지 생성용 영문 프롬프트 v1 (흰 수건, 손에 쥔 상태)

```text
A photorealistic medium shot insert of a hand gripping and throwing a long flowing white silk-like ritual cloth (sugeon) into the air with dynamic fabric motion, dramatic single-source stage lighting against a dark background, restrained solemn ceremonial mood, shallow depth of field on the hand and cloth; no gore, no watermark.
```

## 이미지 생성용 영문 프롬프트 v2 (신칼, 손에 쥔 상태)

```text
A photorealistic close-up insert of a hand gripping a single traditional Korean shamanic ritual knife with a crescent-moon curved matte gray steel blade, dark wood handle, and a silver metal ferrule ring, held with quiet ceremonial precision; no visible cutting motion, no blood, no wound; dramatic single-source stage lighting against a dark background, shallow depth of field; no watermark.
```

## 사운드·전환 디자인 (스킬 §19 Audio Design 연계)

- 살풀이 절정 직전까지: diegetic room tone, 이명(스킬 §11 카메라 언어와 연동해 이미 Shot List S13·S58에 반영됨)
- 절정 시점: **방울 소리(bell/jingle sound)** 삽입
- 직후: 하드 컷 또는 페이드, **화면 완전 암전(블랙아웃)** → 다음 장면 전환

## 생성 설정

- 모델: 미정
- 참조 자산: [[assets/references/props/PROP-003-살풀이-매듭-도구/수건_레퍼런스.png]], [[assets/references/props/PROP-003-살풀이-매듭-도구/신칼_레퍼런스.png]]

## 미결 사항

- 신칼 레퍼런스 이미지는 두 자루가 한 쌍으로 나오지만, 실제 연출은 오른손 한 자루만 사용. 나머지 한 자루를 소품으로 둘지(예비/미사용) 여부는 불필요.


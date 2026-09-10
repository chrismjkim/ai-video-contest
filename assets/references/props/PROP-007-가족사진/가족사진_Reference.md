---
id: PROP-007-REF
type: prop-reference
status: accepted
related_shots:
  - S35
  - S38
related:
  - "[[assets/references/characters/박정호/박정호_Reference]]"
  - "[[assets/references/characters/박예린/박예린_Reference]]"
  - "[[project/decisions/DEC-007-박정호-외형-확정]]"
  - "[[project/decisions/DEC-008-박예린-외형-확정]]"
created: 2026-09-10
updated: 2026-09-10
---

# 가족사진(박정호+박예린) 소품 레퍼런스

## 2026-09-10 확정

사용자가 "가족사진은 레퍼런스 사진 그대로 이용"으로 확정 — 새로 얼굴을 디자인하지 않고, 이미 승인된 [[assets/references/characters/박정호/박정호_다각도.png]]·[[assets/references/characters/박예린/박예린_다각도.png]]를 identity anchor로 그대로 사용해 합성한다(아래 설계 의도와 동일 방향).

## 설계 의도

IDEA-005 S35: "지갑 속 가족사진 인서트(박정호+교복 예린)". S38: "사진 뒤편에 짧게 적힌 이름 '정호 · 예린'". 이 소품은 다른 소품과 달리 **이미 승인된 캐릭터 외형(DEC-007, DEC-008)을 identity anchor로 그대로 쓸 수 있다** — 새로 얼굴을 디자인할 필요가 없다.

## 필수 키워드

- `@Image 1 defines 박정호's face and identity` (from [[assets/references/characters/박정호/박정호_다각도.png]])
- `@Image 2 defines 박예린's face, identity, and school uniform` (from [[assets/references/characters/박예린/박예린_다각도.png]])
- `casual candid snapshot style, not studio portrait` — 지갑 속 개인 사진이므로 격식 없는 스냅샷 톤
- `worn/slightly faded photo paper texture`, `small size (wallet photo)`
- `both figures visible, standing together, casual everyday setting`
- 뒷면 버전: `handwritten-style Korean text "정호 · 예린" on the back of a photograph, informal handwriting, no other text`

## 이미지 생성용 영문 프롬프트 v1 (사진 앞면)

```text
@Image 1 defines 박정호's face, identity, and casual middle-aged appearance — preserve the same person. @Image 2 defines 박예린's face, identity, and school uniform (white shirt, navy tie, navy pleated skirt) — preserve the same person. A casual candid snapshot-style photograph (not a studio portrait) of the two standing together in an ordinary outdoor or home setting, natural relaxed poses, soft everyday lighting, slightly faded and worn photo-paper texture consistent with a photo carried in a wallet for years, small wallet-photo aspect ratio; no readable text, no watermark.
```

## 이미지 생성용 영문 프롬프트 v2 (사진 뒷면)

```text
A close-up insert of the blank back side of a small worn wallet photograph, aged photo-paper texture, with short handwritten-style Korean text near the bottom edge reading "정호 · 예린" in informal handwriting, no other text or markings, soft neutral lighting, shallow depth of field; no watermark.
```

## 생성 설정

- 모델: 미정
- 참조 자산: [[assets/references/characters/박정호/박정호_다각도.png]], [[assets/references/characters/박예린/박예린_다각도.png]] (둘 다 accepted)

## 미결 사항

- 촬영 배경(실외/실내)과 몇 년 전 사진인지(예린이 몇 살 때인지)는 미정 — 다만 현재 교복 차림으로 묘사되어 있어 비교적 최근 사진으로 추정됨(확정 아님).

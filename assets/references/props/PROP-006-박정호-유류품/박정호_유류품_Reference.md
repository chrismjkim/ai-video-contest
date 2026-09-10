---
id: PROP-006-REF
type: prop-reference
status: accepted
related_shots:
  - S34
related:
  - "[[assets/references/props/PROP-007-가족사진/가족사진_Reference]]"
  - "[[production/locations/LOC-006-조직-사무실]]"
created: 2026-09-10
updated: 2026-09-10
---

# 박정호 유류품(지갑) 소품 레퍼런스

## 2026-09-10 확정

사용자가 실제 지갑 사진 2장을 제공했다: [[assets/references/props/PROP-006-박정호-유류품/지갑1.jpg]](닫힌 상태, 검정 가죽), [[assets/references/props/PROP-006-박정호-유류품/지갑2.jpg]](열린 상태, 카드 슬롯). **유류품은 지갑 하나만 쓴다** — S34 대사 "책상 위 유류품(지갑·휴대전화·열쇠)"에서 휴대전화·열쇠는 제외하고 지갑만 인서트로 사용.

**주의(개인정보)**: 지갑2 사진에는 실제 카드·쿠폰·전화번호·이메일 등 사용자의 실제 개인정보가 보인다. 생성 프롬프트와 최종 소품에는 이 텍스트를 그대로 재현하지 않는다 — 지갑의 재질·색상·마모 상태·카드 슬롯 구조 같은 형태적 특징만 참고하고, 카드 문구는 읽을 수 없거나 완전히 다른 허구의 텍스트로 대체한다.

## 필수 키워드

- `worn black saffiano-textured leather bifold wallet`, `slightly aged creases`, `matte finish`
- `open state showing card slots with a few plain cards visible (no readable text/brand)`, `small paper insert tucked in`
- `still life arrangement on a desk`, `soft directional light`, `shallow depth of field`
- `no readable real-world text, numbers, or personal information`

## 이미지 생성용 영문 프롬프트 v1 (닫힌 상태)

```text
A photorealistic close-up still-life insert of a worn black leather bifold wallet with a fine saffiano-style texture and slightly aged creases, closed, resting on a plain desk surface, soft directional light, shallow depth of field, restrained neutral mood; no readable text, no watermark.
```

## 이미지 생성용 영문 프롬프트 v2 (열린 상태, 가족사진과 조합용)

```text
A photorealistic close-up still-life insert of the same worn black leather bifold wallet now open, showing a few plain card slots with unreadable or blank cards, and one inner photo slot partially visible; soft directional light, shallow depth of field; no readable real-world text or personal information, no watermark.
```

## 생성 설정

- 모델: 미정
- 참조 자산: [[assets/references/props/PROP-006-박정호-유류품/지갑1.jpg]], [[assets/references/props/PROP-006-박정호-유류품/지갑2.jpg]] (형태·재질만 참고, 텍스트 재현 금지)

## 인간 승인

- 승인 여부: 승인됨 (지갑만 사용, 휴대전화·열쇠 제외)
- 승인자: 사용자
- 승인일: 2026-09-10
- 승인 범위·메모: "유류품은 배경화면 폴더에 저장된 지갑 사진 2장만 있다고 하자"

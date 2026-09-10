---
id: PROP-002-REF
type: prop-reference
status: rejected
related_shots:
  - S07
related:
  - "[[assets/references/characters/윤서하/Seoha_Visual_Reference]]"
  - "[[project/decisions/DEC-005-윤서하-외형-리얼리즘-수정-확정]]"
  - "[[project/decisions/DEC-011-소품디자인-확정]]"
created: 2026-09-10
updated: 2026-09-10
---

# 서하의 조직 외투 소품(코스튬) 레퍼런스

> **2026-09-10 반려**: [[project/decisions/DEC-011-소품디자인-확정]]으로 이 소품을 만들지 않기로 확정했다. 서하는 이미 승인된 [[assets/references/characters/윤서하/Seoha_Visual_Reference]] 교복 차림만으로 등장한다. IDEA-005·SCENARIO_DRAFT.md의 "조직 외투" 서술도 함께 수정됐다. 아래는 반려 전 제안이었던 초안으로, 재논의 방지를 위해 삭제하지 않고 보존한다.

## 설계 의도

IDEA-005 S07: "교복 위에 조직의 외투를 걸친 현재의 서하". [[assets/references/characters/윤서하/Seoha_Visual_Reference]](DEC-005)는 교복(셔츠·타이·치마·양말·구두)만 확정하며 외투는 정의하지 않는다. 이 외투는 서하의 "학생 / 집행자" 이중생활을 시각적으로 압축하는 핵심 코스튬이라 스킬 §8 Costume Continuity 기준으로 별도 고정이 필요하다.

**제안 방향**: 로고·조직 표식 없는 무채색 긴 아우터. 스킬 기본 제약("no random readable brand text", "no logos")과 SCENARIO_DRAFT의 절제된 톤에 맞춰 장식 없는 실용적 디자인을 제안한다.

## 필수 키워드

- `@Image 1 defines the MAIN CHARACTER's face, identity, hair, skin, and body proportions` (윤서하 primary reference 연결)
- `worn over the existing white shirt, tie, and dark navy pleated skirt`
- `long dark charcoal-black utilitarian coat`, `unadorned`, `no visible logos or emblems`, `no readable text`
- `simple stand collar or plain notch lapel`, `mid-calf to knee length`, `functional silhouette, not fashion-forward`
- `worn open or loosely closed over the school uniform`
- `realistic fabric texture`, `matte finish`, `practical outerwear`

## 이미지 생성용 영문 프롬프트 v1

```text
@Image 1 defines the MAIN CHARACTER's face, identity, hair, skin appearance, age impression, and body proportions — preserve the same person. @Image 2 defines her existing school uniform (white shirt, dark navy tie, dark navy pleated skirt, white socks, black shoes) and must remain visible underneath a new outer layer. Add a long charcoal-black utilitarian coat worn open over the uniform, unadorned with no visible logos, emblems, or readable text, a simple stand collar or plain notch lapel, mid-calf length, practical and unglamorous in silhouette, realistic matte fabric texture. Full-body turnaround (front / back / three-quarter), neutral gray studio background, soft even lighting, eye-level camera, no watermark.
```

## 생성 설정

- 모델: 미정 (기존 윤서하 리얼리즘 수정 세트와 동일 파이프라인 권장)
- 참조 자산: [[assets/references/characters/윤서하/윤서하_정면타이트_리얼리즘수정.png]], [[assets/references/characters/윤서하/윤서하_좌측전신_리얼리즘수정.png]]

## 미결 사항

- 외투 색상·재질(제안: 차콜블랙)과 길이(제안: 무릎 길이)는 확정 아님.
- "조직"임을 시각적으로 드러낼 표식을 아예 안 둘지, 아니면 은은한 비언어적 디테일(예: 특정 단추 모양)로 암시할지 결정 필요.

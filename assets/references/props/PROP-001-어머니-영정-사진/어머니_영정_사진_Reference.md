---
id: PROP-001-REF
type: prop-reference
status: accepted
related_shots:
  - S01
related:
  - "[[assets/references/environments/LOC-001-장례식장/장례식장_Reference]]"
  - "[[project/ideas/IDEA-005-5분-프롤로그-압축-각본-초안]]"
  - "[[project/decisions/DEC-011-소품디자인-확정]]"
created: 2026-09-10
updated: 2026-09-10
---

# 어머니 영정 사진(흐림 처리) 소품 레퍼런스

## 설계 의도

IDEA-005 2026-09-10 수정: "영정 사진 속 어머니의 얼굴은 초점이 흐려 또렷하게 보이지 않지만, 어린 서하의 얼굴은 보여준다." `LOC-001-장례식장` 장소 레퍼런스는 이미 "blank portrait frame with no face"(완전히 빈 프레임)로 만들어져 있어, S01에는 **실제 사진이 꽂혀 있지만 의도적으로 흐리게 처리된 버전**이 별도로 필요하다.

**제안하는 설계 원칙**: 어머니 캐릭터의 얼굴을 특정하지 않는다. 이 프롭은 처음부터 "누구인지 특정할 수 없는, 아웃포커스된 인물 사진"으로만 디자인해 어머니의 실제 외형을 정의하는 것 자체를 피한다. 이는 창작 사실을 임의로 채우지 않기 위한 의도적 선택이며, 인간이 반대로 "어머니 얼굴도 나중에 특정하고 싶다"고 하면 이 프롭 자체를 다시 설계해야 한다.

## 필수 키워드

- `photorealistic memorial portrait photograph`, `heavily out-of-focus`, `shallow depth of field blur`
- `simple dark wood photo frame`, `black mourning ribbon draped over top corner`
- `vague silhouette of an adult Korean woman`, `no identifiable facial features`, `warm skin tone blur only`
- `close-up insert`, `85mm-equivalent macro framing`, `vertical composition`
- `soft warm ambient light`, `slight rain-cooled highlight`
- `no readable text`, `no sharp focus on face`, `no identifiable person`, `no watermark`

## 이미지 생성용 영문 프롬프트 v1

```text
A photorealistic close-up insert of a memorial portrait photograph inside a simple dark wood frame with a black mourning ribbon draped over the top corner, resting on a low altar surface; the photograph itself is heavily out of focus from shallow depth of field, showing only a vague warm-toned silhouette of an adult Korean woman's head and shoulders with no identifiable facial features, no visible eyes, nose, or mouth detail; soft warm ambient candlelight-adjacent light with a faint cool rainy spill from off-frame, restrained solemn mood; vertical 9:16 close-up insert framing, natural macro-style focus fall-off; no readable text, no sharp facial detail, no identifiable person, no watermark.
```

## 생성 설정

- 모델: 미정 (LOC-001과 동일 모델 사용 권장: `gpt-image-2`)
- 크기: 미정
- 참조 자산: 없음 (의도적으로 특정 얼굴 참조를 사용하지 않음)

## 인간 승인

- 승인 여부: 승인됨
- 승인자: 사용자
- 승인일: 2026-09-10
- 승인 범위·메모: 위 설계(얼굴 초점 흐림, 비식별)를 그대로 채택. 근거 [[project/decisions/DEC-011-소품디자인-확정]]

---
id: DEC-002
type: decision
status: accepted
created: 2026-09-03
decided_by: [사용자]
accepted_at: 2026-09-03
supersedes: []
superseded_by:
related:
  - "[[project/decisions/DEC-001-윤서하-외형-확정]]"
  - "[[assets/references/characters/윤서하/Seoha_Visual_Reference]]"
  - "[[production/runs/RUN-REF-YUNSEOHA-001]]"
---

# 윤서하 primary reference 확정

## 결정할 질문

윤서하의 얼굴 identity와 전신 비율·의상에 각각 어떤 파일을 primary reference로 사용할 것인가?

## 결론

- 얼굴 identity primary: `assets/references/characters/윤서하/서하_얼굴_정면.png`
- 전신 비율·의상 primary: `assets/references/characters/윤서하/서하_전신_정면.png`
- 생성 입력 원문에 적힌 `Seoha_2.png`는 이름 변경 전의 `서하_전신_정면.png`를 의미한다.

두 파일은 역할이 다르므로 하나를 제거하지 않고 primary reference 세트로 함께 사용한다.

## 상태

`accepted`

## 맥락과 근거

- 얼굴의 세부 identity 판단에는 얼굴 정면 이미지가 적합하다.
- 전신 비율과 교복 구조 판단에는 전신 정면 이미지가 적합하다.
- 인간이 두 파일의 역할과 변경 전 파일명의 대응을 직접 확인했다.

## 검토한 대안

| 대안 | 장점 | 단점·트레이드오프 | 채택하지 않은 이유 |
|---|---|---|---|
| 전신 정면 한 장만 primary로 사용 | 참조 입력이 단순함 | 얼굴 세부 기준이 약해짐 | 인간이 얼굴·전신 primary를 구분해 확정함 |
| 얼굴 정면 한 장만 primary로 사용 | 얼굴 identity가 명확함 | 전신 비율과 의상 정보가 부족함 | 인간이 얼굴·전신 primary를 구분해 확정함 |

## 영향받는 단일 원본

- [ ] `project/PROJECT_BRIEF.md`
- [x] `project/CANON.md`
- [ ] `project/OPEN_QUESTIONS.md`
- [x] 관련 제작 문서

## 재검토 조건

- 인간이 새로운 primary reference를 승인할 때
- 두 primary 이미지 사이에 얼굴, 체형 또는 의상 불일치가 확인될 때

## 승인 증거

- 2026-09-03, 사용자: "기존 문서가 지목한 Seoha_2.png는 서하_전신_정면.png를 의미해. 파일의 이름이 바뀌었기 때문이야. 따라서 얼굴의 primary는 서하_얼굴_정면.png이고, 전신의 primary는 서하_전신_정면.png이 맞아."

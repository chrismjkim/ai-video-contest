# 원본 이미지 레퍼런스

이 폴더는 생성에 사용하는 캐릭터, 환경, 소품, 스타일 원본 이미지를 Git LFS로 저장하고 공유한다.

## 구조

```text
references/
├─ characters/    캐릭터 외형·의상 레퍼런스
├─ environments/  장소·배경·세트 레퍼런스
├─ props/         소품 레퍼런스
└─ styles/        작품 전반의 시각 스타일 레퍼런스
```

각 대상이 확정되면 해당 분류 아래에 `<ID>-<slug>/` 폴더를 만들고 다음처럼 관리한다.

```text
<ID>-<slug>/
├─ primary.png  현재 primary reference
└─ additional/  필요한 경우에만 두는 추가 레퍼런스
```

## 운영 규칙

- primary reference는 대상 폴더 바로 아래에 `primary.<확장자>`로 둔다.
- 추가 이미지가 필요할 때만 `additional/` 폴더를 만든다.
- 이미지를 수정하거나 교체할 때는 같은 경로의 파일을 덮어쓸 수 있다. 별도 버전 파일은 만들지 않는다.
- Shot에는 사용할 참조 자산의 경로를, Run에는 실제 입력한 정확한 경로를 기록한다.
- 이미지의 출처와 사용 권리는 관련 Decision 또는 Run에 기록한다.
- 캐릭터·장소 설정 자체는 이 폴더가 아니라 승인된 Decision과 `project/CANON.md`에서 관리한다.

생성 영상과 기타 대용량 출력의 저장·백업 정책은 이 구조의 범위에 포함하지 않는다.

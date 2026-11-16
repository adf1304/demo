# Winter Research Portfolio

GitHub Pages용 정적 홈페이지입니다. 별도 설치 없이 `index.html`을 열어 확인할 수 있습니다.

## 배포

`index.html`과 `assets/` 폴더를 GitHub 저장소의 루트에 업로드하세요. 기존 `index.html`을 교체한 뒤 `git add -A && git commit -m "Winter research homepage" && git push`를 실행하면 됩니다.

## 수정

- `index.html`에서 `Your Name`을 자신의 이름으로 변경
- News, About, Research, Publications, Activity 내용 수정
- `assets/winter-forest.png`를 교체해 배경 변경
- `:root`의 색상 변수로 테마 변경

**주의:** 제공된 배경 사진에는 Depositphotos 워터마크가 포함되어 있습니다. 공개 게시 시 사진의 사용 권한을 확인하고 필요하면 정식 라이선스 이미지로 교체하세요.


## 스키 졸라맨 애니메이션
첫 화면 하단에서 졸라맨이 왼쪽에서 오른쪽으로 반복 이동합니다. index.html의 .skier-track, .skier-traveler 및 SVG를 수정할 수 있습니다. 움직임 줄이기 설정에서는 애니메이션이 멈춥니다.


추가 애니메이션: 스키 졸라맨이 왼쪽에서 오른쪽으로 이동하며 점프, 착지, 넘어짐, 일어서기를 반복합니다. CSS keyframes로 구현되어 추가 설치가 필요 없습니다.

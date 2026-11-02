# june0102.github.io

SangJune An의 개인 홈페이지. 빌드 과정 없는 정적 HTML이라 파일을 고치고 push하면 바로 반영됩니다.

## 구조
- `index.html` — 페이지 내용 (소개, News, Publications, Experience, Projects, Education)
- `style.css` — 디자인 (라이트/다크 모드 자동 전환)
- `images/profile.jpg` — 프로필 사진
- `.nojekyll` — GitHub Pages가 Jekyll 빌드를 건너뛰도록 함

## 자주 하는 수정
- **News 추가**: `index.html`의 `<ul class="dated">` 맨 위에 `<li>` 한 줄 추가
- **논문 추가**: `<article class="pub">` 블록을 복사해서 위에 붙여넣기
- **논문 썸네일**: `images/`에 그림을 넣고 `pub-thumb` 주석을 해제하면 왼쪽에 이미지가 붙음
- **CV / Google Scholar / 프로젝트 코드 링크**: `TODO` 주석을 찾아 해제

Layout inspired by [Jon Barron's website](https://github.com/jonbarron/website).

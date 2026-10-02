# 김기윤 · 3D Frontend Portfolio

기존 `Front` 폴더의 프로필과 프로젝트 소개를 바탕으로 만든 스크롤형 3D 포트폴리오입니다. Three.js 씬 안에서 선택 프로젝트를 둘러보고, HUD 패널에서 실제 사이트나 코드 저장소로 이동할 수 있습니다.

## 실행

`index.html` 또는 `Web.html`을 브라우저로 열거나 프로젝트 폴더에서 `python3 -m http.server 8000`을 실행한 뒤 `http://localhost:8000`으로 접속하세요. Three.js 번들은 `vendor/three.r128.min.js`에서 로컬로 불러옵니다. 외부 CDN이나 웹 폰트 연결 없이 실행됩니다. 다만 프로젝트 외부 링크를 열 때는 인터넷이 필요합니다.

## 파일

- `index.html`, `Web.html`: 같은 페이지의 진입 파일
- `Web.css`: 반응형 화면, HUD, 접근성·모션 설정
- `Web.js`: Three.js 장면, 카드 텍스처와 스크롤 인터랙션
- `media/`, `img/`: 기존 폴더 자산
- `vendor/three.r128.min.js`: Three.js r128 로컬 번들
- `vendor/THREE-LICENSE.txt`: Three.js MIT 라이선스

3D/WebGL을 사용할 수 없는 브라우저에서도 프로젝트 정보와 연락 링크가 남도록 처리했습니다. 동작 확인을 위해서는 WebGL을 지원하는 최신 브라우저를 사용하세요.
# 3D-portfolio

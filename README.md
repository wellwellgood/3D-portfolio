# 김기윤 · 3D Frontend Portfolio

Three.js 기반의 스크롤형 3D 포트폴리오입니다. 스크롤에 따라 프로젝트 카드가 이어지고, 화면 패널에서 프로젝트·연락처 링크를 이용할 수 있습니다.

## 실행

`index.html`을 브라우저에서 열거나, 프로젝트 폴더에서 `python3 -m http.server 8000`을 실행한 뒤 `http://localhost:8000`에 접속하세요. Three.js는 `vendor/three.r128.min.js`에서 로컬로 읽습니다. 외부 CDN이나 웹 폰트 연결은 필요하지 않습니다.

## 파일

- `index.html`, `Web.html`: 포트폴리오 진입 페이지
- `Web.css`: 반응형 화면과 접근성·모션 설정
- `Web.js`: Three.js 씬과 스크롤 인터랙션
- `vendor/three.r128.min.js`: Three.js r128
- `vendor/THREE-LICENSE.txt`: MIT 라이선스
- `netlify.toml`, `_redirects`: 정적 사이트 배포 설정

Three.js가 WebGL을 사용할 수 없는 환경에서도 프로젝트 설명과 연락처를 볼 수 있습니다.

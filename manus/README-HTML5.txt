성공하고싶은 재우 - HTML5 빌드

실행 방법:
1. 이 폴더 전체를 웹 서버에 업로드합니다.
2. index.html을 정적 웹 서버로 엽니다.
3. 파일을 직접 더블클릭(file://)하는 방식은 브라우저 보안 정책 때문에 권장하지 않습니다.

간단한 로컬 실행:
- Python 3: python3 -m http.server 8000
- 브라우저에서 http://localhost:8000/ 접속

포함 파일:
- index.html: 게임 로더
- index.js: HTML5 JavaScript 런타임
- index.wasm: Godot WebAssembly 엔진
- index.pck: 게임 데이터와 리소스

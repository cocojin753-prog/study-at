# study-at

알렉산더 테크닉 학습 자료실. 빌드 없이 정적 파일로 실행합니다.

- `index.html` — 자료실 홈
- `lessons/` — 개별 자료와 일러스트
- `style.css` — 공통 스타일

새 자료는 `lessons/`에 추가하고, 홈의 학습 자료 영역에서 상대 경로로 연결합니다. HTML 파일을 직접 열거나 이 디렉터리에서 `python3 -m http.server 8000`을 실행해 볼 수 있습니다.

GitHub Pages에서는 새 `study-at` 저장소의 루트에 이 디렉터리의 **내용물**을 올린 뒤 Settings → Pages에서 **Deploy from a branch**, **main**, **/ (root)**를 선택합니다.

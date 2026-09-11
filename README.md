# Duolingo Spanish Vocabulary Practice

## 실행
이 폴더를 웹서버로 열어야 JSON fetch가 정상 작동합니다.

Python이 설치된 PC:
    python -m http.server 8000

그 후 브라우저에서:
    http://localhost:8000

GitHub Pages에 index.html과 duolingo_spanish_public_master.json을 함께 올려도 됩니다.

## 데이터
업로드된 공개 English → Spanish Duolingo 어휘 master JSON을 그대로 사용합니다.
단어팩 선택 상태는 브라우저 localStorage에 저장되어 기기별로 독립적입니다.

# mywedding

정적 HTML로 만든 웨딩 안내 페이지입니다.

## 파일 구성

- `wedding_guide.html`: 실제 안내 페이지
- `index.html`: GitHub에서 바로 열 수 있도록 `wedding_guide.html`로 연결하는 진입점
- `HANDOFF.md`: 다른 에이전트/다른 데스크탑에서 이어서 작업할 수 있도록 정리한 인수인계 문서

## 로컬에서 열기

브라우저에서 `wedding_guide.html`을 직접 열거나, 간단한 서버를 띄워 확인할 수 있습니다.

```bash
python3 -m http.server 8000
```

그 뒤 `http://localhost:8000`으로 접속하면 됩니다.

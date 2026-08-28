# Taja

감정 문장으로 연습하는 한국어 타자 사이트입니다. Cloudflare Worker가 `public` 정적 자산을 제공합니다.

## 실행

```bash
npm install
npm run dev
```

배포:

```bash
npm run deploy
```

첫 방문에는 사랑, 슬픔, 용기, 평온, 희망 주제를 선택합니다. 선택 내용은 브라우저 `localStorage`에 저장되어 다음 방문부터 연습 화면이 바로 열립니다.
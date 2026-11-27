# 가족여행

우리 가족 여행 일정·동선·예산·준비물을 모아 보는 웹사이트예요.
GitHub Pages 주소: https://fuzzword0z-hue.github.io/travel/

## 구조

```
index.html          가족여행 첫 화면 (여행편 카드 목록)
fukuoka/index.html  여행편 #1 · 후쿠오카 (2026.12.26–12.29)
sw.js               오프라인 지원 (여행편 폴더 목록 TRIPS)
manifest.webmanifest, icon.svg, og-image.jpg   공용 (홈 화면 아이콘, 메신저 미리보기)
```

## 새 여행편 추가하기

1. `fukuoka/` 폴더를 복사해서 새 폴더를 만들어요 (예: `jeju/`).
2. 새 폴더의 `index.html`에서 제목·날짜·일정·예산 데이터를 바꿔요.
   - 브라우저 저장 키 접두어(`fuk26:`)도 새 여행용으로 바꿔요 (예: `jeju27:`).
3. 첫 화면 `index.html`의 `TRIPS` 목록에 카드 한 줄을 추가해요.
4. `sw.js`의 `TRIPS`에 폴더 이름을 넣고 `CACHE` 버전을 올려요.

날짜가 지나면 첫 화면에서 자동으로 ‘다녀온 여행’으로 옮겨져요.

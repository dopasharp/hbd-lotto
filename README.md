# 🎟️ 생일 복권

생일 주인공에게 보내는 100% 당첨 스크래치 복권. 이름·메시지·날짜·최종 당첨금을 넣으면 선물 링크가 만들어지고, 받은 사람은 티켓 3장을 골라 긁어서 당첨금과 편지를 확인해요.

HTML 파일 하나라서 빌드 없이 GitHub Pages로 바로 배포돼요. 로컬 실행: `python -m http.server 4190` 후 http://localhost:4190

## DOPA# 브랜드 프레임

`dopasharp/` 폴더는 모든 DOPASHARP 게임 저장소에 **똑같이** 복사해 쓰는 공통 디자인 시스템(v1.1)입니다. 원본은 `soju-game/dopasharp/`이고, 여기서 고치지 말고 원본을 고친 뒤 모든 저장소에 다시 복사합니다. 이 게임의 포인트 색은 핑크(생일 선물·당첨)이고, 라임은 주요 버튼과 당첨 금액에만 씁니다.

- `tokens.css` — 색상·타이포·여백·모서리·모션 토큰.
- `components.css` — 헤더, 버튼(Primary/Secondary/Tertiary), 결과 시트, 푸터.
- `dopasharp.js` — 게임 목록(`GAMES`, 허브 `games.js`와 같은 순서), "다른 게임 보기" → 허브 /games/ 연결, 공통 분석 이벤트 `DopaSharp.track()`.

링크 미리보기 이미지는 `og/lotto.html`을 고친 뒤 `og/lotto.png`로 다시 렌더링합니다 (명령은 파일 맨 위 주석 참고).

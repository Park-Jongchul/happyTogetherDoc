# 행복하자 우리 (Happy Together) — 화면설계서

돌싱 커뮤니티 서비스 통합 기획·화면설계서 v1.0

## 전체채팅 개편

- `대화 → 채팅`을 누르면 채팅방 목록을 거치지 않고 전체채팅에 즉시 입장합니다.
- 전체채팅은 카카오톡 오픈채팅처럼 모든 정회원이 하나의 `global` 채널에서 실시간으로 대화합니다.
- 메시지는 Supabase Realtime에 저장·배포하며, 서버 연결 실패 시 전송 성공으로 표시하지 않습니다.
- 연락처·계좌번호 의심 문자열 경고, 신고 및 운영 정책을 전체채팅에도 동일하게 적용합니다.
- 보이스룸은 휴대폰에서만 노출하며 PC·태블릿 웹에서는 숨깁니다.

## 👉 [화면설계서 보기](https://park-jongchul.github.io/happyTogetherDoc/)

| 구분 | 주소 |
|---|---|
| 화면설계서 (이 저장소) | https://park-jongchul.github.io/happyTogetherDoc/ |
| 실제 웹페이지 | https://park-jongchul.github.io/happyTogether/ |

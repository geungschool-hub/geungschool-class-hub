# 담임(반) 허브 — geungschool-class-hub

고은표 선생님의 **우리 반 학급 앱** 런처. 긍스쿨 허브(대문)의 "담임 허브" 갈래.

- **주소:** https://geungschool-hub.github.io/geungschool-class-hub/
- 단일 `index.html` (빌드 없음).
- **매년 학급이 바뀌면** `<script>`의 `HUB_NAME` 한 줄만 변경(예: `'8반 허브'`). 대문(긍스쿨 허브)의 `HOMEROOM.name`도 같이 바꿔주세요.
- **앱 추가/수정**: `CONTENTS` 배열에 카드 한 칸(`title, desc, url, group, emoji, status`) 추가 → `git push`.
- 초기 카드: 학급 포털, 영단어 학습, 1인 1역 기록, 번호 뽑기, 얼리버드.

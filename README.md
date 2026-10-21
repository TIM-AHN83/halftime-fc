# 하프타임 FC 클럽하우스

유소년 축구 클럽을 가상 공간으로 만든 3D 웹 게임 시범판입니다.

- 게임 주소: https://tim-ahn83.github.io/halftime-fc/
- 3D: Three.js r128 (cdnjs)
- 서버: Supabase (선수 기록 저장 RPC, 실시간 접속 채널 `htfc-club-v1`)
- 영상관: `media/highlight.mp4`

## 선수 기록
선수 이름 + 숫자 4자리 비밀번호로 입장합니다. 비밀번호는 서버에서 bcrypt로 암호화되고, 5번 틀리면 5분 동안 잠깁니다.


# 카톡 알림 배드애플

PC 카톡 알림창 하나를 픽셀 하나로 써서 배드애플을 재생하는, 정말 쓸모없는 시뮬레이터.

[recording.webm](https://github.com/user-attachments/assets/5f541685-92c6-44ac-88c3-43d29c469c20)

[recording.webm](recording.webm) — 예시: 가로 알림 10개, 임계값 128

## 준비물

저작권 때문에 저장소에는 없음. 이 폴더에 직접 넣기.

- `bad-apple.mp4` — 배드애플 영상 ([Hugging Face](https://huggingface.co/spaces/Nick088/Bad-Apple-Video/tree/main))
- `win10.png` — 작업표시줄까지 나온 1920×1080 윈도우10 바탕화면 ([Alpha Coders](https://wall.alphacoders.com/big.php?i=1410908))

## 실행

```bash
node serve.js
```

http://localhost:8000 접속. (`file://`로 열면 영상 픽셀을 못 읽어서 서버가 필요함)

## 수정

- 알림 내용: `notifications.json`

# 코레일 매크로 업데이트

코레일 매크로 Android 앱이 새 버전을 확인하는 곳입니다. 앱의 [설정] → [업데이트]를 누를 때만 이 저장소를 읽습니다.

- `android-update.json`: 최신 버전 정보 (버전, 내려받기 주소, SHA-256)
- APK: [Releases](https://github.com/ppcciiss2-ux/korail-macro-updates/releases)

처음 설치할 때만 Releases에서 받습니다. 그다음부터는 앱의 업데이트 화면에서 새 버전을 받고, 받은 파일의 SHA-256이 맞을 때만 설치 화면을 엽니다.

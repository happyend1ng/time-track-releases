# TimeTrack 설치 파일

[최신 버전 받기](https://github.com/happyend1ng/time-track-releases/releases/latest)

- **Windows** — `TimeTrack_<버전>_x64-setup.exe` 를 받아 실행합니다.
  SmartScreen 이 막으면 **추가 정보 → 실행**.
- **macOS** — `TimeTrack_<버전>_universal.dmg` 를 열어 Applications 로 끌어 넣습니다.
  서명·공증이 없어 처음 한 번은 막힙니다. 터미널에서 아래를 한 번 실행하세요.

  ```bash
  xattr -dr com.apple.quarantine /Applications/TimeTrack.app
  ```

한 번 설치한 뒤에는 앱이 스스로 새 버전을 확인합니다 (설정 → 업데이트).

소스는 비공개 저장소에 있고, 여기에는 CI 가 구운 설치 파일만 올라옵니다.

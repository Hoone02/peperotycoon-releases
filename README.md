# PeperoTycoon 클라이언트 배포

로컬 테스트용 런처와 모드 자동 업데이트 파일을 배포합니다. 게임·런처 소스와 서버 운영 데이터는 별도 비공개 저장소에서 관리합니다.

## 런처

[런처 다운로드](https://github.com/Hoone02/peperotycoon-releases/releases/download/client-0.9.0-20261027.2/Pepero-Tycoon-Test-Launcher.zip)에서 ZIP을 받아 전체 압축을 풀고 Pepero Tycoon Test.exe를 실행하세요. 기존 런처는 이번 버전으로 한 번 교체해야 합니다. 이후 모드는 시작 시와 게임 실행 전에 자동 확인합니다.

접속 주소는 127.0.0.1:25565, 계정은 PeperoTester입니다. 정식 서버 접속·Microsoft 로그인 기능은 아직 활성화하지 않았습니다.

업데이트 실패 시 게임 실행을 중단하며 기존 파일을 보존합니다. 모드별 출처와 라이선스는 각 릴리스의 mod-licenses.json을 참고하세요. 외부 모드 JAR은 원본 그대로 배포합니다.

이 저장소의 최신 릴리스에는 반드시 client-update.json이 있어야 합니다. 새 모드 배포는 모든 파일 업로드 후 초안을 공개하는 도구를 사용합니다. 런처 실행 파일 자체의 자동 교체는 현재 제공하지 않습니다.

# 안심케어 Android APK 다운로드

이 저장소는 **안심케어 Android APK의 공개 다운로드 전용**입니다. 소스 코드, 환자 정보, 중앙 관제 접속 정보, 운영 설정, 비밀값은 포함하지 않습니다.

## 현재 제공 파일

현재 기본 배포본은 ARM64 갤럭시 시험 기기용 **release 서명 사전 릴리스 APK**입니다. [최신 서명 APK 다운로드](https://github.com/GrayOM/ansimcare-downloads/releases/download/v0.1.0-autoenroll-signed-test.2/app-arm64-v8a-release.apk) 또는 [릴리스 안내 페이지](https://github.com/GrayOM/ansimcare-downloads/releases/tag/v0.1.0-autoenroll-signed-test.2)에서 파일을 받습니다. 이 APK는 위치 동의와 공유 시작 직후 중앙 관제 자동 등록 요청을 전송하도록 수정됐습니다. 환자가 서버 주소, 기기 ID, 인증 토큰을 직접 입력하지 않습니다.

> 이 파일은 release 키로 서명된 시험용 APK입니다. 실환자 운영 배포에는 사용하지 마십시오. release 서명은 debug APK보다 직접 배포 신뢰성을 높이지만, Google Play Protect 경고가 항상 사라진다는 보장은 없습니다. 중앙 관리자 승인과 시험 기기 1대의 전체 등록 흐름을 먼저 확인한 뒤 제한된 검증 용도로만 사용해야 합니다.

## 설치 방법

1. Release 페이지에서 최신 `ARM64` APK 파일을 다운로드합니다.
2. 갤럭시 기기에서 다운로드한 APK를 열고, 설치 안내에 따라 해당 브라우저 또는 파일 앱의 설치 권한을 일시적으로 허용합니다.
3. 앱을 실행하고 안내된 동의 절차를 완료합니다.
4. 중앙 관리자가 대시보드의 승인 대기 목록에서 기기를 환자 프로필에 연결해 승인합니다.

설치 및 운영 중 문제가 발생하면 APK 파일명, 설치 기기 모델, Android 버전, 발생 시각을 중앙 관리자에게 전달해 주세요. APK 파일만 이 저장소에 공개되며, 환자 데이터나 관리자 대시보드는 공개되지 않습니다.

# AVRA Beta

AVRA 소설 집필 앱의 베타 설치 파일과 사용 안내를 배포합니다. 앱 소스 코드는 비공개입니다.

## 다운로드

- **[Windows 0.1.32 — 64비트 설치 파일](https://github.com/ell0420/avra-beta/releases/download/v0.1.32-beta.1/AVRA-0.1.32-Windows-x64-setup.exe)**: 내려받은 `.exe`를 실행하세요.
- **[Mac 0.1.32 — Apple Silicon 설치 파일](https://github.com/ell0420/avra-beta/releases/download/v0.1.32-beta.1/AVRA-0.1.32-macOS-Apple-Silicon.dmg)**: macOS 13.0 이상, M1 이후 Apple Silicon용입니다. `.dmg`를 열어 AVRA를 응용 프로그램 폴더로 옮기세요.
- **[Mac 0.1.32 — Intel Mac(x64) 설치 파일](https://github.com/ell0420/avra-beta/releases/download/v0.1.32-beta.1/AVRA-0.1.32-macOS-Intel.dmg)**: macOS 13.0 이상, Intel Mac(x64)용입니다. `.dmg`를 열어 AVRA를 응용 프로그램 폴더로 옮기세요.

0.1.32 오픈베타는 2027년 2월 10일까지 키 없이 모든 Pro 기능을 쓸 수 있습니다. 다회차 감상 모드(A4·신국판 두 쪽 보기) 긴 문단 잘림 수정, 외부 AI 에이전트(Antigravity · Claude Code · Codex) 로컬 브리지 기본 비활성화(읽기 전용 기본) 및 원고 보호·보안 전면 보강, PC 화면 절반 분할 레이아웃 및 API 키 상태 조회 오류 수정 등을 포함합니다(세부 내역은 [v0.1.32-beta.1 릴리스 노트](https://github.com/ell0420/avra-beta/releases/tag/v0.1.32-beta.1) 참고). 이미 설치한 앱은 **도움말 > 앱 업데이트**에서 0.1.32로 업데이트됩니다(Mac·Windows 공통). '설치 준비가 끝났습니다'가 나올 때까지 기다린 뒤 **지금 설치**를 누르세요. 업데이트가 실패하면 위 설치 파일로 설치하세요. 원고와 설정은 그대로 유지됩니다.

오픈베타 기간에는 체험 없이 모든 Pro 기능을 쓸 수 있습니다. 베타가 끝나면 인터넷에 연결된 첫 실행에서 14일 Pro 체험이 시작되고, 영구 Pro는 별도 발급 키로 활성화합니다. 체험이 끝나도 무료 집필 기능과 원고는 유지됩니다.

소설 모드와 최신 바인더·동기화, 녹음 안정성 및 업데이트 창 개선을 포함합니다. 논문·에이전트 모드는 포함하지 않습니다.

## Mac 설치 안내

0.1.31부터 Mac 버전(Apple Silicon · Intel)은 Apple Developer ID 정식 서명 및 공증을 완료했습니다.

1. 내 Mac에 맞는 `.dmg`(M1 이후는 Apple Silicon, 구형 맥은 Intel)를 열고 AVRA를 **응용 프로그램(Applications)** 폴더로 옮깁니다.
2. 별도 보안 우회 설정 없이 바로 열립니다.

## 베타 안내

Mac은 Apple 정식 공증을 완료했으며(macOS 13.0 이상, Apple Silicon · Intel), Windows는 코드 서명이 없는 베타라 설치 시 "Windows의 PC 보호" 보안 경고가 표시될 수 있습니다(**추가 정보** → **실행**).

Mac 0.1.32는 Apple Silicon 및 Intel Mac 두 DMG의 Apple 공증(`Accepted`)·staple·서명 검증과 패키지 무결성을 확인했습니다(Intel 실기 실행은 미검증). Windows 0.1.32는 GitHub Actions(`windows-2022`)에서 설치·10초 기동 및 0.1.31 → 0.1.32 인앱 덮어 업데이트를 검증했습니다(Windows 실기기 인터랙티브·브리지 동작은 미검증).

각 릴리스의 `SHA256SUMS` 파일로 설치 파일 무결성을 확인할 수 있습니다. 포함된 제3자 구성 요소에는 각각의 라이선스가 적용됩니다.

GitHub의 자동 `Source code (zip)` / `Source code (tar.gz)`는 이 배포 저장소의 안내문 묶음입니다. 앱 설치에는 위의 `.exe` 또는 `.dmg`를 사용하세요.

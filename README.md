# Codepet

<img src="assets/codepet-icon.png" alt="Codepet 앱 아이콘" width="160" />

할 일을 미루면 바탕화면 펫이 말풍선과 행동으로 다시 알려주는 macOS Todo 앱입니다.

[최신 버전 다운로드](https://github.com/081114ysm/Codepet-Downloads/releases/latest)

## 주요 기능

- macOS 메뉴바에서 빠르게 Todo 추가
- `Command + Shift + Space` 전역 빠른 추가
- `보고서 내일 오후 6시` 형태의 한국어 일정 입력
- 25분 집중 타이머와 펫 타이핑·책 읽기·완료 축하
- 마감 5분 전 고정 카운트다운
- 여러 Todo 제목을 빠짐없이 보여주는 순환 말풍선
- 원숭이·고양이·강아지·토끼·곰·펭귄·여우 선택
- 하루 정리와 가벼운 펫 친밀도
- 로그인이나 외부 서버 없이 Mac 내부에만 데이터 저장

## 실행 환경

- Apple Silicon Mac: M1, M2, M3, M4 계열
- 현재 Intel Mac은 지원하지 않습니다.

## 설치 방법

1. [Releases](https://github.com/081114ysm/Codepet-Downloads/releases/latest)에서 `Codepet-1.1.1-mac-arm64.dmg`를 다운로드합니다.
2. DMG를 열고 Codepet을 `응용 프로그램` 폴더로 옮깁니다.
3. 터미널을 열고 아래 명령을 한 번 실행합니다.

```sh
xattr -dr com.apple.quarantine /Applications/Codepet.app
open /Applications/Codepet.app
```

현재 학교 프로젝트 빌드는 중첩 바이너리까지 애드혹 서명했지만 Apple Developer ID 서명과 공증은 하지 않았습니다. 위 명령은 Codepet 앱에만 다운로드 격리 속성을 제거합니다. 출처와 아래 체크섬을 확인한 파일에서만 실행하세요. macOS 전체 Gatekeeper를 끄는 명령은 사용하지 마세요.

[Apple의 미공증 앱 실행 안내](https://support.apple.com/ko-kr/102445)

## 화면

### Todo 작업 창

![Codepet Todo 작업 창](assets/codepet-todo.png)

### 데스크톱 펫

![Codepet 원숭이 펫](assets/codepet-pet.png)

## Codepet 1.1.1 체크섬

다운로드한 파일이 바뀌지 않았는지 확인할 때 사용합니다.

```text
DMG  a367f67292ca21aaf590bbba19239e18bb3b1c4f54cd56956e433addb37f06dd
ZIP  51280645a361f2298447c9cc92af3d3ac02eb9fe9cc46a6bd610ab4ae6634a21
```

## 개인정보

Todo와 설정은 사용자의 Mac 안에만 저장됩니다. 계정, 광고, 분석 SDK, 외부 서버 전송 기능은 없습니다.

설치나 실행 중 문제가 생기면 이 저장소의 [Issues](https://github.com/081114ysm/Codepet-Downloads/issues)에 macOS 버전과 오류 화면을 남겨 주세요.

이 저장소는 설치 파일과 안내 문서만 제공하는 공개 배포 저장소입니다. 개발 소스 저장소는 별도로 관리합니다.

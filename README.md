# FileNic (파일닉)
윈도우와 맥 간의 한글 파일명 호환성 문제를 간단히 해결하는 도구입니다.

## 소개
맥OS 사용자들이 흔히 겪는 한글 파일명 자소분리 현상을 해결합니다. 기존의 복잡한 해결방법들(Automator 등)과 달리, FileNic은 간단한 드래그 앤 드롭으로 문제를 해결합니다.

## 시스템 요구사항
- macOS 13 Ventura 이상
- Apple Silicon 또는 Intel 프로세서

## 주요 기능
- 드래그 앤 드롭으로 즉시 파일명 변환
- 메뉴바 상주 앱으로 언제든 즉시 사용 가능
- 별도 설정 없이 즉시 사용 가능
- 알림으로 변환 결과 확인
- 로그인 시 자동 실행 지원
- 모든 파일 처리는 사용자의 컴퓨터에서 로컬로 진행 (서버 통신 없음)

## 설치 방법
1. [릴리즈 페이지](https://github.com/0126kjw/FileNic/releases/latest)에서 최신 버전의 `FileNic.app.zip` 다운로드
2. 다운로드한 파일의 압축 해제
3. 응용프로그램 폴더로 FileNic.app 이동

## 앱 실행 시 보안 경고 해결 방법
처음 실행 시 "Apple이 개발자를 확인할 수 없기 때문에 열 수 없습니다"라는 보안 경고가 표시될 수 있습니다. 아래 단계를 따라 해결하실 수 있습니다:

1. 시스템 설정(System Settings) 열기
2. '개인정보 보호 및 보안'(Privacy & Security) 선택
3. 화면 우측의 보안(Security) 섹션에서 "Mac을 보호하기 위해 'FileNic'을 차단했습니다." 또는 "이 앱은 확인되지 않은 개발자의 앱입니다..."라는 메시지 확인
4. '그래도 열기' 또는 '확인 없이 열기' (Open Anyway) 버튼 클릭
5. 확인 팝업창에서 '그래도 열기' 또는 '열기'(Open) 선택

## 사용 방법
1. FileNic 실행 시 상단 메뉴바에 아이콘이 생성됩니다.
2. 변환이 필요한 파일을 메뉴바 아이콘으로 드래그 앤 드롭
3. 자동으로 파일명이 변환되어 윈도우와 호환되는 형식으로 저장됩니다.

## 개인정보 보호
- 모든 파일명 변환은 사용자의 로컬 컴퓨터에서만 처리됩니다.
- 외부 서버와의 통신이 전혀 없어 파일 정보가 외부로 유출될 위험이 없습니다.
- 파일의 내용이나 메타데이터는 전혀 수정되지 않으며, 순수하게 파일명만 변환됩니다.

## 주의사항
- 변환 결과 확인을 위해 시스템 알림 권한을 허용해주세요.

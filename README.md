![Downloads](https://img.shields.io/endpoint?url=https://zdxl2n129h.execute-api.ap-northeast-2.amazonaws.com/count)

# FileNic (파일닉)
맥OS와 윈도우 사이의 한글 파일명 호환 문제를 해결하는 간단한 도구입니다.

## 소개
맥OS에서 자주 발생하는 한글 파일명 자소분리 문제를 해결합니다. 기존의 복잡한 설정 대신 FileNic은 간단한 드래그 앤 드롭으로 동작합니다.

### 자소분리 현상이란?
맥OS와 윈도우는 한글을 저장하는 방식이 서로 달라서 호환성 문제가 발생합니다. 예를 들어:
- 맥에서 만든 '안녕.txt' 파일이
- 윈도우에서는 'ㅇㅏㄴㄴㅕㅇ.txt'처럼 보이는 현상

FileNic은 이러한 차이를 자동으로 해결하여 양쪽 운영체제에서 모두 올바르게 표시되도록 합니다.

## 시스템 요구사항
- macOS 13 Ventura 이상
- Apple Silicon 또는 Intel 프로세서

## 주요 기능
- 드래그 앤 드롭으로 즉시 변환
- 파일 및 폴더명 변환 지원
- 폴더 변환 시 하위 파일명 변환 여부 설정 가능
- 메뉴바에서 바로 사용
- 별도 설정 없이 바로 시작
- 알림으로 변환 결과 즉시 확인
- 로그인 시 자동 실행 지원
- 모든 파일 처리는 사용자의 컴퓨터에서 로컬로 진행 (서버 통신 없음)

## 설치 방법
### 앱스토어 공식 설치 (권장)
<a href="https://apps.apple.com/kr/app/%ED%8C%8C%EC%9D%BC%EB%8B%89-%EC%9E%90%EC%86%8C%EB%B6%84%EB%A6%AC-%EC%97%86%EC%9D%B4-%EA%B9%94%EB%81%94%ED%95%98%EA%B2%8C/id6740508269?mt=12&itscg=30200&itsct=apps_box_badge&mttnsubad=6740508269" style="display: inline-block;">
<img src="https://toolbox.marketingtools.apple.com/api/v2/badges/download-on-the-app-store/black/ko-kr?releaseDate=1737676800" alt="Download on the App Store" style="width: 267px; height: 82px; vertical-align: middle; object-fit: contain;" />
</a>
    

### 직접 다운로드
1. [릴리즈 페이지](https://github.com/0126kjw/FileNic/releases/latest)에서 최신 버전 다운로드
2. 다운로드한 파일 압축 해제
3. FileNic.app을 응용프로그램 폴더로 이동

### 향후 지원 예정
- Homebrew

## 사용 방법
> 이제 메뉴바 아이콘 아래 드롭존에서도 변환할 수 있습니다! (v1.0.4)
1. FileNic 실행 시 메뉴바에 아이콘이 나타납니다
2. 변환할 파일이나 폴더를 아이콘이나 드롭존에 끌어다 놓으세요
3. 폴더 변환 시 설정에 따라 폴더명만 또는 하위 파일명까지 변환됩니다
4. 자동으로 윈도우와 호환되는 이름으로 변환됩니다

## 개인정보 보호
- 모든 파일명 변환은 사용자의 로컬 컴퓨터에서만 처리됩니다
- 외부 서버와의 통신이 전혀 없어 파일 정보가 외부로 유출될 위험이 없습니다
- 파일의 내용이나 메타데이터는 전혀 수정되지 않으며, 순수하게 파일명만 변환됩니다

## 주의사항
- 변환 결과 확인을 위해 **시스템 알림** 권한이 필요합니다

## 업데이트 내역
### 2024-01-25:
- App Store 공식 배포 🎉

### 2024-01-15 (v1.0.5):
- 폴더 변환 기능 추가
- 폴더 변환 시 폴더명만 변환할지, 하위 파일명까지 변환할지 선택 가능

### 2024-01-14 (v1.0.4 이상):
- 애플 공식 인증 개발자 서명 적용으로 안전하고 간편한 설치 가능
- 복잡한 보안 설정 과정 없이 바로 실행

### 2024-01-10 (v1.0.4):
- 메뉴바 아이콘 아래 드롭존 추가

# SpringProject

## 프로젝트 개요
이 프로젝트는 전자정부표준프레임워크 eGovFrame-4.2.0 버전에서 Spring MVC, Spring Security 환경으로 만든 회원 홈페이지입니다.

## 주요 기능
- 회원가입
- 로그인
- 로그아웃
- 프로필 사진 업로드
- 게시판 작성, 수정, 삭제
- 권한부여 (권한만 부여 했으며, 다른 기능은 구현되지 않았습니다)
- 회원 정보 수정

## 설치 방법
- 1. GitHub에서 프로젝트 다운로드
GitHub 레포지토리 페이지로 이동하여 "Code" 버튼을 클릭한 후, "Download ZIP"을 선택하여 프로젝트를 다운로드합니다.
또는, Git을 사용하여 클론합니다.

git clone https://github.com/githubjjunyeop/SpringProject
cd SpringProject
- 2. 이클립스에서 프로젝트 가져오기
이클립스를 실행하고, File -> Import -> Existing Projects into Workspace를 선택합니다.
다운로드한 프로젝트 디렉토리를 선택하여 프로젝트를 가져옵니다.

- 3. eGovFrame 설치 및 설정
eGovFrame 개발환경을 설치합니다. (https://www.egovframe.go.kr/)
설치 후 eGovFrame을 이클립스에 통합하고 필요한 플러그인을 설치합니다.
프로젝트의 pom.xml 파일을 확인하여 필요한 라이브러리를 다운로드받습니다.

- 4. 데이터베이스 설정
src/main/resources 디렉토리의 egovframework/spring/com/context-datasource.xml 파일을 열어 데이터베이스 연결 정보를 설정합니다.
필요한 데이터베이스를 생성하고 테이블을 설정합니다.

- 5. 프로젝트 빌드 및 실행
프로젝트를 Clean 및 Build 합니다.
Run -> Run As -> Run on Server를 선택하여 서버를 실행합니다.
브라우저를 열어 http://localhost:8080으로 접근하여 프로젝트가 정상적으로 실행되는지 확인합니다.

## 사용 방법
- 브라우저에서 http://localhost:8080으로 접근합니다.
- 회원가입 페이지에서 새로운 계정을 생성합니다.
- 로그인 페이지에서 생성한 계정으로 로그인합니다.
- 프로필 페이지에서 프로필 사진을 업로드할 수 있습니다.
- 게시판 페이지에서 게시물을 작성, 수정, 삭제할 수 있습니다.
- 관리자 계정으로 로그인하면 다른 사용자에게 권한을 부여할 수 있습니다.

## 기술 스택
- jQuery
- Spring API
- Spring Security
- Spring MVC
- JSTL

## 기여 방법
- 이 레포지토리를 포크합니다.
- 새로운 브랜치를 생성합니다 (git checkout -b feature/새로운기능).
- 변경 사항을 커밋합니다 (git commit -am 'Add 새로운기능').
- 포크한 레포지토리로 푸시합니다 (git push origin feature/새로운기능).
- Pull Request를 생성합니다.

## 라이선스
- 이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 LICENSE 파일을 참고하세요.

작성자 정보
국비학원을 졸업하고 자바 알고리즘 위주의 학습을 끝낸 후 간단한 자바스크립트로 윷놀이, 포커, 오목을 구현하였습니다. 졸업 후에는 Spring 학습을 꾸준히 하고 있습니다.

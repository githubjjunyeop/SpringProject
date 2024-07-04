# 프로젝트 개요

이 프로젝트는 전자정부표준프레임워크(eGovFrame) 4.2.0 버전에서 Spring MVC와 Spring Security 환경으로 만든 회원 홈페이지입니다. 이 프로젝트는 전자정부프레임워크를 활용하여 웹 개발의 기본 기능을 익히고, 회원 관리 시스템을 구축하는 것을 목표로 합니다.

## 목차

- [주요 기능](#주요-기능)
- [설치 방법](#설치-방법)
- [사용 방법](#사용-방법)
- [기술 스택](#기술-스택)
- [기여 방법](#기여-방법)
- [라이선스](#라이선스)
- [작성자 정보](#작성자-정보)

## 주요 기능

- 회원가입
- 로그인 및 로그아웃
- 프로필 사진 업로드
- 게시판 작성, 수정, 삭제
- 권한 부여 (기본적인 권한 설정만 구현)
- 회원 정보 수정

## 설치 방법

### GitHub에서 프로젝트 다운로드

GitHub 레포지토리 페이지로 이동하여 "Code" 버튼을 클릭한 후, "Download ZIP"을 선택하여 프로젝트를 다운로드합니다.
또는, Git을 사용하여 클론합니다.

```bash
git clone https://github.com/githubjjunyeop/SpringProject
cd SpringProject
이클립스에서 프로젝트 가져오기
이클립스를 실행하고, File -> Import -> Existing Projects into Workspace를 선택합니다.
다운로드한 프로젝트 디렉토리를 선택하여 프로젝트를 가져옵니다.

eGovFrame 설치 및 설정
eGovFrame 개발환경을 설치합니다. (https://www.egovframe.go.kr/)
설치 후 eGovFrame을 이클립스에 통합하고 필요한 플러그인을 설치합니다.
프로젝트의 pom.xml 파일을 확인하여 필요한 라이브러리를 다운로드받습니다.

데이터베이스 설정
src/main/resources 디렉토리의 egovframework/spring/com/context-datasource.xml 파일을 열어 데이터베이스 연결 정보를 설정합니다.
필요한 데이터베이스를 생성하고 테이블을 설정합니다.

프로젝트 빌드 및 실행
프로젝트를 Clean 및 Build 합니다.
Run -> Run As -> Run on Server를 선택하여 서버를 실행합니다.
브라우저를 열어 http://localhost:8080으로 접근하여 프로젝트가 정상적으로 실행되는지 확인합니다.

사용 방법
회원가입
홈페이지 메인 화면에서 회원가입 버튼을 클릭하여 회원가입 폼을 작성합니다.

로그인
회원가입 후, 로그인 페이지에서 아이디와 비밀번호를 입력하여 로그인합니다.

프로필 사진 업로드
로그인 후, 프로필 페이지에서 사진을 업로드할 수 있습니다.

게시판 사용
게시판 페이지에서 글을 작성하고 수정하거나 삭제할 수 있습니다.

회원 정보 수정
회원 정보 페이지에서 자신의 정보를 수정할 수 있습니다.

기술 스택
Frontend: jQuery
Backend: Spring MVC, Spring Security
View: JSP, JSTL
Framework: eGovFrame
Database: 설정된 데이터베이스 (context-datasource.xml 참조)
기여 방법
이 프로젝트를 포크(Fork)합니다.
새로운 기능이나 버그 수정을 위한 브랜치(Branch)를 만듭니다.
변경 사항을 커밋(Commit)합니다.
자신의 브랜치로 푸시(Push)합니다.
Pull Request를 엽니다.

라이선스
MIT License

sql
코드 복사
MIT License

Copyright (c) 2024 githubjjunyeop

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
작성자 정보
국비학원을 졸업하고 자바 알고리즘 위주의 학습을 끝낸 후 간단한 자바스크립트로 윷놀이, 포커, 오목을 구현하였고 졸업 후에는 Spring 학습을 꾸준히 하고 있습니다.

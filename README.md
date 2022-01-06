# 🕹 프로젝트 소개
- 나의 첫 개인 프로젝트 : 자기계발 관련 정보를 공유할 수 있는 커뮤니티 홈페이지 만들기
- JSP Model1 기반 홈페이지로 자기계발 관련 활동일지를 게시, 공유합니다.
- 자기계발에 관심있는 사용자는 회원가입을 통해 해당 홈페이지의 회원이 될 수 있습니다.
- 회원이 되면 운동, 독서, 공부 등 자기계발과 관련된 자신의 활동을 게시판에 글과 사진으로 올릴 수 있고, 다른 사용자의 글에 댓글을 달며 소통할 수 있습니다.

## 🔨 제작 동기

![image](https://user-images.githubusercontent.com/92525310/148019946-a7ded44b-7f5c-443b-9fcb-447c6da2e8bf.png)


## 💾 DB 구조

![image](https://user-images.githubusercontent.com/92525310/148019975-b8c1927c-4a0c-462f-88eb-974ca72eb423.png)

## 🔧 개발 환경

![image](https://user-images.githubusercontent.com/92525310/148327918-9da9abe8-0302-49bd-a797-a7ec0d349393.png)

 <개발 툴 버전>
- JavaSE 1.8
- Tomcat ver 8.5
- MySQL Server ver 5.7

## ⌚ 개발 기간
2021년 6월 16일 ~ 2021년 7월 20일

## 🎨 구현 기능

1> 메인 페이지
- HTML/CSS/JSP 등을 이용하여 메인화면 구성
- 로그인 / 회원가입 버튼 구현
- 로그인 시에만 마이페이지를 볼 수 있는 버튼 구성
- 메인 메뉴바 구성

2> 로그인 및 회원가입
- JS함수와 표현식을 활용한 회원가입 유효성 검사
- 회원가입 시 우편주소 api로 주소 불러오기
- 아이디 중복체크 검사
- Open-API를 활용한 소셜로그인 기능 구현
- 비밀번호 찾기 기능 구현

3> 마이페이지
- 회원 정보 조회, 수정, 삭제 및 로그아웃 기능 구현
- 관리자 전용 아이디로 로그인 시 전체 회원정보 조회 가능

4> 게시판 
- 기본적인 CRUD 기능 구현
- 답글 기능 들여쓰기 구현
- 페이징 처리 및 최신글 순 출력 구현
- 세션값을 활용한 아이디 검증
- 본인 글에서만 수정,삭제 버튼 활성화

5> 갤러리 게시판
- 글 목록에서 이미지 미리보기
- 작성일과 NOW()함수 비교로 NOW 이미지 삽입
- 글쓰기 시 파일 첨부 기능
- 게시판에서 파일 다운로드 기능

6> 기타
- 카카오 OPEN-API 활용 다국어 번역기
- 문의사항에서 구글 SMTP 서버를 활용한 메일 전송 기능 구현


## 차후 보완점

![image](https://user-images.githubusercontent.com/92525310/148328661-4d901319-9826-4256-9727-06ec37ea01be.png)

## ✨프로젝트 참고 페이지
1) https://postcode.map.daum.net/guide#usage
2) https://developers.kakao.com/
3) https://juyoungit.tistory.com/164
4) https://academy.dream-coding.com/courses/portfolio (강의 영상 참조)
5) https://fontawesome.com/
6) https://www.youtube.com/watch?v=QPEUU89AOg8 (강의 영상 참조)



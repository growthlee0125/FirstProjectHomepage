# FirstProjectHomepage
첫 프로젝트 - 개인 홈페이지 만들기 

![image](https://user-images.githubusercontent.com/92525310/148019946-a7ded44b-7f5c-443b-9fcb-447c6da2e8bf.png)

![image](https://user-images.githubusercontent.com/92525310/148019975-b8c1927c-4a0c-462f-88eb-974ca72eb423.png)

## 기획사항
1. 주제 : 자기계발 정보공유 커뮤니티

2. 사용 언어 및 기술
- JavaSE - 1.8
- JSP
- JavaScript
- HTML
- CSS
- Jquery
- Tomcat ver 8.5
- MySQL Server ver 5.7

## 기간
2021년 6월 16일 ~ 2021년 7월 20일

## 구현 기능

1> 회원가입
- js함수와 표현식을 활용한 회원가입 유효성 검사
- 회원가입 시 우편주소 api로 주소 불러오기
- 아이디 중복체크 검사
- 로그인
- Open-API를 활용한 소셜로그인 기능 구현
- DAO를 활용한 DB접근으로 로그인 유효성 검증 및 비밀번호 찾기

2> 마이페이지
- 회원 정보 조회, 수정, 삭제 및 로그아웃 기능
- 관리자 전용 전체 회원정보 조회
- 게시판 CRUD
- 게시판 기본적인 CRUD 구현
- 답글 들여쓰기 기능, 페이징 처리 및 최신글 순 출력 구현
- 세션값을 활용한 아이디 검증
- 본인 글에서만 수정,삭제 버튼 활성화

3> 갤러리 게시판
- 글 목록에서 이미지 미리보기
- 작성일과 NOW()함수 비교로 NOW 이미지 삽입
- 글쓰기 파일 첨부 기능
- 언어번역기
- 카카오 OPEN-API 활용 다국어 번역기

4>문의
- 구글 SMTP 서버를 활용한 메일 전송 기능 구현

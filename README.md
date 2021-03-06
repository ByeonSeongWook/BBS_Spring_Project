# BBS Spring Project
---

## 1. 프로젝트 소개

- Spring 으로 MVC 패턴을 이해하며 공부하면서 만든 게시판 프로젝트입니다.

<br/><br/>
## 2. 기능 소개

- 회원 가입, 로그인, 게시판(insert, select, update, delete), 게시판 view (댓글, 공감하기 카운트, 조회 수 카운트), 페이징 처리
- 회원가입 시 modal을 사용해서 이메일 인증, 주소 찾기 API를 사용했습니다.
- 게시판은 내용에 XSS 처리, 작성자만 수정, 삭제를 할 수 있게 만들었습니다.
- 게시물에는 파일 업로드, 댓글은 작성자만 삭제할 수 있도록 만들었습니다.
- 댓글을 등록, 공감버튼 클릭시 ajax 비동기 통신으로 처리해서 처리한 내용을 바로 볼 수 있게 만들었습니다.
- 페이징 처리는 한 페이지당 게시물 10개, 목록 5개  까지만 보이게 처리했습니다.

<br/><br/>
## 3. 사용 기술

<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/> <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/> <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white"/>

<br/><br/>

## 4. 소요 기간

- 21.12.06 ~ 21.12.13(1주일)

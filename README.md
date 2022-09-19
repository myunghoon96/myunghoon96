# 🙋🏻‍♂️조명훈

- 안녕하세요. 신입 **백엔드** 개발자 **조명훈**입니다.
- 소통하고 협업하는 것을 좋아합니다.
- 튼튼한 기초를 바탕으로 끊임없이 성장하는 개발자가 되는 것이 목표입니다.

# ✉ Contact

- Email   | qkdlqkdl44@naver.com
- Github | [https://github.com/myunghoon96](https://github.com/myunghoon96)

# 🚵🏻‍♂️ Career

- F&F 프로세스팀 사원 *(2022.03* ~  *2022.05)*
- F&F 프로세스팀 인턴 *(2022.01* ~  *2022.03)*

---

# 🛠 Skills

## 💻  Backend

- Spring

## 💻 Frontend

- React

---

# **🖥Projects**

**🌱Community Toy Project** **([https://hoon.ml](https://hoon.ml/))**

- [ ]  **22.09 ~ Current**

**로그인, 게시글, 댓글, 랭킹 기능을 구현한 Spring, React 기반의 커뮤니티 개인 토이 프로젝트입니다.**

- JWT 토큰 인증 방식을 사용하였으며 웹 브라우저의 쿠키에 저장하였습니다. 보안을 고려하여 짧은 유효 기간을 가진 access token과 긴 유효 기간을 가진 refresh token을 사용하였습니다.
- 회원, 게시글, 댓글 엔티티에 공통으로 필요한 생성일자, 수정일자는 BaseTimeEntity 추상 클래스를 작성하고 상속받아 코드의 중복을 최소화하였습니다.
- 데이터 유효성 검증을 위해서 @Valid 어노테이션을 사용하였습니다.
- 일관성 있는 api 응답을 하기 위해서 ApiResponse 클래스를 작성하여 사용하였으며 적절한 에러 메시지를 응답하기 위해서 @ExceptionHandler와 CustomAuthenticationEntryPoint를 사용하였습니다.
- Redis를 사용하여 조회 수 기반의 게시글 랭킹을 구현하였고, 조회 수 업데이트의 경우 DB 부하를 줄이기 위해서 write back 패턴을 적용하였습니다.
- Junit5을 사용하여 테스트 코드를 작성하고 있습니다.
- 프론트엔드에서 api 요청 시 콘텐츠 타입, 토큰과 같이 중복되는 코드를 줄이기 위해서 axios를 모듈화하였습니다. silent refresh와 api 인증 관련 에러를 처리하기 위해서 axios interceptor를 사용하였습니다.

---

🏢 **Back Office Dashboard / Blog** 

- [x]  **22.01 ~ 22.05**

**대시보드, 블로그 기능을 구현한 React, FastAPI 기반의 개인 프로젝트입니다.**

- 데이터들을 적절하게 테이블, 라인, 파이, 바, 지도 차트 등으로 시각화하였습니다.
- 트리형 챗봇, PDF 미리 보기, 게시판, 파일 버전 관리, 업무 담당자 조회 등 기능을 구현하였습니다.

---

# 🎓 Education

## 연세대학교 컴퓨터과학과

*2015.03* ~ *2022.02 (졸업 )*

---

# 💬 Etc

## 📚 Learning

- [인프런] 우아한형제들 개발팀장 김영한의 스프링 완전 정복 로드맵
- [인프런] 김영한의 스프링 부트와 JPA 실무 완전 정복 로드맵

## 🗣 Languages

- 영어 🇺🇸
    - TOIEC SPEAKING, Score: 150, Level: IH
- 중국어 🇨🇳

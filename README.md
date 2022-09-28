# toy_validation_check

정규표현식을 통해서 입력 유효성을 검사하는 간단한 로그인 or 회원가입 페이지입니다.

# 개발환경

- react 최신 버젼(18.2.0) / react-router-dom 최신 버젼

# 필요한 파일

+— src

+— Page

+— Signin.js  (로그인 페이지)

+— Signin.css 

+— Signup.js (회원가입 페이지)

+— Signup.css

+— App.js

# 요구사항

컴포넌트 명은 파일명으로 일치

### SignIn Page

— 아이디 입력 엘리먼트 필요 (클래스명 : signin_userid)

— 비밀번호 입력 엘리먼트 필요 (클래스명 : signin_password)

— 로그인 Button 필요

— ‘react_router_dom’ 을 통해 회원가입 페이지로 이동(회원가입 페이지 url은 ‘/signup’)

validate

— 아이디 입력 폼에 값이 있는지 확인

— 비밀번호 입력 폼에 값이 있는지 확인

— 버튼 눌렀을 때 각각에 해당하는 안내문구 출력(alert는 되도록 지양)

### SignUp Page

— 아이디 입력 엘리먼트 필요 (클래스명 : signup_userid)

— 비밀번호 입력 엘리먼트 필요 (클래스명 : signup_password)

— 비밀번호 확인 입력 엘리먼트 필요 (클래스명 : signup_password_confirm)

— 이메일 주소 입력 엘리먼트 필요 (클래스명 : signup_email)

— 전화번호 입력 엘리먼트 필요 (클래스명 : signup_phonenumber)

— (선택) 주소 API 불러와 우편번호, 주소, 상세주소 뿌리는 입력 엘리먼트 생성

—  회원가입 Button 필요

— ‘react_router_dom’ 을 통해 로그인 페이지로 이동(회원가입 페이지 url은 ‘/’)

validate

— 아이디 입력 (영어 알파벳 소문자 대문자), (숫자 )만 입력하게 정규표현으로 검사

— 비밀번호 입력 적어도 영어 알파벳 소문자 1개, 영어 알파벳 대문자 1개, 숫자 1개, 특수문자(!,@,#,$,%,^,&,*) 1개 씩 포함, 정규표현으로 검사

— 이메일 주소 입력 이메일 형태에 맞게 정규표현으로 검사 (모든 이메일 형태에 일치해야 함.)

— 전화번호 입력 정규표현으로 검사(010-1234-1234 의 형식으로 입력 검사)

— 모든 검사에서 불일치 시 안내문구 출력

# 개발 업무 내용

## — 컴포넌트 및 HTML 개발 / 인원 1명

## — CSS 디자인 / 인원 1명

## — Validation 함수 개발 / 인원 1명
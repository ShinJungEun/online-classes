### 강의
> 누구나 따라하면서 배우는 JSP 커뮤니티 게시판 만들기  
> JSP를 활용한 웹 사이트 개발

💡link: https://www.inflearn.com/course/jsp-%EA%B2%8C%EC%8B%9C%ED%8C%90/dashboard

<br/>
 
### 개발환경
- IDE: Eclipse
- JDK: JDK 1.8
- Tomcat: Tomcat v8.5

<br/>

### Dev Stack
- JAVA 8
- jsp
- HTML/css (Bootstrap)

 <br/>

### 내용
#### 1) mysql 설치, DB 및 테이블 생성
 : mysql Database를 설치하여 회원 관리를 위한 user 테이블 생성

![image](https://github.com/ShinJungEun/online-classes/assets/38749778/7fd6e178-d667-49e5-b376-f448c04b8fb4)

※ 참고
```
SHOW DATABASES; -- DB 리스트 조회
USE 'DB이름'; -- 해당 DB로 이동
SHOW TABLES; -- DB TABLE 리스트 조회
```
![image](https://github.com/ShinJungEun/online-classes/assets/38749778/08238af8-5a93-412a-b71a-efe2f4bb9a1b)


#### 2) eclipse Dynamic Web Project 생성 
 : Tomcat 연결, mysql 연결 및 localhost Test

#### 3) login 화면, join 화면 구현
 : 회원 가입을 할 수 있는 join 화면과, 로그인할 수 있는 login 화면 구현
 - join 화면에서 회원 가입 시 데이터 검증 및 회원 정보를 DB에 INSERT 하는 기능 구현
 - login 화면에서 로그인 시, 기존 가입 회원인지 DB에서 검증하여 로그인하는 기능 구현

#### 4) session 부여 및 logout 기능 구현
 : 로그인 시, session을 부여하여 관리하고, 로그아웃 시 session을 제거하는 기능 구현

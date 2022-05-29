## 스파르타 코딩클럽 Spring 심화반 프로젝트 - 나만의 쇼핑몰

#### 기능

- 아이디/비밀번호 회원가입, 로그인과 OAuth2를 이용한 카카오 로그인
- 네이버 쇼핑 API를 이용한 상품 검색 및 최저가 알림을 위한 목표 가격 설정
- 상품을 보관할 수 있는 폴더 기능
- (관리자) 사용자가 등록한 상품을 모두 볼 수 있는 기능

#### 사용 기술

- Spring Boot
  - CRUD를 위한 API와 기본 애플리케이션 작동을 위해 사용하였습니다.
- Spring Data JPA
  - 데이터의 CRUD를 위해 사용하였습니다.
- Spring Security
  - 로그인과 일반 사용자와 관리자 권한 구별을 위해 사용하였습니다.
- JUnit
  - 테스트 케이스 작성을 위해 사용하였습니다.
- Thymeleaf
  - 쇼핑몰 페이지를 위하여 사용하였습니다.
- Rest Template
  - 네이버 쇼핑 API를 이용하기 위해 사용하였습니다.
- OAuth2
  - 카카오 로그인 지원을 위해 사용하였습니다.

#### 경험

- API를 구현해봄으로써 Controller와 Service, Repository의 분할에 대해 알게 되었습니다.
- JUnit 을 통해 테스트 케이스를 작성해보면서 테스트 케이스의 작성법과 중요성을 알게 되었습니다.
- 스프링의 IOC/DI를 경험해보았습니다.
- 시간 측정을 위한 AOP를 구현하여 AOP의 사용 방식을 알게 되었습니다.
- Spring Data JPA를 이용하여 보다 간편하게 데이터베이스 CRUD를 경험하였습니다.
- 카카오 로그인을 구현해봄으로써 OAuth2가 무엇인지 알게 되었습니다.

#### 작동 화면

![image](https://user-images.githubusercontent.com/71131071/149718421-447eddd5-f36a-410c-b806-a17002659858.png)
![image](https://user-images.githubusercontent.com/71131071/149718657-e398b84d-5e43-4928-810c-d2ea78b689ca.png)
![image](https://user-images.githubusercontent.com/71131071/149718688-dc20506e-3f43-41f5-b73b-193c24c072ed.png)

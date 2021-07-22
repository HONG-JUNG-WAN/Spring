# Spring Boot 개인 스터디

> Spring Boot, 웹 MVC, DB 접근 기술, 마지막 수정 : 07.22
<br>

  * 개발 환경 : Java 11, IDE : IntelliJ


## UML
 
 * 7.17 👉 7.23일 수정 예정
 
    ![스크린샷(1069)](https://user-images.githubusercontent.com/76596316/125999263-a153744a-0c7c-4acd-90af-ef94cf0f9e15.png)

## 업데이트 내역

* 0.2.3
  * 추가 : [feat] SpringDataJpaMemberRepository
  * 수정 : [style] MemberServiceIntegrationTest
  * 수정 : [refactor] SpringConfig

* 0.2.3
  * 추가 : [feat] JpaMemberRepository
  * 설명 : JdbcTemplate -> JPA

* 0.2.3
  * 추가 : [feat] JdbcTemplateMemberRepository
  * 설명 : 순수 Jdbc -> Spring JdbcTemplate
  * 추가 : [refactor] SpringConfig
  * 설명 : see comments

* 0.2.2
  * 추가 : [test] MemberServiceIntegrationTest
  * 설명 : Integration test by connecting Spring Container and DB

* 0.2.1
  * 추가 : [feat] JdbcMemberRepository, [feat] SpringConfig
  * 설명 : Spring DB access technology - 순수 JDBC, SpringConfig update

* 0.2.0
  * 추가 : [feat] JdbcMemberRepository, [update] build.gradle, [update] resources/application.properties
  * 설명 : jdbc, h2 add DB related library, spring boot add DB connection settings
  
* 0.1.9
  * 추가 : [feat] sql/ddl.sql 
  * 설명 : Spring DB access technology

* 0.1.8
  * 추가 : [feat] MemberController, memberList

* 0.1.7
  * 추가 : [feat] MemberForm, MemberController, createMemberForm.html
  * 설명 : sign up

* 0.1.6
  * 추가 : [feat] HomeController, [feat] home.html
  * 설명 : add home screen
   
* 0.1.5
  * 추가 : [feat] MemberController
  * 업데이트 : [feat] MemberService, MemoryMemberRepository
  * 설명 : Registering Spring Beans directly using Java code

* 0.1.4
  * 추가 : [feat] MemberController
  * 업데이트 : [refactor] MemberService, MemoryMemberRepository

* 0.1.3
  * 업데이트 : [fix] update MemberServiceTest 

* 0.1.2
  * 업데이트 : [refactor] update MemberService
  * 추가 : [test] MemberServiceTest

* 0.1.1
  * commit 태그 규칙에 맞게 수정
  * 추가 : [feat] MemberService class implementation

* 0.1.0
  * 첫 업데이트 
  * 추가 : 'domain' 패키지 추가
  * 업데이트 : 'repository' 패키지 update
  * 업데이트 : 'test code'  update

* 0.0.1
  * spring study01 project 생성 

## 정보

홍정완 – [cs 블로그 @velog 주소](https://velog.io/@daydream) - hjw43ok@hs.ac.kr

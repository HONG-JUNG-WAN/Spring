# Spring Boot 개인 스터디

> Spring Boot, 웹 MVC, DB 접근 기술, 마지막 수정 : 07.17
<br>

  * 개발 환경 : Java 11, IDE : IntelliJ


## UML
 
 * 7.17
 
 <?xml version="1.0" encoding="UTF-8"?>
<class-diagram version="1.2.4" icons="true" always-add-relationships="false" generalizations="true" realizations="true" 
  associations="true" dependencies="false" nesting-relationships="true" router="FAN">  
  <class id="1" language="java" name="hello.hellospring.HelloSpringApplicationTests" project="Spring" 
    file="/Spring/hello-spring/src/test/java/hello/hellospring/HelloSpringApplicationTests.java" binary="false" 
    corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="105" y="643"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="2" language="java" name="hello.hellospring.repository.MemoryMemberRepositoryTest" project="Spring" 
    file="/Spring/hello-spring/src/test/java/hello/hellospring/repository/MemoryMemberRepositoryTest.java" 
    binary="false" corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="464" y="692"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="3" language="java" name="hello.hellospring.service.MemberServiceIntegrationTest" project="Spring" 
    file="/Spring/hello-spring/src/test/java/hello/hellospring/service/MemberServiceIntegrationTest.java" binary="false" 
    corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="171" y="976"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="4" language="java" name="hello.hellospring.service.MemberServiceTest" project="Spring" 
    file="/Spring/hello-spring/src/test/java/hello/hellospring/service/MemberServiceTest.java" binary="false" 
    corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="426" y="909"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="5" language="java" name="hello.hellospring.service.MemberService" project="Spring" 
    file="/Spring/hello-spring/src/main/java/hello/hellospring/service/MemberService.java" binary="false" 
    corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="852" y="1031"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="6" language="java" name="hello.hellospring.repository.MemoryMemberRepository" project="Spring" 
    file="/Spring/hello-spring/src/main/java/hello/hellospring/repository/MemoryMemberRepository.java" binary="false" 
    corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="884" y="785"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <interface id="7" language="java" name="hello.hellospring.repository.MemberRepository" project="Spring" 
    file="/Spring/hello-spring/src/main/java/hello/hellospring/repository/MemberRepository.java" binary="false" 
    corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="300" y="385"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </interface>  
  <class id="8" language="java" name="hello.hellospring.repository.JdbcTemplateMemberRepository" project="Spring" 
    file="/Spring/hello-spring/src/main/java/hello/hellospring/repository/JdbcTemplateMemberRepository.java" 
    binary="false" corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="663" y="363"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="9" language="java" name="hello.hellospring.repository.JdbcMemberRepository" project="Spring" 
    file="/Spring/hello-spring/src/main/java/hello/hellospring/repository/JdbcMemberRepository.java" binary="false" 
    corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="296" y="159"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="10" language="java" name="hello.hellospring.domain.Member" project="Spring" 
    file="/Spring/hello-spring/src/main/java/hello/hellospring/domain/Member.java" binary="false" corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="1021" y="514"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="11" language="java" name="hello.hellospring.controller.MemberForm" project="Spring" 
    file="/Spring/hello-spring/src/main/java/hello/hellospring/controller/MemberForm.java" binary="false" 
    corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="1233" y="486"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="12" language="java" name="hello.hellospring.controller.MemberController" project="Spring" 
    file="/Spring/hello-spring/src/main/java/hello/hellospring/controller/MemberController.java" binary="false" 
    corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="1278" y="906"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="13" language="java" name="hello.hellospring.controller.HomeController" project="Spring" 
    file="/Spring/hello-spring/src/main/java/hello/hellospring/controller/HomeController.java" binary="false" 
    corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="1243" y="744"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="14" language="java" name="hello.hellospring.controller.HelloController.Hello" project="Spring" 
    file="/Spring/hello-spring/src/main/java/hello/hellospring/controller/HelloController.java" binary="false" 
    corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="1439" y="712"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="15" language="java" name="hello.hellospring.controller.HelloController" project="Spring" 
    file="/Spring/hello-spring/src/main/java/hello/hellospring/controller/HelloController.java" binary="false" 
    corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="1458" y="521"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="16" language="java" name="hello.hellospring.SpringConfig" project="Spring" 
    file="/Spring/hello-spring/src/main/java/hello/hellospring/SpringConfig.java" binary="false" corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="1062" y="277"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <class id="17" language="java" name="hello.hellospring.HelloSpringApplication" project="Spring" 
    file="/Spring/hello-spring/src/main/java/hello/hellospring/HelloSpringApplication.java" binary="false" 
    corner="BOTTOM_RIGHT">    
    <position height="-1" width="-1" x="1305" y="293"/>    
    <display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
      sort-features="false" accessors="true" visibility="true">      
      <attributes public="true" package="true" protected="true" private="true" static="true"/>      
      <operations public="true" package="true" protected="true" private="true" static="true"/>    
    </display>  
  </class>  
  <realization id="18">    
    <end type="SOURCE" refId="6"/>    
    <end type="TARGET" refId="7"/>  
  </realization>  
  <association id="19">    
    <end type="SOURCE" refId="3" navigable="false">      
      <attribute id="20" name="memberService"/>      
      <multiplicity id="21" minimum="0" maximum="1"/>    
    </end>    
    <end type="TARGET" refId="5" navigable="true"/>    
    <display labels="true" multiplicity="true"/>  
  </association>  
  <association id="22">    
    <end type="SOURCE" refId="12" navigable="false">      
      <attribute id="23" name="memberService"/>      
      <multiplicity id="24" minimum="0" maximum="1"/>    
    </end>    
    <end type="TARGET" refId="5" navigable="true"/>    
    <display labels="true" multiplicity="true"/>  
  </association>  
  <realization id="25">    
    <end type="SOURCE" refId="8"/>    
    <end type="TARGET" refId="7"/>  
  </realization>  
  <nesting id="26">    
    <end type="SOURCE" refId="15"/>    
    <end type="TARGET" refId="14"/>  
  </nesting>  
  <association id="27">    
    <end type="SOURCE" refId="4" navigable="false">      
      <attribute id="28" name="memberService"/>      
      <multiplicity id="29" minimum="0" maximum="1"/>    
    </end>    
    <end type="TARGET" refId="5" navigable="true"/>    
    <display labels="true" multiplicity="true"/>  
  </association>  
  <association id="30">    
    <end type="SOURCE" refId="3" navigable="false">      
      <attribute id="31" name="memberRepository"/>      
      <multiplicity id="32" minimum="0" maximum="1"/>    
    </end>    
    <end type="TARGET" refId="7" navigable="true"/>    
    <display labels="true" multiplicity="true"/>  
  </association>  
  <association id="33">    
    <end type="SOURCE" refId="4" navigable="false">      
      <attribute id="34" name="memberRepository"/>      
      <multiplicity id="35" minimum="0" maximum="1"/>    
    </end>    
    <end type="TARGET" refId="6" navigable="true"/>    
    <display labels="true" multiplicity="true"/>  
  </association>  
  <association id="36">    
    <end type="SOURCE" refId="2" navigable="false">      
      <attribute id="37" name="repository"/>      
      <multiplicity id="38" minimum="0" maximum="1"/>    
    </end>    
    <end type="TARGET" refId="6" navigable="true"/>    
    <display labels="true" multiplicity="true"/>  
  </association>  
  <realization id="39">    
    <end type="SOURCE" refId="9"/>    
    <end type="TARGET" refId="7"/>  
  </realization>  
  <association id="40">    
    <end type="SOURCE" refId="5" navigable="false">      
      <attribute id="41" name="memberRepository"/>      
      <multiplicity id="42" minimum="0" maximum="1"/>    
    </end>    
    <end type="TARGET" refId="7" navigable="true"/>    
    <display labels="true" multiplicity="true"/>  
  </association>  
  <association id="43">    
    <end type="SOURCE" refId="6" navigable="false">      
      <attribute id="44" name="store"/>      
      <multiplicity id="45" minimum="0" maximum="2147483647"/>    
    </end>    
    <end type="TARGET" refId="10" navigable="true"/>    
    <display labels="true" multiplicity="true"/>  
  </association>  
  <classifier-display autosize="true" stereotype="true" package="true" initial-value="false" signature="true" 
    sort-features="false" accessors="true" visibility="true">    
    <attributes public="true" package="true" protected="true" private="true" static="true"/>    
    <operations public="true" package="true" protected="true" private="true" static="true"/>  
  </classifier-display>  
  <association-display labels="true" multiplicity="true"/>
</class-diagram>



## 업데이트 내역

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

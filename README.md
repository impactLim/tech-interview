# Tech Interview

**기술 면접 대비를 위한 기본 개념을 정리하는 Repository 입니다.**
> :star: 내용에 오류가 있거나 추가할 내용이 있다면 Pull Request를 통해서 알려주시면 감사하겠습니다.
> <br> :star: Star나 Watching를 통한 많은 관심 부탁드립니다. :)

<div align=center>

[![author](https://img.shields.io/badge/author-WeareSoft-red.svg)](https://github.com/WeareSoft)
[![HeeBlog](https://img.shields.io/badge/blog-Hee-lightgrey.svg)](https://gmlwjd9405.github.io/)
[![DoyBlog](https://img.shields.io/badge/blog-Doy-lightgrey.svg)](https://doooyeon.github.io/)
[![NesoyBlog](https://img.shields.io/badge/blog-Nesoy-lightgrey.svg)](https://nesoy.github.io/)
[![DelfBlog](https://img.shields.io/badge/blog-Delf-lightgrey.svg)](https://delf-lee.github.io/)
[![contributors](https://img.shields.io/badge/contributors-4-yellowgreen.svg)](https://github.com/WeareSoft/tech-interview/graphs/contributors)
[![HitCount](http://hits.dwyl.io/WeareSoft/tech-interview.svg?style=popout)](http://hits.dwyl.io/WeareSoft/tech-interview)

</div>


**:book: Contents**
1. [Data Structure](#1-data-structure)
2. [Network](#2-network)
3. [Operating System](#3-operating-system)
4. [Database](#4-database)
5. [Design Pattern](#5-design-pattern)
6. [Algorithm](#6-algorithm)
7. [Java](#7-java)
8. [JavaScript](#8-javascript)
9. [Spring](#9-spring)
10. [Security](#10-security)
11. [ETC](#11-etc)

---

## 1. Data Structure
:arrow_forward: [답변 내용](/contents/datastructure.md)
* Array
* LinkedList
* HashTable
* Stack
* Queue
* Graph
* Tree
* 그래프(Graph)와 트리(Tree)의 차이점
* Binary Heap
* Red-Black Tree
* B+ Tree

## 2. Network
:arrow_forward: [답변 내용](/contents/network.md)
* OSI 7계층
* TCP/IP의 개념
* TCP와 UDP
* TCP와 UDP의 헤더 분석
* TCP의 3-way-handshake와 4-way-handshake
  * Q. TCP의 연결 설정 과정(3단계)과 연결 종료 과정(4단계)이 단계가 차이나는 이유?
  * Q. 만약 Server에서 FIN 플래그를 전송하기 전에 전송한 패킷이 Routing 지연이나 패킷 유실로 인한 재전송 등으로 인해 FIN 패킷보다 늦게 도착하는 상황이 발생하면 어떻게 될까?
  * Q. 초기 Sequence Number인 ISN을 0부터 시작하지 않고 난수를 생성해서 설정하는 이유?
* HTTP와 HTTPS
* HTTP 요청/응답 헤더
* CORS란
* GET 메서드와 POST 메서드
* 쿠키(Cookie)와 세션(Session)
* DNS
* REST와 RESTful의 개념
* 소켓(Socket)이란
* Socket.io와 WebSocket의 차이
* Frame, Packet, Segment, Datagram

## 3. Operating System
:arrow_forward: [답변 내용](/contents/os.md)
* 프로세스와 스레드의 차이(Process vs Thread)
* 멀티 프로세스 대신 멀티 스레드를 사용하는 이유
* Thread-safe
* 동기화 객체의 종류
* 뮤텍스와 세마포어의 차이
* 스케줄러
* 동기와 비동기
* 프로세스 동기화
* 메모리 관리 전략
* 가상 메모리
* 캐시의 지역성
* 교착상태(데드락, Deadlock)의 개념과 조건
* 사용자 수준 스레드와 커널 수준 스레드
* 외부 단편화와 내부 단편화
* Context Switching
* Swapping

## 4. Database
:arrow_forward: [답변 내용](/contents/db.md)
* 데이터베이스 풀
* 정규화(1차 2차 3차 BCNF)
* 트랜잭션(Transaction) 이란
* 트랜잭션 격리 수준(Transaction Isolation Level)
* Join
* SQL injection
* Index란
* Statement와 PrepareStatement
* RDBMS와 NoSQL
* 효과적인 쿼리 저장
* 옵티마이저(Optimizer)란
* Replication
* 파티셔닝(Partitioning)
* 샤딩(Sharding)
* 객체 관계 매핑(Object-relational mapping, ORM)이란
* java JDBC

## 5. Design Pattern
:arrow_forward: [답변 내용](/contents/designpattern.md)
* 디자인 패턴의 개념과 종류
* Singleton 패턴
* Strategy 패턴
* Template Method 패턴
* Factory Method 패턴
* MVC1 패턴과 MVC2 패턴

## 6. Algorithm 
### :pushpin: [관련 링크](https://github.com/WeareSoft/algorithm-study)
:arrow_forward: [답변 내용](/contents/algorithm.md)
* BigO
* DFS와 BFS의 차이
* Fibonacci에서의 세 가지(Recursion, Dynamic Programming, 반복) 방식에 대한 시간복잡도와 공간복잡도 차이
* 정렬 알고리즘의 종류와 개념
* 최소 신장 트리(MST, Minimum Spanning Tree)란
* Kruskal MST 알고리즘
* Prim MST 알고리즘

## 7. Java
:arrow_forward: [답변 내용](/contents/java.md)
* java 프로그래밍이란
* Java SE와 Java EE 애플리케이션 차이
* java와 c/c++의 차이점
* java 언어의 장단점
* java의 접근 제어자의 종류와 특징
* java의 데이터 타입
* Wrapper class
* OOP의 4가지 특징
  * 추상화(Abstraction), 캡슐화(Encapsulation), 상속(Inheritance), 다형성(Polymorphism)
* OOP의 5대 원칙 (SOLID)
* 객체지향 프로그래밍과 절차지향 프로그래밍의 차이
* 객체지향(Object-Oriented)이란
* java의 non-static 멤버와 static 멤버의 차이
  * Q. java의 main 메서드가 static인 이유
* java의 final 키워드 (final/finally/finalize)
* java의 제네릭(Generic)과 c++의 템플릿(Template)의 차이
* java의 가비지 컬렉션(Garbage Collection) 처리 방법
* java 직렬화(Serialization)와 역직렬화(Deserialization)란 무엇인가
* 클래스, 객체, 인스턴스의 차이
* 객체(Object)란 무엇인가
* 오버로딩과 오버라이딩의 차이(Overloading vs Overriding)
* Call by Reference와 Call by Value의 차이
* 인터페이스와 추상 클래스의 차이(Interface vs Abstract Class)
* JVM 구조
* Java Collections Framework
  * java Map 인터페이스 구현체의 종류
  * java Set 인터페이스 구현체의 종류
  * java List 인터페이스 구현체의 종류
* Annotation
* String, StringBuilder, StringBuffer
* 동기화와 비동기화의 차이(Syncronous vs Asyncronous)
* java에서 '=='와 'equals()'의 차이
* java의 리플렉션(Reflection) 이란

## 8. JavaScript
:arrow_forward: [답변 내용](/contents/javascript.md)
* JavaScript Event Loop
* 함수 선언식과 함수 표현식
* 화살표 함수(Arrow Function)
* 향상된 객체 리터럴(Enhanced Object Literals)
* Modules
* 디스트럭처링(Destructuring)
* 전개 연산자(Spread Operator)
* 호이스팅(Hoisting)
* Closure
* this
* Promise
* Async/Await

## 9. Spring
:arrow_forward: [답변 내용](/contents/spring.md)
* 스프링 프레임워크란
* Spring, Spring MVC, Spring Boot의 차이
* Container란
* IOC(Inversion of Control, 제어의 역전)란
* MVC 패턴이란
* DI(Dependency Injection, 의존성 주입)란
* AOP(Aspect Oriented Programming)란
* POJO
* DAO와 DTO의 차이
* Spring JDBC를 이용한 데이터 접근

## 10. Security 
:arrow_forward: [답변 내용](/contents/security.md)
* 대칭키와 비대칭키 차이
* 패스워드 암호화 방법 
* SQL Injection 공격 
* CSRF 공격 
* XSS 공격 

## 11. ETC
:arrow_forward: [답변 내용](/contents/etc.md)
* TDD란
* 웹 브라우저에서 서버로 어떤 페이지를 요청하면 일어나는 일련의 과정을 설명
  * Ex. url에 'www.naver.com' 을 입력했다. 일어나는 현상에 대해 아는대로 설명하라.
* 컴파일러와 인터프리터
* 분산락
* 프레임워크와 라이브러리의 차이
* 64bit CPU와 32bit CPU 차이
* CVS, SVN, Git
* Git Branch 종류(5가지)
* 웹 서버(Web Server)와 웹 어플리케이션 서버(WAS)의 차이
* 애자일 방법론이란
* Servlet과 JSP
* Memcached와 Redis의 차이
* Maven과 Gradle의 차이 

---

# Reference
* [jojoldu님의 junior-recruit-scheduler](https://github.com/jojoldu/junior-recruit-scheduler/blob/master/README.md)
* [JaeYeopHan 님의 Interview_Question_for_Beginner](https://github.com/JaeYeopHan/Interview_Question_for_Beginner)
* [KimHunJin님의 Study-Book/interview](https://github.com/KimHunJin/Study-Book/tree/master/interview)
* [TaeMInMoon님의 신입 개발자 기술면접](https://trello.com/b/BWtpfywH/%EC%8B%A0%EC%9E%85-%EA%B0%9C%EB%B0%9C%EC%9E%90-%EA%B8%B0%EC%88%A0%EB%A9%B4%EC%A0%91)
* [NESOY님의 Back-end-Developer-Interview-Questions](https://github.com/NESOY/Back-end-Developer-Interview-Questions)
* [hanee24님의 신입 개발자 면접 질문](https://hanee24.github.io/2018/05/13/interview-questions/)
* [“개발자 면접 예상 질문, 오픈소스로 공유해요”](http://www.bloter.net/archives/246472)
* [150 Java Interview Questions and Answers](https://www.javacodegeeks.com/2014/04/java-interview-questions-and-answers.html#2)
* [yangshun님의 front-end-interview-handbook](https://github.com/yangshun/front-end-interview-handbook/blob/master/Translations/Korean/questions/javascript-questions.md)
* [ganqqwerty님의 123-Essential-JavaScript-Interview-Questions](https://github.com/ganqqwerty/123-Essential-JavaScript-Interview-Questions)

---

그 외 참고
면접질문 

-이력서, 자기소개서를 바탕으로 질문을한다. (해당 기술, 본인에 대한 소개 및 자기소개서, 이력, 경험 등등에 근거해서 
철저하게 준비한다.)

- 객체지향에 대해 설명해보라 

sol: 컴퓨터 프로그래밍 페러다임 중 하나로서, 프로그래밍에서 필요한 데이터를 
추상화시켜 상태와 행위를 가진 객체를 만들고 그 객체들 간의 유기적인 상호작용을 
통해 로직을 구성하는 프로그래밍 방법이다.

- 인터페이스에 대해 설명하라. 
인터페이스는 자바 프로그래밍 언어에서 클래스들이 구현해야 하는 동작을 지정하는데 사용되는 추상형이다.
자바의 다형성을 극대화하여 개발코드의 수정을 줄이고 프로그램 유지보수성을 높이기 위해 인터페이스를 
사용한다. 또한 인터페이스는 상수, 추상메소드, 디폴트메소드, 정적메소드를 포함할 수있다.

- 오버로딩과 오버라이딩의 차이점에 대해서 설명하라.
오버로딩 - 두 메소드가 같은 이름을 갖고있으나 파라미터의 수나 자료형, 순서등이 이 다른 경우를 말한다.
이때, 접근지정자, 반환형등은 오버로딩의 선언과 무관하다.

오버라이딩 - 상위클래스의 메서드와 이름과 용례가 같은 함수를 하위클래스에 재정의하는 것을 말한다.
즉, 상속관계에 있는 클래스 간에 같은 이름의 메서드를 재정의 하는 것을 말한다.

- call by value, call by reference에 대해 설명하라. 
call by value는 인자로 받은 값을 복사하여 처리를한다. 
call by reference는 인자로 받은 값의 주소를 참조하여 값에 직접적인 영향을 준다.

- 배열과 array list의 차이점에 대해 설명하라. 
배열은 크기가 지정되어있다. array list는 배열처럼 크기를 한번에 지정해줄 필요가 없다.
원하는 만큼 늘릴 수 있다. 단, 배열은 O(1)에 가능하지만 arraylist는 O(index)만큼의 시간복잡도가 소요된다. 

- 본인이 알고있는 자료구조에 대해 설명하라. 
~~~~~쭈욱 설명

- 자바의 접근제어자에 대해 설명하라. 
~~~~~쭈욱 설명

- 클래스와 객체의 차이점에 대해 설명하라. 
클래스는 어떤 대상을 나타내기위해 변수(속성)과 행위(메소드)로 표현(설계)한 것이다.
객체(인스턴스)는 클래스로부터 메모리를 할당해 변수로 선언한 것이다. 즉, 하나의 대상이다.

- 자료형에 대해 설명하라. 

- jsp의 생명주기에 대해서 설명하라.

- jsp의 redirect와 forward의 차이점에 대하여 설명하라.

- 데이터베이스의 트랜잭션에 대하여 설명하라.

- map과 set의 차이점에 대하여 설명하라.


- HTTP의 메소드에 대해서 설명해보라

- HTTP의 최신버전은 어느사이트에서 확인할 수 있는가?

- MVC패턴에 대해 설명해보세요.

- OSI 7계층에대해 설명해보고 HTTP프로토콜은 어느계층에 속하는가?

- HTTP프로토콜에 대해서 설명해보세요.

- 인터페이스 구현과 상속에대한 차이점을 설명해보세요.

- 본인이 진행한 프로젝트를 하면서 가장 어렵운 기술을 적용해 해결/수행한 것에 대하여 설명하세요.

- 자기자신에 대해 소개하세요.

- 본인의 성격(장점,단점)에 대해서 설명하세요.
 
- 휴학을 하면서 뭘 했나요?  

- 만약, 선임이 자기보다 못하는데, 부당한 일을 시킨다. 그렇다면 어떻게 대처할 것인가?

- 본인이 진행한 프로젝트에서 어떠한 역할을 맡았는가?

- 가장 잘하는 언어는 무엇인가? 

- 우리회사에 대해서 설명해보세요.

- 우리회사에서 어떻게 기여할 것인가요? 

- 자기소개 및 지원동기에 대해서 얘기해보세요.

- 주52시간근무에 대한 자신의 생각은? Due date를 못맞출 것 같을 때, 상사에게 어떻게 얘기를 할 것인가

자기소개해봐라

졸업작품으로 뭘햇고 어떤역할을 맡앗는지

Pl sql이 뭔지

sql플랜이뭔지

set cookie가 뭔지  

객체지향의 특징에대해 설명 

트랜잭션이뭔지 

트랜잭션의 선언과 종료가 어떤방식으로 이루어지는지 

오픈소스를 참고해 개발해본적이 잇는지

es6 js스펙이뭐거잇는지 

클로저가뭔지 

프로토타입이 뭔지  

리액트와 같은 자바스크립트와 부트스트랩의 동작방식의차이가뭔지 

브라우저의 동작방식에 대해서

포인터는 몇바이트로 이루어져잇는지 

코딩테스트를 봣는데 어땟는지 어떻게 문제를풀었는가 

가장 잘하는언어는 무엇이고 

가장잘하는언어가 자바인데 왜 c++로 문제를 풀엇는지

JVM의 메모리구조에 대해 설명해봐라

JVM의 힙메모리구조에 대해 설명해봐라 

Spring의 Mvc패턴이뭔지

스프링의 주요기능과 특징이뭔지

ajax 비동기통신에 대해 설명해봐라. 

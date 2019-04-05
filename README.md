# KESA_ANDROID

KESA (Korean Engineering Student Association) 에서 진행하는 첫 프로젝트

## Project Description

안드로이드 플랫폼에서 날씨 애플리케이션 구축.
User Interface, Design 등을 담당할 Front-End 팀과 API, Database 구축 등을 담당할 Back-End 팀 구분

### 1. Front End? Back End?
***

1.1 
> Front End 는 프로그램에서 유저에게 노출되는 코드를 말한다. 핸드폰에서 카카오톡 아이콘을 누르면 톡이 로딩되고, 맥북에서 사파리를 누르면 사파리가 로딩되는것도 Front End 코드의 결과물이다. 

1.2 
> Back End 코드는 사용자에게 노출이 안되는 코드다. API (Application Programming Interface) 를 불러오거나, Database 를 관리 하는것, 그리고 서버와 
연결 하는 모든 과정은 Back End 코드의 결과물이다.

>참고: <https://hpitos.tistory.com/10>

### 2. JAVA, ANDROID 기본 개념
***

2.1) Language vs Framework
> 언어와 프레임워크는 명백히 다른 개념이다. 언어는 C, Java, Python 처럼 어떤 과제를 직접 수행할 수 있도록 하는 용어이고 프레임워크는 어떠한 코딩 언어를 써서 개발에 도움이 되는 라이브러리 (function, api, class) 를 갖추고 있는 시스템이다. 각 프레임워크마다 지원하는 언어가 있다. 안드로이드 애플리케이션을 만들기 위해서는 안드로이드 프레임워크, 그리고 안드로이드 프레임워크가 기반으로 하는 Java 언어를 써야 한다. 다른 예로는 Rails 는 Ruby, 그리고 Django 는 Python 을 쓴다.

2.2) Java 의 기본
> Java 는 C 와 다른 OOP (Object Oriented Programming; 객체 지향 프로그래밍) 언어이다. 대표적인 OOP 언어로는 Java, Python, C++ 가 있다. C 는 Procedural Programming Language 이다. 간단히 정리하자면 OOP 에서는 여러개의 객체가 한 프로그램을 이루어서 완성시킨다. 대표적인 OOP 의 기능에는 Class 와 Instance, 그리고 Object 라는 개념이 있다. 그리고 OOP 를 설명하는 4대 요소가 있다. 
1. Inheritance
2. Encapsulation
3. Polymorphism
4. Abstract    
<https://stackify.com/oops-concepts-in-java/>    
4대 요소에 대한 더 자세한 설명을 위해서는 위 링크 참코

2.3) Class 설명
OOP 의 핵심 자료 형태는 Class 이다. 여러개의 Class 들이 합쳐져서 한 프로그램을 구축한다. Class 를 설명하기 앞서서 Object (객체) 를 이해해보자.

> Object (객체) 란 OOP 언어의 기본 자료 형태로 한 프로그램을 이루어준다. Java 의 Object 는 Python 의 Object 와 거의 동일하고 C 에서는 Struct 와 가장 비슷하다. 링크를 참고하자 <https://www.geeksforgeeks.org/classes-objects-java/>

> Class 는 Object 를 만들 수 있는 틀이다. Class 를 만들고 Construcor 을 부르면 한개의 Instance 가 생긴다. 이것이 Object 이다. 


### 3. 필요한 소프트웨어 설치
***

3.1) JAVA 설치

컴퓨터에서 자바를 사용하기 위해서는 JDK (Java Development Kit) 를 설치해야된다. <https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html> 
링크 클릭 후 운영체제에 맞는 옵션을 다운로드 (JAVA SE Development Kit 8u201 에서 Windows or MAC OS X)

3.2) IDE 설치

해당 프로젝트에는 사용하지 않지만, JAVA IDE (Integrated Development Environment) 를 설치하는 것도 추천한다.
IDE 란 개발을 조금 더 편하게 할수 있도록 하는 소프트웨어다. JAVA IDE 로는 대표적으로 Eclipse, IntelliJ (Jetbrains) 가 있다.

3.3) Android Studio 설치

해당 프로젝트에 필요한 IDE. Android 라이브러리를 지원해주고, Android Framework 를 사용할수 있도록 도움을 주는 Google 공식 IDE 이다.
<https://developer.android.com/studio#downloads> 
링크 클릭 후 운영체제에 맞는 옵션을 다운로드


# 0. 목차

[1. 인터넷 네트워크 - IP,TCP,PORT,DNS](https://github.com/MJ054/HTML_study/edit/main/HTTP_basic/readme.md#1-%EC%9D%B8%ED%84%B0%EB%84%B7-%ED%86%B5%EC%8B%A0)<br/>
[2. URI와 웹 브라우저 요청 흐름](https://github.com/MJ054/HTML_study/edit/main/HTTP_basic/readme.md#1-uriuniform-resource-identifier)<br/>
[3. HTTP]()





# 1. 인터넷 통신
# 2. IP(인터넷 프로토콜)
![image](https://user-images.githubusercontent.com/109513458/180629948-c6f3db2f-021c-4c50-9aee-e450799c7884.png)

## 2.1. 패킷(Packet)

![image](https://user-images.githubusercontent.com/109513458/180629991-9d084a0f-eae5-4a9a-aac5-0f4bf69beae9.png)

- 패킷(Packet)이라는 통신 단위로 데이터 전달.

## 2.1. IP 프로토콜의 한계
- 비연결성: 패킷을 받을 대상이 없거나 서비스 불능 상태여도 패킷 전송.
- 비신뢰성: 중간에 패킷이 사라지거나 순서대로 안와도 방법이 없다.
- 프로그램 구분: 같은 IP를 사용하는 서버에서 통신하는 애플리케이션이 둘 이상이면 구분할 수 없다.

# 3. TCP, UDP
## 3.1. 인터넷 프로토콜 스택의 4계층
![image](https://user-images.githubusercontent.com/109513458/180630082-ea4c2276-7ac2-44b6-b373-ed850ef7edf2.png)

![image](https://user-images.githubusercontent.com/109513458/180630110-10476846-8bab-48d1-8ee8-687ce770b57e.png)

## 3.2. TCP/IP 패킷 정보
![image](https://user-images.githubusercontent.com/109513458/180630124-311ae326-b911-40c9-b80f-a89492e9f56e.png)

## 3.3. TCP 특징
- 전송 제어 프로토콜(Transmisstion Conrol Protocol)
### 3.3.1. 연결지향-TCP 3 way handshake(가상연결)
![image](https://user-images.githubusercontent.com/109513458/180630167-edd075f1-b9ac-48dd-8113-61877cf7e16e.png)

### 3.3.2. 데이터 전달 보증
![image](https://user-images.githubusercontent.com/109513458/180630184-827e5f3c-ea07-437a-bf9c-019b38ad61fa.png)

### 3.3.3. 순서보장
![image](https://user-images.githubusercontent.com/109513458/180630190-fd2a7ea1-4e35-4d93-b085-a0649b71261f.png)

## 3.4. UDP 특징
- 사용자 데이터그램 프로토콜(User Datagram Protocol)
- 기능이 거의 없음
- IP와 거의같다 + PORT + 체크섬 정도만 추가
- 단순하고 빠름.

# 4. Port

![image](https://user-images.githubusercontent.com/109513458/180633749-676dfca6-b1cc-440b-a853-aed32590ed4d.png)

-TCP/IP 패킷 내에 PORT 정보가 있다.

# 5. DNS(Domain Name System)
- IP는 기억하기 어렵다.
- 도메인 명을 IP 주소로 변환.

![image](https://user-images.githubusercontent.com/109513458/180633794-a077c2a3-a699-4cb3-9be3-c82dd72c5045.png)



--------


# 1. URI(Uniform Resource Identifier)

![image](https://user-images.githubusercontent.com/109513458/180635297-9cb5fcc3-b735-4a65-88b8-8d2ad6ac46b0.png)
![image](https://user-images.githubusercontent.com/109513458/180635304-43f73899-69f1-4567-b805-affd9c4e53ff.png)

## 1.1. 단어 뜻
1) URL
- Uniform: 리소스 식별하는 통일된 방식
- Resource: 자원, URI로 식별할 수 있는 모든 것.(제한 없음)
- Identifier: 다른 과 구분하는데 필요한 정보
 
2) URL, URN
- URL-Locator: 리소스가 있는 위치를 지정
- URN-Name: 리소스에 이름을 부여
- 위치는 변할 수 있지만, 이름은 변하지 않는다.

## 1.2. URL 분석
### 1.2.1. 전체 문법

![image](https://user-images.githubusercontent.com/109513458/180635473-e66fbe78-637d-4c7f-b268-3183a1624037.png)

1)scheme
- 주로 프로토콜 사용
- 프로토콜: 어떤 방식으로 자원에 접근할 것인가 하는 약속 규칙
  ex) http, https,ftp 등등
  
2)userinfo
- URL에 사용자 정보를 포함해서 인증

3)host
- 도메인명 또는 IP주소를 직접 사용가능

4)port
- 접속 포트

5)path
- 리소스 경로(path), 계층적 구조

6)query

- key=value 형태
- ?로 시작,&로 추가 가능

7)fragment

- html 내부 북마크 등에 사용
- 서버에 전송하는 정보 아님

# 2. 웹 브라우저 요청 흐름

![image](https://user-images.githubusercontent.com/109513458/180635671-c026bfac-f904-41ea-8698-1f317cd76490.png)

- 클라이언트-> 서버

![image](https://user-images.githubusercontent.com/109513458/180635680-97b3ba73-6363-4575-ac75-9dd8a5b3bd85.png)

- 서버 -> 클라이언트





















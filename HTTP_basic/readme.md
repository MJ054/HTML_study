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









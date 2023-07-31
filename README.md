# :pushpin: groupStudy
> mvc 구조 스터디를 위한 게시판 실습 


</br>

## 1. 제작 기간 & 참여 인원
- 2023년 8월 1일 ~ 8월 6일
- 팀 프로젝트

</br>

## 2. 사용 기술
#### `Back-end`
  - Java 17
  - Oracle 18c
  - Mybatis
    
#### `Front-end`
  - bootstrap
  

</br>

## 3. 핵심 기능
mvc 구조 스터디를 위한 기본 게시판 기능 프로젝트입니다.
각 팀원 별로 모든 기능을 다 작성해보는 것을 목적이으로 
공통된 코드에 모듈화는 고려하지 않습니다.
<details>
<summary><b>핵심 기능 설명 펼치기</b></summary>
<div markdown="1">
### 4.1. 전체 흐름
![](https://zuminternet.github.io/images/portal/post/2019-04-22-ZUM-Pilot-integer/flow1.png)
### 4.3. Controller

![](https://zuminternet.github.io/images/portal/post/2019-04-22-ZUM-Pilot-integer/flow_controller.png)

- **요청 처리** :pushpin: [코드 확인](https://github.com/Integerous/goQuality/blob/b2c5e60761b6308f14eebe98ccdb1949de6c4b99/src/main/java/goQuality/integerous/controller/PostRestController.java#L55)
  - Controller에서는 요청을 화면단에서 넘어온 요청을 받고, Service 계층에 로직 처리를 위임합니다.

- **결과 응답** :pushpin: [코드 확인]()
  - Service 계층에서 넘어온 로직 처리 결과(메세지)를 화면단에 응답해줍니다.

### 4.4. Service

![](https://zuminternet.github.io/images/portal/post/2019-04-22-ZUM-Pilot-integer/flow_service1.png)

- **Http 프로토콜 추가 및 trim()** :pushpin: [코드 확인]()
  - 사용자가 URL 입력 시 Http 프로토콜을 생략하거나 공백을 넣은 경우,  
  올바른 URL이 될 수 있도록 Http 프로토콜을 추가해주고, 공백을 제거해줍니다.





## 4. ERD 설계
![](https://zuminternet.github.io/images/portal/post/2019-04-22-ZUM-Pilot-integer/final_erd.png)



## 5. 핵심 트러블 슈팅


## 6. 회고 / 느낀점


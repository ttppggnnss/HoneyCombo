<img src='https://user-images.githubusercontent.com/19357410/91040270-e3acae00-e648-11ea-96f8-d2022d22c741.gif'>

# <center>:honey_pot: Honey-Combo :bee:</center>

 ![Github](https://img.shields.io/badge/vue-2.6.11-%234FC08D?style=plastic&logo=Vue.js)![Github](https://img.shields.io/badge/spring_boot-2.3.1-%236DB33F?style=plastic&logo=Spring)![Github](https://img.shields.io/badge/MySQL-8.0-%234479A1?style=plastic&logo=mysql)![Github](https://img.shields.io/badge/Redis-3.0-%23DC382D?style=plastic&logo=Redis)![Github](https://img.shields.io/badge/build-passing-brightgreen?style=plastic)



:earth_asia: 번역: [KR](https://github.com/ttppggnnss/HoneyCombo/blob/master/README.md) [US](https://github.com/ttppggnnss/HoneyCombo/blob/master/docs/README.md)



`Honey-Combo` 는 1인 가구를 위한 음식 조합을 공유하기 위한 소셜 네트워크 서비스(Social Networking Service, SNS) 입니다. 사용자가 직접 요리한 사진을 피드로 게시해 여러 사용자들과 공유하며 소통할 수 있습니다.

1. Common Service
   - 꿀조합 피드 게시, 댓글, 좋아요 서비스를 제공합니다.
   - 유저들 간 팔로우 및 팔로잉 서비스를 제공합니다.
   - 유저의 성별과 나이대를 기반으로 피드 게시, 피드 좋아요, 피드 상세 조회, 검색 데이터를 분석해 피드를 추천합니다.
2. Contest Service
   - 관리자가 매주 하나의 주제로 콘테스트를 열어 유저들이 익명으로 참여합니다.
   - 좋아요를 가장 많이 받은 3개의 꿀조합을 게시한 유저에게 포인트를 부여합니다. 
   - 차트를 이용해 콘테스트 피드의 좋아요를 누른 유저의 성별과 나이대 데이터를 시각화합니다. 
3. Liquors Service
   - 관리자가 매주 새로운 주류 조합을 게시합니다.



## 📌 목차

[:honey_pot: Honey-Combo :bee:](#-honey-combo-)  

   - [시작하기](#-시작하기)
     - [시작하기에 앞서](#시작하기에-앞서)
- [사용된 도구](#-사용된-도구)
- [사용된 기술](#-사용된-기술)
- [저자](#-저자)
- [라이센스](#-라이센스)
- [참고](#-참고)



## :runner: 시작하기

아래 방법을 따르시면 프로젝트를 실행시킬 수 있습니다.

### 시작하기에 앞서

* [Windows 10](https://www.microsoft.com/en-us/software-download/windows10)
* [JDK 1.8](https://www.oracle.com/kr/java/technologies/javase/javase-jdk8-downloads.html)
* [Node.js 12.8.1](https://nodejs.org/ko/download/)
* [MySQL 8.0](https://www.mysql.com/downloads/)

## :globe_with_meridians: 지원하는 브라우저

| <img src='https://user-images.githubusercontent.com/19357410/91040268-e27b8100-e648-11ea-9dfa-21123112fd23.png' width=60> | <img src='https://user-images.githubusercontent.com/19357410/91040279-e7403500-e648-11ea-8b38-07049ca300af.png' width=60> | <img src='https://user-images.githubusercontent.com/19357410/91040276-e6a79e80-e648-11ea-8c97-ddc1d35d761c.png' width=60> | <img src='https://user-images.githubusercontent.com/19357410/91040282-e7403500-e648-11ea-9f42-d8abd35e9b50.png' width=60> |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|                            latest                            |                            latest                            |                            latest                            |                            latest                            |



## :hammer_and_wrench: ​사용된 도구

* Vue.js 2.6.11
* vue/cli 4.4.6
* yarn 1.22.4
* Spring boot 2.3.1
* Gradle 6.4.1
* IDE: Visual Studio Code 1.48, Spring Tool Suite 3



## :desktop_computer: ​사용된 기술

<img src="https://user-images.githubusercontent.com/19357410/91040283-e7d8cb80-e648-11ea-8724-e20afcbefcc4.png" width=850>

#### 프론트엔드

| Technology          | Description                                                  | Official website                                  |
| ------------------- | ------------------------------------------------------------ | ------------------------------------------------- |
| Vue                 | Front-end framework                                          | https://vuejs.org/                                |
| Vue-router          | Routing library                                              | https://router.vuejs.org/                         |
| Vuex                | Global State Management library                              | https://vuex.vuejs.org/                           |
| vuex-persistedstate | Persist and rehydrate your Vuex state between page reloads   | https://www.npmjs.com/package/vuex-persistedstate |
| Axios               | HTTP communication library                                   | https://github.com/axios/axios                    |
| Vuetify             | Vue UI library                                               | https://vuetifyjs.com/                            |
| vue-cookies         | A simple Vue.js plugin for handling browser cookies          | https://www.npmjs.com/package/vue-cookies         |
| vue-chartjs         | Wrapper for Chart.js in vue                                  | https://vue-chartjs.org/                          |
| vue-cropperjs       | A Vue wrapper component for [cropperjs](https://github.com/fengyuanchen/cropperjs) | https://www.npmjs.com/package/vue-cropperjs       |
| sweetalert          | A beautiful replacement for messages                         | https://sweetalert.js.org/guides/                 |
| vue-google-oauth2   | Handling Google sign-in and sign-out for Vue.js applications | https://www.npmjs.com/package/vue-google-oauth2   |

#### 백엔드

| Technology      | Dscription                       | Official Website                           |
| --------------- | -------------------------------- | ------------------------------------------ |
| Spring Boot     | Container + MVC framework        | https://spring.io/projects/spring-boot     |
| Spring Security | Authentication and authorization | https://spring.io/projects/spring-security |
| Redis           | Distributed cache                | https://redis.io/                          |
| JWT             | JWT login support                | https://jwt.io/                            |
| MySQL           | RDBMS                            | https://www.mysql.com/                     |
| JPA             | ORM framework                    | https://spring.io/projects/spring-data-jpa |
| QueryDsl        | Java persistence query language  | http://www.querydsl.com/                   |
| Lombok          | Simplified object packaging tool | https://projectlombok.org/                 |
| OAuth           | Authentication and authorization | https://oauth.net/                         |
| Swagger-UI      | Document production tool         | https://github.com/swagger-api/swagger-ui  |

* Spring security와 JWT(JSON Web Token)를 이용해 사용자 인증 및 인가 과정을 거쳐 웹 어플리케이션의 보안을 구성하였습니다.
* 로그인한 사용자의 인증 토큰을 인-메모리 데이터 저장소인 Redis에 저장하여 로그인 및 로그아웃한 사용자를 관리하였습니다.
* 인증 프로토콜 중 하나인 OAuth2(Open Authorization) 를 통해 구글 소셜 로그인을 구현하였습니다.
* JPA(Java Persistence API) + Spring Data JPA 를 사용하여 객체들과 테이블, 레코드를 자동으로 관리하며 기본적인 쿼리를 자동으로 생성합니다.
* QueryDSL을 이용해 타입에 안전한 방식으로 동적 쿼리를 생성해 SQL문을 문자열로 작성하거나 XML파일에 작성하지 않고  코드로 작성합니다.
* 사용자의 성별과 연령대를 기반으로 피드 게시, 피드 좋아요, 피드 상세 조회, 검색 로그 데이터를 분석해 추천 서비스를 제공합니다.
* AWS EC2와 Nginx를 이용하여 서비스를 배포하였습니다.

#### 추후 적용

* 추가로 docker를 사용하여 배포할 예정입니다.



## :vhs: 시연 영상

* [시연 영상](https://youtu.be/Vrj9zyP7zac)
* 로그인, 피드, 댓글, 좋아요, 팔로우, 알림 서비스
  * <img src="https://user-images.githubusercontent.com/19357410/91041095-62eeb180-e64a-11ea-9614-ec12760ad28b.gif" width=350>
  * <img src="https://user-images.githubusercontent.com/19357410/91041119-6bdf8300-e64a-11ea-9f3c-b98d2d5e032f.gif" width=350>
  * <img src="https://user-images.githubusercontent.com/19357410/91041081-5e29fd80-e64a-11ea-8f44-7f77596022ce.gif" width=350>
  * <img src="https://user-images.githubusercontent.com/19357410/91041105-65510b80-e64a-11ea-8ac7-5bede39d7493.gif" width=350>
* 콘테스트 서비스
  * <img src="https://user-images.githubusercontent.com/19357410/91041112-68e49280-e64a-11ea-9c86-d76ac9142956.gif" width=350>
* 주류 서비스
  * <img src="https://user-images.githubusercontent.com/19357410/91041106-66823880-e64a-11ea-8b99-3c3f60538de4.gif" width=350>



## 👤 저자

* 김세훈 - Sehoon Kim - kimsae123@naver.com
* 김순빈 - Soonbeen Kim - ksb940925@gmail.com
* 류승민 - Seungmin Ryu - dkqyqytt@gmail.com
* 이선수 - Sunsoo Lee - tjstn921030@gmail.com
* 서용준 - Yongjoon Seo - koreakkrea12@naver.com



## :page_with_curl: 라이센스

```
Copyright (c) 2015 Juns Alen

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```



## :books: 참고

* https://gist.github.com/taeukme/e004e01963190615d308a16bcd6e6040

* https://github.com/naver/egjs-flicking
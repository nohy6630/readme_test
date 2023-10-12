### 💻 기술 스택
- Web

- Server
    - ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000.svg?style=flat-square&logo=intellij-idea&logoColor=white)
      ![Springboot](https://img.shields.io/badge/Springboot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
      ![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
      ![JWT](https://img.shields.io/badge/JWT-black?style=flat-square&logo=JSON%20web%20tokens)
    - ![MySQL](https://img.shields.io/badge/MySQL-%2300f.svg?style=flat-square&logo=mysql&logoColor=white)
      ![RDS](https://img.shields.io/badge/AWS%20RDS-527FFF?style=flat-square&logo=Amazon%20RDS&logoColor=white)
      ![S3](https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square&logo=Amazon%20S3&logoColor=white)
      ![Redis](https://img.shields.io/badge/Redis-%23DC382D?logo=redis&logoColor=white)
    - ![GitHub Actions](https://img.shields.io/badge/Github%20Actions-%232671E5.svg?style=flat-square&logo=githubactions&logoColor=white)
      ![EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=Amazon%20EC2&logoColor=white)
      ![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white)
      ![Nginx](https://img.shields.io/badge/Nginx-%23009639.svg?style=flat-square&logo=nginx&logoColor=white)
- Co-working Tool
    - ![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=flat-square&logo=swagger&logoColor=white)
      ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=flat-square&logo=notion&logoColor=white)
      ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

#### 기술 스택 선정 이유
### 🎉 Android
0️⃣ **Android Studio**   
안드로이드 애플리케이션 개발에 최적화된 통합 개발 환경(IDE)

1️⃣ **Coroutine**   
네트워크 통신 과정에서 효율적인 비동기 처리를 위해 코루틴 사용

2️⃣ **Android Jetpack**      
재사용 가능한 컴포넌트와 공통 아키텍처 가이드라인을 제공하여 안정적이고 일관된 앱 개발

3️⃣ **Navigation**      
SAA(Single Acitivity Architecture) 구조에 적합한 화면 전환과 UI 구성 라이브러리

4️⃣ **ViewModel**        
UI와 데이터 영역을 분리하고, 화면 전환에 따른 데이터 저장을 담당

5️⃣ **Flow**         
Clean Architecture에서 LiveData 사용을 지양함에 따라 Flow로 대체

6️⃣ **DataBinding**   
데이터와 UI를 연결하는 작업을 레이아웃(.xml)에서 처리하는 기술

7️⃣ **Hilt**   
Android 환경에서 최적화된 DI(의존성 주입) 라이브러리

8️⃣ **OkHttp & Retrofit2**   
REST API, HTTP 네트워크 통신 및 데이터베이스 접근에 사용되는 라이브러리


### 🎉 Backend

0️⃣ **Spring Boot**       
스프링 프레임워크의 여러 기능을 쉽게 활용하여 안정적이고 확장 가능한 웹 애플리케이션을 구축하기 위함

1️⃣ **JPA**         
핵심적인 비지니스 로직 개발에 집중할 수 있도록, 객체지향적인 관점에서 데이터베이스를 다루기 위함

2️⃣ **Querydsl**           
복잡한 요구사항을 만족하기 위한 동적 쿼리 등을 쉽게 구현하기 위함

3️⃣ **AWS RDS mysql**              
데이터베이스 인프라를 쉽게 구축하기 위해 AWS rds 를 사용함. 또한 상용화 된 RDBMS 중, 가장 대중화되어있고 레퍼런스가 풍부한 mysql 을 주 데이터베이스로 선정함

4️⃣ **AWS S3 storage**                    
확장 가능한 백엔드 스토리지 솔루션으로서 데이터를 안전하게 저장하고 쉽게 관리하기 위함

5️⃣ **Java 17**   
안정성을 보장하는 LTS(Long-Term Support) 버전이고, 팀원들의 기존 스택을 고려하여 JAVA 17 을 선정함

6️⃣ **Spring Security**   
웹 애플리케이션의 보안 기능을 강화하며 사용자 인증 및 권한 관리를 손쉽게 제공하기 위함.

7️⃣ **Redis**   
고성능의 인메모리 데이터 구조 저장소로, 캐싱 및 세션 관리 등 다양한 사용 사례에서 데이터의 빠른 조회와 저장을 위해 사용함

8️⃣ **JWT**   
세션 관리 없이 사용자 인증 및 정보 전송을 위한 경량화된 토큰 방식을 사용하기 위함

## :pushpin: 네이밍룰
- 파일 : CamelCase + SnakeCase
- 클래스명 : PascalCase
- 함수/변수명 : CamelCase

## 📑 커밋 컨벤션
커밋 메세지는 **커밋 태그(이슈 번호): 커밋 내용** 으로 작성  
ex) `git commit -m "Feat(#8): 로그인 기능 구현`
|커밋태그|설명|
|:---:|---|
|Feat|신규 기능 구현 작업|
|Fix|버그 수정|
|Docs|문서 수정|
|Style|코드 스타일 변경|
|Design|UI 디자인 변경|
|Refactor|코드 리팩토링|
|Rename|변수, 클래스, 메소드, 패키지명 변경|
|Build|dependencies 추가 및 삭제|
|Chore|기타 변경사항(빌드 관련, 패키지 매니징, CI/CD, assets 등)|
|Test|테스트 코드 추가|

## 📘 Git flow 전략
![image](https://github.com/nohy6630/readme_test/assets/129354455/a9deda9f-b901-479d-b8c7-51ca5bd4f431)
|브랜치명|설명|
|:---:|---|
|main|출시 또는 배포 가능한 코드의 브랜치|
|dev|다음 버전을 개발하는 브랜치|
|feat/[이름]|기능을 개발하는 브랜치|
|fix/[이름]|버그를 수정하는 브랜치|

  
### 🔍 소프트웨어 아키텍쳐
![KakaoTalk_20221014_222429596](https://user-images.githubusercontent.com/115769126/195902499-86655519-bf4b-4741-b533-e74c242a8b93.png)

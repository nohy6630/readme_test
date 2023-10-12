### 💻 기술 스택
**Front-End :** <img src="https://img.shields.io/badge/React Native-61DAFB?style=flat-square&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=Axios&logoColor=white"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=black"/> <img src="https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=Visual Studio Code&logoColor=white"/> <p>
**Back-End :** <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=Spring Boot&logoColor=white"/> <img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=flat-square&logo=IntelliJ IDEA&logoColor=white"/> <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=Postman&logoColor=white"/> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=Swagger&logoColor=white"/> <img src="https://img.shields.io/badge/spring-6DB33F?style=flat-squre&logo=spring&logoColor=white">

#### 기술 스택 선정 이유
* Use Case 를 고려했을 때, 우리 서비스를 이용하는 고객은 실제 사용자(User)입니다. 
* User는 Android 혹은 iOS 기기를 사용합니다. 
### 🎉 ReactNative 선정 이유
1️⃣ **Hot Reload와 Live Reload를 지원하는 크로스 플랫폼**   
코드를 수정했을 때 다시 빌드할 필요 없이 바로 기기에서 변경사항을 확인 할 수 있습니다.

2️⃣ **웹 확장에 유리한 크로스 플랫폼**      
React-Native로 개발하고 React로 넘어가기에 수월합니다. 또한 react-native-web을 이용하여 웹 앱을 한 번에 만들 수 있습니다.

3️⃣ **개발 툴이 필요 없는 크로스 플랫폼**      
Xcode(ios simulator) 없이 IOS 개발이 가능하여, window 운영체제를 가진 개발 팀원도 IOS 개발에 참여 할 수 있습니다.

4️⃣ **호환이 용이한 크로스 플랫폼**        
android, ios 호환이 가능하여 유저의 사용성을 높여줄 수 있습니다. 

5️⃣ **효율적인 크로스 플랫폼**       
axios는 fetch와는 달리 response의 object를 json 메소드 없이도 바로 받을 수 있어 더 빠르고 효율적일 것입니다.


### 🎉 Spring/ 선정 이유

1️⃣ **쉬운 개발환경을 제공하는 프레임워크**       
스프링은 자바 및 JVM 환경의 대체언어들의 효율적이고 쉬운 엔터프라이즈 애플리케이션 개발 환경을 제공합니다.

2️⃣ **구조 설계에 유용한 프레임워크**         
기존의 웹, 또는 하드웨어, 데이터베이스등 전문적인 영역만 지원하는 프레임워크들과 다르게, 스프링은 전체를 설계하는 용도로 사용할 수 있습니다.

3️⃣ **트렌디한 개발 프레임워크**           
Spring은 최근의 트렌드, 혹은 더 나은 프로그래밍 방법을 찾기 위해 트렌드에 맞추어 개발자들이 좀 더 능동적으로 개발할 수 있는 다양한 모듈들과 방법론을 적용시키고 있습니다.

4️⃣ **오픈소스의 호환성을 제공하는 프레임워크**              
스프링은 오픈소스로써 지속적인 업데이트가 되고 있으며 이전 버전들에 대한 강력한 호환성을 지원합니다.

5️⃣ **직관적이고 유연한 프레임워크**                    
스프링은 직관적인 API를 제공하며, 만들고자하는 애플리케이션의 요구사항과 목적에 따라 유연하게 적용시킬수 있습니다.

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
![image](https://github.com/nohy6630/readme_test/assets/129354455/7cdbf4c9-7585-4736-ac01-b3bd2e61e8e4)

|브랜치명|설명|
|:---:|---|
|main|출시 또는 배포 가능한 코드의 브랜치|
|dev|다음 버전을 개발하는 브랜치|
|feat/[이름]|기능을 개발하는 브랜치|
|fix/[이름]|버그를 수정하는 브랜치|

  
### 🔍 소프트웨어 아키텍쳐
![KakaoTalk_20221014_222429596](https://user-images.githubusercontent.com/115769126/195902499-86655519-bf4b-4741-b533-e74c242a8b93.png)

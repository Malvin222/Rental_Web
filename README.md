
 ## 🖨Rental_Web
<br>

 * 개발기간
   - 2023-11-01 ~ 2023-11-15
 * 설계 배경
   - 사업 홍보 및 거래업체의 편의성 제공
 * 설계 목적 
   - 새로운 거래처를 위한 업체 홍보
   - 거래업체의 AS예약 일정 및 기능 제공
 * 기능 요약
   - AS예약 
   - 사업 제품 및 정보제공
   - 새로운 거래업체 등록
  
  ### 🔧개발환경
  * Front-End :  HTML5, CSS3, JavaScript, Thymeleaf
  * Back-End : Java, SpringBoot, SpringSecurity, JPA
  * Database : MariaDB
  * Server : ApacheTomcat, AWS EC2,RDS
  * Tool : IntelliJ, Git

  ### ⚙담당 핵심 기능
  * 기능 글씨 클릭시 해당 코드로 이동됩니다.
  * 기능 이미지 클릭시 크게 출력됩니다.
  <table>
    <tr>
    <th>
     <a href="https://github.com/Malvin222/Rental_Web/blob/049c3a8862148c20b7b3a791564925747156bcb6/src/main/resources/templates/introduce/introduce.html#L36"> 지도API</a>
    </th>
    <th>
     <a href="https://github.com/Malvin222/Rental_Web/blob/049c3a8862148c20b7b3a791564925747156bcb6/src/main/java/com/rental_web/controller/AscalController.java#L47"> 일정 CRUD</a>
    </th>
    <th>
     <a href="https://github.com/Malvin222/Rental_Web/blob/049c3a8862148c20b7b3a791564925747156bcb6/src/main/resources/templates/ascal/main.html#L17C7-L17C7"> 풀캘린더</a>
    </th>
   </tr>
   <tr>
     <td>
      <img src="https://github.com/Malvin222/Rental_Web/assets/127707299/a70c4ae6-f2a6-4c86-991b-2eb0b75c93d2" width="250" height="300">
     </td>
     <td>
      <img src="https://github.com/Malvin222/Rental_Web/assets/127707299/095d53a8-08cb-46c7-ba87-3403167b888a" width="200" height="300">
     </td>
     <td>
      <img src="https://github.com/Malvin222/Rental_Web/assets/127707299/ea4500d9-c9ab-440c-b26c-b702ba67f691" width="200" height="300">
     </td>
   </tr>
  </table>

   ### 🛠트러블 슈팅 (해결을 누르면 해당 코드로 이동됩니다.)
   - Querydsl Q클래스 생성오류
     
     <img src="https://github.com/Malvin222/Rental_Web/assets/127707299/de755ec1-32db-429c-9d6e-d32787c83e1a" width="300">
    
   - 원인 <br>
        스프링부트 3.1.0 및 Gradle버전과 IntelliJ IDE 버전에 따라
        querydsl  플러그인을 사용하면 문제가 발생할 수 있는것을 확인
       
   - [해결](https://github.com/Malvin222/Rental_Web/blob/049c3a8862148c20b7b3a791564925747156bcb6/build.gradle#L12C1-L12C1) <br>
        기존 Dependency는 유지하면서 plugin에서 querydsl을 주석처리 후 재빌드 함으로써 오류를 해결

        <img src="https://github.com/Malvin222/Rental_Web/assets/127707299/c73353a4-32d6-44f1-9ace-e529bbb70f37" width="300">



  ### 프로젝트 후기
  - 새로운 학습 <br>
    첫 프로젝트는 학원에서 수업 기반으로 코드를 작성하여 진행했고, 그 당시 코드 작성에 대해서는 어려움이 없었습니다. 팀원 간의 원활한 의사소통
    과 협업을 우선으로 두어 프로젝트를 성공적으로 마무리했습니다. 이후, 새로운 도전을 위해 다양한 기술과 도구를 다뤄보고자 했습니다.
    이번 프로젝트는 스프링 부트, 그래들, 인텔리제이, 마리아디비 등을 처음 다뤄보는 경험을 중심으로 진행되었으며, 최종적으로는 AWS에 배포하는
    것을 목표로 삼았습니다. 이를 통해 여러 새로운 스킬들을 배우고, 프로젝트를 통해 실제로 활용하고 응용하는 재미를 느꼈습니다.
  - 다양한 스킬 이용 <br>
    다양한 스킬을 활용하면서 예상치 못한 어려움도 있었습니다. JPA를 이용한 데이터베이스 활용, Ajax를 통한 서버와의 데이터 통신 등에서 발생한
    에러들을 해결하는 과정이 새로운 학습의 일부분이었습니다. 이러한 문제들을 해결할 때마다 성취감과 즐거움을 느꼈습니다.
    프로젝트에서는 이전보다 WBS와 ERD를 더 신경써서 작성해 보았습니다. 또한, 빠르게 환경에 적응하기 위해 스프링 시큐리티, 풀캘린더 API, 타임
    리프 등 다양한 기술을 활용하였고, 최종적으로 AWS EC2와 RDS를 이용하여 성공적으로 배포를 완료했습니다
    
     


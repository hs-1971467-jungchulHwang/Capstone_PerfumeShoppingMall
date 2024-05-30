<div align="center">
  <img src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/111953799/857bc5dd-4ca3-4104-9dfe-0193a2baf209" alt="pd로고" width = "200" height="200"/>
</div>
<div align="center">
  <h1><strong>🛒 향수 쇼핑몰 Perfume Dream</strong></h1>
</div>

<br/>

## 🚀 목차

1. [개요](#-개요)
2. [팀원 소개](#-팀원-소개)
3. [팀원 사진](#-팀원-사진)
4. [개발 환경](#%EF%B8%8F-개발-환경)
5. [기능구성도](#-기능구성도)
6. [REST API 명세서](#-REST-API-명세서)
7. [구현 화면](#-구현-화면)
8. [시연 영상](#-시연-영상)
9. [비교표](#-비교표)
10. [9.25 한성공학경진대회 추가예정사항](#-9.25-한성공학경진대회-추가예정사항)


<br/>

## 📌 개요

React, Flutter와 SpringBoot를 이용한 향수 쇼핑몰 웹/앱 서비스로 다양한 향수 브랜드 및 제품을 포함하는 카테고리를 구축하고 각 제품의 특징, 성분, 사용 방법 등을 명확하게 설명하여 고객들이 제품을 더 잘 이해할 수 있도록 한다.
웹 버전은 데스크탑 및 랩탑을 통해, 모바일 버전은 테블릿 또는 핸드폰으로 사이트 방문 또는 별도의 앱을 통해 접근이 가능하다. 
커져가는 모바일 시장에서 OS를 가리지 않고 다양한 방법을 통해 접속 할 수 있어 접근성이 높다는 것이 큰 특징이다.

<br/>

## 👩‍👩‍👧‍👦 팀원 소개

| 역할                  | 학번       | 이름      | Git URL                                              |
|---------------------|-----------|-------------|---------------------------------------------------|
| 프론트엔드 (IOS)     | 1971434 | 조정우       | [https://github.com/jungwoooooooo/perfumedream_capston2024](https://github.com/jungwoooooooo/perfumedream_capston2024)     |
| 프론트엔드 (Android) | 1971467 | 황정철      | [https://github.com/hs-1971467-jungchulHwang/Android_perfume](https://github.com/hs-1971467-jungchulHwang/Android_perfume) |
| 프론트엔드 (React)   | 2171202 | 김지효      | [https://github.com/hjjh0531/react-perfume](https://github.com/hjjh0531/react-perfume)       |
| 백엔드 (Spring Boot) | 1971196 | 정재민      | [https://github.com/jaemin0211/backend_perfume](https://github.com/jaemin0211/backend_perfume)   |

<br/>

## 📷 팀원 사진


<br/>

## ⚙️ 개발 환경
<img src = "https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/e1a02090-d446-4030-8a1f-7fc666e22622" width = 700>    




프레임워크 : ![RA](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![FT](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) ![SB](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

개발 도구 : ![AS](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white) ![VC](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white) ![IJ](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white) ![MS](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

<br/>

## 🔧 기능구성도
<table>
  <tr>
    <th>카테고리</th>
    <th>주 기능</th>
    <th>세부 기능</th>
    <th>
    </th>
  </tr>
  <tr>
    <td rowspan="8">관리자</td>
    <td rowspan="8">관리자 페이지</td>
    <td>관리자 로그인</td>
    <td rowspan="8">
      <a>
        <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
      </a>
    </td>
  </tr>
  <tr>
    <td>모든 상품 조회</td>
  </tr>
    <tr>
    <td>상품 추가</td>
  </tr>
    <tr>
    <td>상품 수정</td>
  </tr>
    <tr>
    <td>페이징된 상품 조회</td>
  </tr>
    <tr>
    <td>페이징된 주문 조회</td>
  </tr>
    <tr>
    <td>특정 주문 상세 조회</td>
  </tr>
    <tr>
    <td>주문 상태 변경</td>
  </tr>
  <tr>
    <td rowspan="6">회원</td>
    <td rowspan="6">회원 관리</td>
    <td>회원가입</td>
    <td rowspan="6">
        <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
      </a>
        <img src="https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white">
      </a>
        <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white">
      </a>
    </td>
  </tr>

  <tr>
    <td>아이디 중복 확인</td>
  </tr>
  <tr>
    <td>전화번호 중복 확인</td>
  </tr>
  <tr>
    <td>사용자 로그인</td>
  </tr>
  <tr>
    <td>아이디 찾기</td>
  </tr>
  <tr>
    <td>비밀번호 찾기</td>
  </tr>

  <tr>
    <td rowspan="3">구매</td>
    <td rowspan="3">구매 기능</td>
    <td>장바구니 주문</td>
    <td rowspan="3">
      <a>
        <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
      </a>
      <a>
        <img src="https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white">
      </a>
      <a>
        <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white">
      </a>
    </td>
  </tr>
  <tr>
    <td>개별 상품 주문</td>
  </tr>
  <tr>
    <td>내 주문 조회</td>
  </tr>
  <tr>
    <td rowspan="4">제품</td>
    <td rowspan="4">제품 기능</td>
    <td>장바구니에 제품 추가</td>
    <td rowspan="4">
      <a>
        <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
      </a>
      <a>
        <img src="https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white">
      </a>
      <a>
        <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white">
      </a>
    </td>
  </tr>
  <tr>
    <td>모든 카테고리 조회</td>
  </tr>
  <tr>
    <td>상품 좋아요</td>
  </tr>
  <tr>
    <td>카테고리별 상품 조회</td>
  </tr>

</table>
<br/>

## 📝 REST API 명세서

### API 목록

| 기능                  | HTTP 메서드 | API 경로                          | 완료 여부 |
|---------------------|-------------|----------------------------------|----------|
| 관리자 로그인            | POST        | `/admin/login`                   | ✅       |
| 모든 상품 조회 (관리자)    | GET         | `/admin/product/all`             | ✅       |
| 상품 추가 (관리자)        | POST        | `/admin/add/product`             | ✅       |
| 상품 수정 (관리자)        | POST        | `/admin/edit/product/{productId}` | ✅       |
| 페이징된 상품 조회 (관리자) | GET         | `/admin/view/product/{page}/{size}` | ✅       |
| 페이징된 주문 조회 (관리자) | GET         | `/admin/view/orders/{page}/{size}` | ✅       |
| 특정 주문 상세 조회 (관리자) | GET         | `/admin/view/details/items/{orderId}` | ✅       |
| 주문 상태 변경 (관리자)    | POST        | `/admin/change/state/{orderId}`  | ✅       |
| 장바구니에 상품 추가       | POST        | `/cart/addCart`                  | ✅       |
| 모든 카테고리 조회         | GET         | `/category/all`                  | ✅       |
| 상품 좋아요             | POST        | `/like/{productNo}`              | ✅       |
| 회원 가입              | POST        | `/member/join`                   | ✅       |
| 아이디 중복 확인          | POST        | `/member/id-check`               | ✅       |
| 전화번호 중복 확인         | POST        | `/member/phone-check`            | ✅       |
| 사용자 로그인            | POST        | `/member/login`                  | ✅       |
| 아이디 찾기             | POST        | `/member/find-id`                | ✅       |
| 비밀번호 찾기            | POST        | `/member/find-password`          | ✅       |
| 장바구니 주문            | POST        | `/order/cart`                    | ✅       |
| 개별 상품 주문           | POST        | `/order/detail/{productId}`      | ✅       |
| 내 주문 조회             | GET         | `/order/my`                      | ✅       |
| 카테고리별 상품 조회        | GET         | `/product/category`              | ✅       |


<br/>


## 💻 구현 화면
### 웹 화면
<details>
<summary> ▶️ click! </summary>
<br/>
( 메인홈 )   
<img width="945" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/c4248ca1-ad60-43d6-abf1-84f12bcfca5b">   
<br/>
( 상품 목록 )   
<img width="945" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/ed7426e7-cbf0-4b14-af67-ffa11307e089">   
<br/>
( 상품 상세 )   
<img width="944" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/b9e79195-4fe4-428c-b1e2-8118029de618">   
<br/>
 ( 로그인 / 회원가입 )   
 <img width="959" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/099bfcd6-4731-47ae-b560-b563957c250e">   

<img width="959" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/5327cc8a-bec0-4d00-816d-ac3eecdf5947">   
<br/>
 ( 장바구니 )   
<img width="944" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/2f74e1ec-5303-4b0c-a49d-d61547482c5f">   
<br/>
 ( 관심상품 )   
 <img width="946" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/bc687959-95ad-428a-8b27-8b8b3d208089">   
<br/>
 ( 내 정보 )   
 <img width="946" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/58c38a03-6d7f-4477-bdf4-1fe02238ce0b">   
<br/>
 (주문 조회)
 <img width="959" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/9ad6de69-cf9f-425b-9458-ffdbeaa55d2e">
<br/>
 ( 메뉴 )   
 <img width="946" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/79dd91fb-3af8-4e9e-a630-be7e708bc9e1">   
<br/>

</details>

### 웹 앱 화면
<details>
<summary> ▶️ click! </summary>

<br/>
 ( 메인홈 )   
<img width="240" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/3db02790-6b8f-46da-9b8a-06cd38e0cfe8">   
<br/>
<br/>   
 ( 상품 목록 )   
<img width="247" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/51d99107-6398-4109-a78c-c3dc94cbd365">   
<br/>
<br/>   
 ( 상품 상세 )   
<img width="238" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/306c6cbd-4553-42ff-be6b-cf684f89c194">   
<br/>
<br/>   
 ( 로그인 / 회원가입 )   
<img width="239" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/3e259ea2-5ce9-45da-9ed0-7c7a74b967f3">   
<br/>   
 ( 장바구니 )   
<img width="248" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/9de8fdc8-4941-40d9-9ff3-7a56c551cc89">   
<br/>
 ( 관심상품 )   
 <img width="238" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/f5ce5c38-305e-499e-9014-ec2377b3d24c">   
<br/>
 ( 내 정보 )   
 <img width="241" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/c47966f0-1720-4d44-860a-b4b53c9fb757">   
<br/>
 (주문 조회)
 <img width="227" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/3cac5cef-3026-422a-8b40-94bf9b0767e3">
<br/>
 ( 메뉴 )   
 <img width="224" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/abcb981a-94ac-4d59-aa6e-29c944ed3e29">   
<br/>

</details>
  
### IOS 앱 화면
<details>
<summary> ▶️ click! </summary>

<br/>
   ( 상품 목록 )        ( 상품 상세 )         ( 로그인 )        ( 회원가입 )
<img width="1000" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/115887505/b34df6aa-3676-4b92-98c7-39d1618ddcb5">
<br/>

</details>

### Android 앱 화면
<details>
<summary> ▶️ click! </summary>
  
<br/>
   ( 상품 목록 )        ( 상품 상세 )        ( 로그인 )        ( 회원가입 )
<img width="1000" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/115887505/e5c72848-9a59-48a4-a1e2-f390afd0bc42">   
<br/>
    ( 장바구니 )        ( 관심 상품 )       ( 내 정보 )       ( 주문조회 )
<img width="1000" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/115887505/8f39c53e-9871-4f56-834c-a3213a338417">
<br/>

</details>

<br/>

## 📹 시연 영상
### 리액트 시연 영상
[<img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white">
](https://youtu.be/0xI4mW6GvUM)
<br/>

### IOS 시연 영상
<img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white">
()
<br/>

### Android 시연 영상
<img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white">
()
<br/>

<br/>

## 📊 비교표
|      |   :Perfume Dream:    | :최우수: | :우수 1: | :우수 2: |
|----- |--------------------|--------|-------|---------|
| :code: |          :O:         |   :O:   |   :O:   |   :O:   |
| :doc:  |          :O:         |   :O:   |   :X:   |   :X:   |
| :영상: |          :O:         |   :X:   |   :X:   |   :X:   |
| :화면: | :React(Web, Mobile), IOS, Android: | :React(Web, Mobile): | :React(Web, Mobile): | :React(Web, Mobile): |

<img src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/111953799/de894fbf-2dfd-4d54-97be-bf8a203c89ab" width="500" />    
<br/>
최우수 : https://github.com/capstone-aloha     
<br/>
우수1 : https://github.com/TeamCookCaps  
<br/>
우수2 : https://github.com/godi00/capstone  

<br/>


## 💡 9.25 한성공학경진대회 추가예정사항
1. 개인에게 맞는 향수 추천 알고리즘 추가
2. 향수에 대해 정보를 남길 수 있는 커뮤니티 기능 추가
3. Azure, GCP에서 수행 추가





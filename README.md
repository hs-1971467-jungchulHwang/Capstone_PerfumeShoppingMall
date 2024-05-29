<div align="center">
  <img src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/111953799/857bc5dd-4ca3-4104-9dfe-0193a2baf209" alt="pd로고" width = "200" height="200"/>
</div>
<div align="center">
  <h1><strong>🛒 향수 쇼핑몰 Perfume Dream</strong></h1>
</div>


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

React,Flutter와 SpringBoot를 이용한 향수쇼핑몰 웹/앱 서비스로 다양한 향수 브랜드 및 제품을 포함하는 카테고리를 구축하고 각 제품의 특징, 성분, 사용 방법 등을 명확하게 설명하여 고객들이 제품을 더 잘 이해할 수 있도록 한다.
웹버전은 테스크탑 및 랩탑을 통해, 모바일 버전은 테블릿 또는 핸드폰으로 사이트 방문 또는 별도의 앱을 통해 접근이 가능하다. 커져가는 모바일 시장에서 OS를 가리지 않고 다양한 방법을 통해 접속 할 수 있어 접근성이 높다는 것이 큰 특징이다.

<br/>

## 👩‍👩‍👧‍👦 팀원 소개

| 역할                  | 학번       | 이름      | Git URL                                              |
|---------------------|-----------|---------|---------------------------------------------------|
| 프론트엔드 (IOS)     | 1971434 | 조정우   | [https://github.com/jungwoooooooo/perfumedream-capstone](https://github.com/jungwoooooooo/perfumedream-capstone)     |
| 프론트엔드 (Android) | 1971467 | 황정철   | [https://github.com/hs-1971467-jungchulHwang/Android_perfume](https://github.com/hs-1971467-jungchulHwang/Android_perfume) |
| 프론트엔드 (React)   | 2171202 | 김지효   | [https://github.com/hjjh0531/react-perfume](https://github.com/hjjh0531/react)       |
| 백엔드 (Spring Boot) | 1971196 | 정재민   | [https://github.com/jaemin0211/backend_perfume](https://github.com/jaemin0211/backend_perfume)   |

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

---

<br/>

## 💻 구현 화면

### 웹 화면
<details>
<summary> ▶️ click! </summary>
<br/>
( 메인홈 )
<img width="559" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/dfcfef35-9111-4804-8920-f7a64dad0b3a">
<br/>
( 상품 목록 )
<img width="559" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/31797b67-87d3-41f0-a44d-2dd8fe11d326">
<br/>
( 상품 상세 )
<img width="560" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/136f1783-6cb2-4b47-a840-9e4b28b26393">
<br/>
 ( 로그인 / 회원가입 )
 <img width="560" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/c43f4a0e-da35-470d-a584-ed0f7d04359b">
 <img width="559" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/196c21cf-1491-4b59-99f0-f79b7da7c8a8">
<br/>
 ( 장바구니 )
 <img width="558" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/e62bee9f-2d5c-42e6-9770-6bebf031ee34">

<br/>

</details>

### 웹 앱 화면
<details>
<summary> ▶️ click! </summary>
</details>

### IOS 앱 화면
<details>
<summary> ▶️ click! </summary>
</details>

### Android 앱 화면
<details>
<summary> ▶️ click! </summary>
</details>

<br/>

## 📹 시연 영상

<br/>

## 📊 비교표
<img src="https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/111953799/de894fbf-2dfd-4d54-97be-bf8a203c89ab" width="500" />

최우수: https://github.com/capstone-aloha
우수1: https://github.com/TeamCookCaps
우수2: https://github.com/godi00/capstone

<br/>

## 💡 9.25 한성공학경진대회 추가예정사항
1. 개인에게 맞는 향수 추천 알고리즘 추가
2. 향수에 대해 정보를 남길 수 있는 커뮤니티 기능 추가
3. Azure, gcp 에서 수행 추가하기


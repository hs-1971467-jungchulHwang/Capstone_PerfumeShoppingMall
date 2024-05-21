## 🛒 향수 쇼핑몰 Perfume Dream

<br/>

## 🚀 목차

1. [개요](#개요)
2. [팀원 소개](#팀원-소개)
3. [개발환경](#개발환경)
4. [RESTAPI 명세서](#REST-API-명세서)
5. [구현 화면](#구현-화면)

<br/>

## 📝 개요

React,Flutter와 SpringBoot를 이용한 향수쇼핑몰 웹/앱 서비스로 다양한 향수 브랜드 및 제품을 포함하는 카테고리를 구축하고 각 제품의 특징, 성분, 사용 방법 등을 명확하게 설명하여 고객들이 제품을 더 잘 이해할 수 있도록 한다.
웹버전은 테스크탑 및 랩탑을 통해, 모바일 버전은 테블릿 또는 핸드폰으로 사이트 방문 또는 별도의 앱을 통해 접근이 가능하다. 커져가는 모바일 시장에서 OS를 가리지 않고 다양한 방법을 통해 접속 할 수 있어 접근성이 높다는 것이 큰 특징이다.

<br/>

## 👩‍👩‍👧‍👦 팀원 소개

| 역할                  | 학번       | 이름   |
|---------------------|-----------|-------|
| 프론트엔드 (iOS)      | 1971434   | 조정우 |
| 프론트엔드 (Android)  | 1971467   | 황정철 |
| 프론트엔드 (React)    | 2171202   | 김지효 |
| 백엔드 (Spring Boot)  | 1971196   | 정재민 |

<br/>

## ⚙️ 개발환경

![image](https://github.com/hs-1971467-jungchulHwang/Capstone_PerfumeShoppingMall/assets/106284092/e1a02090-d446-4030-8a1f-7fc666e22622)


프레임워크 : ![RA](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![FT](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) ![SB](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

개발 도구 : ![AS](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white) ![VC](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white) ![IJ](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white) ![MS](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

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
<img width="560" alt="image" src="https://github.com/hs-1971467-jungchulHwang/Capstonea_PerfumeShoppingMall/assets/106284092/f65dd298-e1fd-4f54-abcb-215b9faa9f08">
<br/>
 로그인 / 회원가입
 장바구니

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


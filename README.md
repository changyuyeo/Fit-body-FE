# Fit body 👩‍👦‍👦
`Fit body(핏바디)`는 다양한 홈트레이닝용 운동기구를 판매하는 쇼핑몰 입니다. <br />

> 개발 기간: 2021.09.26 ~ ing <br />
> 개발 인원: 1명 (개인 프로젝트)
<br />

[Fit body!](https://bodyfit-app.herokuapp.com/)

## Index 📖
1. 프로젝트 주제 선정 이유
1. 프로젝트 스케줄
1. 사용기술
1. 프로젝트 구조
1. 주요 기능 미리보기
<br />

## 선정 이유
계속되는 코로나로 인해 헬스장보다는 홈트레이닝을 꾸리는 사람들이<br />
늘어가는 추세이기 떄문에 운동용품을 아이템으로 쇼핑몰 주제를 생각해봤습니다.
<br /><br />

## 프로젝트 스케줄 (주차별)
<table>
  <tr>
    <td>주차별</td>
    <td>내용</td>
  </tr>
  <tr>
    <td>3주차</td>
    <td>아이템 선정 및 아이디어 구체화, 스토리보드 작성</td>
  </tr>
  <tr>
    <td>4주차</td>
    <td>스토리보드 토대로 디자인 레이아웃 구성</td>
  </tr>
  <tr>
    <td>5주차</td>
    <td rowspan="2">
      프로젝트 초기화 및 설정<br />
      깃허브 레포지토리 생성, 버전관리 시작<br />
      완성된 레이아웃을 참고해서 마크업 진행, 모바일, 테블렛 사이즈 고려하면서 스타일링<br />
      더미데이터로 화면에 데이터 뿌려서 동작 테스트해보기
    </td>
  </tr>
  <tr>
    <td>6주차</td>
  </tr>
  <tr>
    <td>7주차</td>
    <td rowspan="2">
      작업된 화면과 더미데이터, 스토리보드를 참고해 db 스키마 작성<br />
      백엔드 API 구성, 포스트맨을 이용해서 API 테스트
    </td>
  </tr>
  <tr>
    <td>8주차</td>
  </tr>
  <tr>
    <td>9주차</td>
    <td rowspan="2">
      프론트엔드와 완성된 백엔드API 연동하고 기능 구현해가기<br />
      더미데이터를 실제 db데이터로 교체
    </td>
  </tr>
  <tr>
    <td>10주차</td>
  </tr>
  <tr>
    <td>11주차</td>
    <td rowspan="2">
      프로젝트 모든 기능 완성하기
    </td>
  </tr>
  <tr>
    <td>12주차</td>
  </tr>
  <tr>
    <td>13주차</td>
    <td>heroku를 이용해 프론트엔드, 백엔드 배포 하기</td>
  </tr>
  <tr>
    <td>14주차</td>
    <td>주변 사람들에게 프로젝트 테스트를 받고 정보를 토대로 유지보수</td>
  </tr>
  </tr>
  <tr>
    <td>15주차</td>
    <td>기말발표</td>
  </tr>
</table>
<br />

## 사용기술 🔍
### Front-End
![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![NuxtJS](https://img.shields.io/badge/Nuxt-black?style=for-the-badge&logo=nuxt.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=AEDDFF)

### Back-End
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### Design
![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white)
![Adobe XD](https://img.shields.io/badge/Adobe%20XD-470137?style=for-the-badge&logo=Adobe%20XD&logoColor=#FF61F6)
![Adobe Photoshop](https://img.shields.io/badge/adobephotoshop-%2331A8FF.svg?style=for-the-badge&logo=adobephotoshop&logoColor=white)

### IDE
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

### Hosting/SaaS
![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)
<br /><br />

## 프로젝트 구조 🛠
- [x] 메인페이지 접속
- [x] 로그인 페이지 이동: 로그인 또는 회원가입 진행
- [x] 상품 조회: 메인페이지에서 상품목록 조회
- [x] 상품 조회: 메뉴를 이용해 해당 카테고리 페이지로 이동 후 상품목록 조회
- [x] 상품 상세 조회: 상품 조회 페이지에서 상품 상세페이지로 이동
- [x] 상품 상세 조회: 다른상품 보기와, 댓글 기능 (회원기능)
- [x] 상품 리스트 조회: 유저가 저장한 장바구니 리스트 페이지 (회원기능)
- [x] 상품 리스트 조회: 유저가 구매한 구매목록 리스트 페이지 (회원기능)
- [x] 상품 생성: 해당하는 카테고리에 원하는 상품 등록 (관리자 기능)
<br />

## 주요 기능 미리보기 🖥

<table>
  <tr>
    <td>미리보기</td>
    <td>설명</td>
  </tr>

  <tr>
    <td>업로드 다시</td>
    <td>
      <b>메인 페이지</b> <br />
      - 웹 페이지에 들어오면 제일 먼저 볼 수 있는 메인 페이지 입니다. <br />
      - 여러 상품을 볼 수 있고  LOAD MORE 버튼으로 더욱 많은 상품을 볼 수 있습니다.
    </td>
  </tr>
  

  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/80776262/144866236-eda00afb-fec6-4804-89c9-dbc01d443e50.gif" width="500">
    </td>
    <td>
      <b>회원 인증 페이지</b> <br />
      - 회원가입과 로그인을 할 수 있는 페이지 입니다.<br />
      - 이메일형식에 맞아야하며 비밀번호는 5자리 이상이여야 가입이 가능합니다.
    </td>
  </tr>

  <tr>
    <td>업로드 다시</td>
    <td>
      <b>카테고리 별 상품</b> <br />
      - 많은 상품 중 카테고리 별로 상품을 선택하여 볼 수 있습니다. <br />
      - 카테고리안에는 다시 서브카테고리가 존재해 원하는 상품을 쉽게 찾을 수 있습니다.
    </td>
  </tr>

  <tr>
    <td>업로드 다시</td>
    <td>
      <b>상품 상세 정보 보기</b> <br />
      - 해당 상품의 상세정보를 볼 수 있습니다. <br />
      - 바로 구매할 수 있는 버튼과 장바구니에 담을 수 있는 버튼이 있으며 여러개를 장바구니에 담을 수 있습니다. <br />
      - 아래에는 댓글을 자유롭게 작성할 수 있으며, 다른 상품을 랜덤으로 4개를 보여주는 부분이 있습니다.
    </td>
  </tr>

  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/80776262/144866533-f60197dd-5bf0-4375-9101-f711225ff0f5.gif" width="500">
    </td>
    <td>
      <b>장바구니</b> <br />
      - 계속 상품을 장바구니에 담아왔다면 장바구니 페이지에 해당 상품들이 쌓이게 됩니다.  <br />
      - 장바구니 상품들의 총 가격을 알 수 있고, 구매와 삭제가 가능합니다.
    </td>
  </tr>

  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/80776262/144865267-0c1a3b74-ffde-433e-8513-707127bd6e05.gif" width="500">
    </td>
    <td>
      <b>구매내역</b> <br />
      - 지금까지 구매했던 상품들이 기록이된 페이지 입니다.
    </td>
  </tr>

  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/80776262/144867240-db153ecf-a924-4146-8de2-34c7da6cac06.gif" width="500">
    </td>
    <td>
      <b>상품 업로드</b> <br />
      - 상품을 업로드 할 수 있는 페이지 입니다. <br />
      - 제목, 설명, 가격, 이미지의 정보를 입력 후 업로드를 할 수 있습니다. <br />
      - 당연히 어드민의 권한을 가진 계정만 가능합니다.
    </td>
  </tr>

  
</table>




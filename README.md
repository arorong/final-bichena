# 🍶전통주 판매 사이트 비채나
![bichena_logo](https://github.com/user-attachments/assets/fa671af9-3dc7-409e-a958-dabf6ae7cb43)
- 배포 url : http://bichena.kro.kr/main.ko
</br></br></br>

## 1. 프로젝트 소개
- 비채나는 전국 양조장에서 만들어지는 다양한 종류의 전통주를 구매할 수 있는 사이트 입니다.
- 전통주를 구매한 후 별점 등록 및 리뷰 작성을 할 수 있습니다.
- 옵션 설정을 통해 기호에 맞는 전통주를 검색할 수 있습니다.
- 구매 금액에 따라 회원 등급이 결정되며 할인 혜택을 받을 수 있습니다.
</br></br></br>

## 2. 개발 기간 및 인원
- 개발 기간 : 2024. 04. 26. ~ 2024. 05. 25. (4주)
- 개발 인원 : 7명

## 3. 개발 환경
- Front-end & Back-end: Java,HTML/CSS, JavaScript, Ajax, jquery
- 프레임워크 : Spring Framework, BootStrap
- 서버 & DB :  Apache Tomcat, MariaDB
- API : kakaomap Maps API, kakao/Naver login, PortOne 등
- 버전 및 이슈관리 : Github
- 서비스 배포 환경 : AWS
- 디자인 : Figma
</br></br></br>

## 4. 주요 기능
### 1) 메인페이지
![bichena main](https://github.com/user-attachments/assets/e98ad588-d7b2-4296-99c1-ed365fc4e3a2)
- 슬라이드 API를 사용하여 이벤트별/주류별/리뷰 슬라이드를 구현했습니다.
- 각 슬라이드의 더보기 버튼을 통해 해당 상품 카테고리로 이동합니다.
- 슬라이드의 상품을 클릭 시 해당 상품의 상세 페이지로 이동합니다.
</br></br></br></br>

### 2) 로그인 및 회원 가입
![image](https://github.com/user-attachments/assets/e10d1ff3-f6db-4eeb-bae7-ce566455b868)
</br></br>
- 카카오, 네이버, 이메일을 이용해 로그인 및 회원가입을 진행합니다.
</br></br></br>
**[회원가입]**

![image](https://github.com/user-attachments/assets/0ea8882d-0609-4bc3-901a-c19fa0d914a1)
</br></br>
- 주류판매 사이트이기 때문에 가입 시 성인인증 실행합니다.
</br></br></br></br></br>

![image](https://github.com/user-attachments/assets/f69c2a41-d891-41f5-8037-b8a32500e965)
- 성인인증을 통해 확인된 이름, 생년월일, 전화번호는 미리 노출해 고정시킵니다.
- 아이디, 비밀번호, 닉네임, 이메일, 주소를 입력하면 입력창에서 바로 유효성 검사가 진행. 유효성 검사에서 통과하지 못할 경우 입력창 하단에 경고 문구가 표시됩니다.
</br></br></br>

**[로그인]**
![image](https://github.com/user-attachments/assets/1e6d1094-7b22-4b03-840f-d0d4ab39b6c1)
</br></br>
- 아이디나 비밀번호가 일치하지 않을 경우 경고 문구가 나타나며, 로그인에 성공했을 경우 홈화면으로 이동합니다.
</br></br></br></br>

### 3) 회원 마이페이지
![image](https://github.com/user-attachments/assets/40769d8a-3847-4a0d-a0a0-57eecf93c80d)
- 로그인 후 오른쪽 상단의 닉네임을 누르면 마이페이지 메인화면으로 이동합니다. 
- 주문내역, 취소/환불 내역, 작성한 리뷰, 회원정보를 확인할 수 있습니다.
</br></br></br>

### 4) 상품 검색 및 상세 보기
![image](https://github.com/user-attachments/assets/c886be94-72e8-4085-8955-e57e9760cd19)
- 각 옵션들을 선택하여 원하는 술을 검색할 수 있습니다. 
- 상품을 클릭하면 구매 가능한 페이지로 이동하며 상품에 대한 상세 정보를 확인할 수 있습니다.
</br></br></br></br>

### 5) 게시판
**[공지사항]**
![image](https://github.com/user-attachments/assets/5f2f8a5d-08b3-4b77-bff2-b02718ed8ee9)
- 관리자가 공지사항을 등록하면 회원은 공지사항 게시판에서 공지를 확인할 수 있습니다. 
- 하단의 검색창에 단어를 입력해 원하는 공지를 검색할 수 있습니다.
</br></br></br>

**[Q&A]**
![image](https://github.com/user-attachments/assets/d40c71fa-fbc0-4385-9bc5-9d94c8ea9cc1)
- 카테고리 항목을 선택하여 문의하고자 하는 내용을 작성 후, 하단의 작성 버튼을 누르면 글을 등록할 수 있습니다.
</br></br></br>

**[FAQ]**
![image](https://github.com/user-attachments/assets/07ea79bb-b540-4ac4-9c0b-4e8f6d560fb6)
- 자주 묻는 질문들을 한 줄 데이터로 담아 아코디언으로 구현하였습니다.
- 제목 클릭 시 내용을 확인할 수 있으며,  다른 게시글을 클릭하면 기존에 열렸던 글은 닫히고 새로 누른 글의 내용이 열립니다.
</br></br></br></br>

### 6) 관리자 페이지
**[메인페이지]**

![image](https://github.com/user-attachments/assets/ce5396a7-e538-40fc-a5a7-e165fde874be)
![image](https://github.com/user-attachments/assets/e00a5d52-09f9-49ee-80c1-a2d3387781fe)

- 메인페이지 하단에 위치한 관리자페이지 링크로 접속해 로그인을 하면 관리자페이지로 이동할 수 있습니다.
- 관리자페이지에서 판매현황 확인, 회원들의 주문 목록, 상품/회원/공지사항 관리 등의 작업을 할 수 있습니다.
</br></br></br>

**[판매현황]**
![image](https://github.com/user-attachments/assets/f7d2234e-1b0f-453e-87b5-59661d7d29ae)
- Google Chart API를 이용해 판매 순위가 높은 5개 상품이 그래프로 노출되도록 구현하였습니다.
- 갯수 출력 시 판매 물량에서 주문 취소된 물량은 제외하고 출력됩니다.
</br></br></br>
**[스마트 에디터]**

![image](https://github.com/user-attachments/assets/25af893d-d8b6-4f91-8c73-99f89c633308)
- 상품 등록 및 공지사항을 작성할 수 있도록 Smart editor 기능을 사용하였습니다.
- Smart editor을 이용해 만들어진 html 형식의 데이터를 JSP 형식으로 혹은 DB베이스에 바로 저장되도록 구현하였습니다.
- 사진과 gif 형식의 파일을 따로 저장하지 않고 
바로 사용이 가능하기 때문에 데이터의 업로드 기능이 원할해집니다.
</br></br></br></br>
### 7) 반응형
![image](https://github.com/user-attachments/assets/b98a7d3c-528a-42ee-81d6-c86598c184a3)



</br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br>


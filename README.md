# MakingBaking Final Project
![MakingBaking_시현](https://user-images.githubusercontent.com/110507639/217481206-18ebfe6f-9c2f-4c5d-a175-4d8c4eeaf679.gif)
<h3>MakingBaking, 원데이클래스 예약 및 상품 판매 사이트</h3>
<p>MZ 세대의 다양한 취미생활 열풍과 환경을 생각한 Vegan Bread 판매</p>
<br>

<h2>:calendar: 프로젝트 기간</h2>
2022.12.05 ~ 2023.01.20 (46일)
<br>

<h2>:hammer_and_pick: Tools</h2>
<div align="center">
	<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=Spring&logoColor=white"/>
	<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white"/>
	<img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat&logo=Visual Studio Code&logoColor=white"/>
	<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/>
	<img src="https://img.shields.io/badge/Apache Tomcat-F8DC75?style=flat&logo=Apache Tomcat&logoColor=white"/>
	<img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=flat&logo=Thymeleaf&logoColor=white"/>
</div>
<br>

<h2>:books: Skills</h2>
<div align="center">
	<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
	<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white"/>
	<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white"/>
	<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white"/>
	<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jQuery&logoColor=white"/>
</div>
<br>

<h2>:globe_with_meridians: 오픈 API</h2>
<li>Daum 주소검색 api</li>
<li>KakaoMap api</li>
<li>Kakao 로그인 api</li>
<li>KakaoPay api</li>
<br>

<h2>:sound: 프로젝트 설명</h2>
<li>Spring Boot를 사용한 프로젝트입니다.</li>
<li>원데이클래스 예약 및 상품 판매 사이트로 일반 회원은 기본적으로 상품 구매, 원데이클래스 예약이 가능하고 결제 및 결제취소를 할 수 있습니다.</li>
<li>관리자는 회원 관리, 원데이클래스와 상품 관리, 게시판 관리, 주문 및 예약 관리, 리뷰 관리를 할 수 있습니다.</li>
<li>부가적으로 비밀번호를 잃어버렸을 경우 이메일로 임시 비밀번호를 발급해주는 기능을 구현하였습니다.</li>
<br>

# 👩‍💻 담당 구현부분
<h2>관리자 페이지</h2>
<h4>회원, 원데이클래스, 상품, 주문 및 예약, 리뷰 관리</h4>
<li><strong>@PageableDefault어노테이션</strong>을 사용하여 페이징처리</li>
<li>searchCondition, searchKeyword 속성을 클래스에 추가하여 <strong>검색기능 구현</strong></li>
<li>원데이클래스/상품 등록, 수정, 삭제 가능</li>
<li>회원, 원데이클래스, 상품, 리뷰의<strong> 체크박스를 통해 선택 삭제 시, ajax를 이용해 백단에 전송</strong></li>
<li>window.open을 이용하여, <strong>팝업창</strong>구현(회원의 정보/리뷰/QnA 상세보기)</li>
<li>주문 및 예약 페이지에서 <strong>ajax를 이용하여 참여현황/배송상태 변경</strong></li>


## mini project 주제

CRUD와 FILE I/O를 사용한 Fleamarket 관리(중고제품 등록하기)

## 팀
- 팀원: 양지후(21900433), 하정원(21900780)
- 역할: 

   양지후 - 뼈대의 역할을 할 CRUD, main과 signup 함수를 작성, 
         
   하정원 - 기능적인 역할을 할 Search, SignUp, ReView 함수를 작성

## mini project 가 가지고 있는 대략적인 기능 설명
~~~
1. Sign up
    * 회원가입
    * 프로그램을 시작할 때 회원 유무를 파악
    * 회원이라고 응답했으며 파일에 입력한 아이디가 저장되어 있다면 입력한 아이디로 로그인
    * 회원이라고 응답했지만 파일에 입력한 아이디가 저장되어 있지 않다면 회원가입 유도
    * 회원이 아니라고 응답했다면 회원가입 유도
2. Create Product
    * 중고 제품을 등록
    * 등록 정보: 제품명, 판매가격, 카테고리, 아이디, 중고상품여부
    * 카테고리를 등록할 때는 화면에 출력된 카테고리 종류 중 하나를 선택
3. Read Product 
    * 등록된 중고 제품 1개를 출력
    * list함수를 통해 전체 중고 제품을 나열
4. Update Product 
    * 이전에 등록한 중고 제품을 선택 후 정보를 수정
5. Delete Product 
    * 이전에 등록한 중고 제품을 선택 후 삭제
6. Search Product 
    * 원하는 중고 제품을 검색
    * 이름, 카테고리, 판매가격 검색 가능
7. Review board
    * 등록된 중고 제품에 등록된 후기를 나열
8. Save and load data about product  
    * 파일에 중고 제품을 저장
    * 저장된 내용을 프로그램 시작할 때 로드
9. Save and load data about member information  
    * 파일에 회원의 아이디를 저장
    * 저장된 아이디를 프로그램 시작할 때 로드
10. Save and load data about review 
    * 파일에 등록된 제품들의 후기를 저장
    * 저장된 후기를 후기 게시판 보기 메뉴를 선택하면 로드
~~~

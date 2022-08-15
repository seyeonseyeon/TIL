# DAY92

## 1. 회원가입 화면

* 어느 한 칸이라도 빈칸일 시 '필수황목입니다.' 메세지 띄우기
![회원가입](https://user-images.githubusercontent.com/103159709/184588880-29ea09d4-cfc3-466e-848f-b8bc7b8feef8.png)

* Ajax를 이용해 데이터베이스에 동일한 아이디가 존재하는지 비교
![회원가입 오류](https://user-images.githubusercontent.com/103159709/184589002-c80c26bd-6c9c-4dc3-a74f-1ee2141f0560.png)

* 비밀번호 조건 미충족 시 '보안에 취약합니다. 5자리 이상이어야 합니다.' 메세지 띄우기
![회원가입 오류3](https://user-images.githubusercontent.com/103159709/184589156-f0efc88c-cc86-4211-a7d9-1932b155fffa.png)

* 비밀번호 확인: 위 비밀번호와 일치하지 않을 시 '일치하지 않습니다. 비밀번호를 다시 입력해주세요.' 메세지 띄우기
 ![화면 캡처 2022-08-15 151235](https://user-images.githubusercontent.com/103159709/184589362-0eacb31c-ea22-45c7-b38c-cb2f8c03ad15.png)

## 2. 로그인 화면 

#### 로그인 성공 전 메인 화면
 ![메인](https://user-images.githubusercontent.com/103159709/184587001-baaed115-59d8-4e4e-8124-9526465136d4.png)

#### 로그인 성공 시 메인 화면 
 ![로그인 시 메인](https://user-images.githubusercontent.com/103159709/184587306-a4b96cc2-fa53-469d-b7b4-a25f4fd4b4df.png)

## 3. 마이페이지

* 로그인 성공 시에만 화면에 보여짐
* 로그인한 아이디값에 따른 정보 불러옴(쿠폰내역, 포인트 내역, 예매내역, 회원정보)
![마이페이지](https://user-images.githubusercontent.com/103159709/184587770-8cf97d89-0dd1-4ff6-89f6-ad2fc66b738b.png)


#### 회원탈퇴
* 비밀번호가 일치하지 않을 시 회원탈퇴 불가
![회원탈퇴](https://user-images.githubusercontent.com/103159709/184588051-364001e8-ad64-4b91-9625-012369aa7c5d.png)


* 회원탈퇴 성공 시 'used'필드 값 변경(완전 삭제 ×/ 0: 탈퇴한 계정, 1: 사용 중인 계정) 

![회원탈퇴2](https://user-images.githubusercontent.com/103159709/184588283-c7794aaf-8c7e-4fde-a7ba-b9c5cd2fda95.png)


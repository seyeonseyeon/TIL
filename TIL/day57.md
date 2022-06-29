# DAY57

## 1. 수업내용

##### 1. mysql(putty에 입력)

* systemctl enable mysqld: 재부팅 시 자동 시작하도록 설정

* systemctl start mysqld: 서비스 시작

* systemctl status mysqld: 서비스 구동 여부 확인

##### 2. 파일 전송
1. eclipse에서 project export

2. 명령 프롬프트에서 
* dir
* scp -P 6003(내 포트 번호) day05(파일 이름) root@27.96.129.120(내 포트 포워딩 번호):/root
* 비밀번호 입력

3. putty창에서  
* [root@multi14 jsy webapps] # cp /root/day05.war .
* [root@multi14 jsy webapps] # ls

ls

cd ..

cd bin

 ./startup.sh
 
 cd ..
 ls
 
Putty 창에서 sql문 쓸 때 테이블명만 대소문자 구분

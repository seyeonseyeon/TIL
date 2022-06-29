# DAY57

## 1. 수업내용

##### 1. mysql(putty에 입력)

* systemctl enable mysqld: 재부팅 시 자동 시작하도록 설정

* systemctl start mysqld: 서비스 시작

* systemctl status mysqld: 서비스 구동 여부 확인

##### 2. 파일 전송 방법
1. eclipse에서 project export

2. 명령 프롬프트에서 
* dir
* scp -P 6003(내 포트 번호) day05(파일 이름) root@27.96.129.120(내 포트 포워딩 번호):/root
* 비밀번호 입력

3. putty창에서  
* [root@multi14 jsy webapps] # cp /root/day05.war .
* [root@multi14 jsy webapps] # ls

##### 3. 사용자 생성 및 데이터베이스 생성
1. [root@multi14 jsy bin] # mysql -u root -p

2. 비밀번호 입력

3. mysql> use mysql;

4. mysql> select host, user from user;

5. mysql> CREATE DATABASE DB이름(shopdb) default character set utf8;

6. mysql> GRANT ALL PRIVILEGES ON DB이름(shopdb).* to '아이디(admin1)'@'%';  -- 해당 DB에 대한 권한 부여

7. mysql> flush privileges;  -- 새로고침

##### 4. linux 명령어
1. pwd(print working directory): 현재 작업중인 디렉토리 정보 출력
2. cd(change directory): 경로 이동
3. ls(list segments): 디렉토리 목록 확인
4. cp(copy): 파일 혹은 디렉토리 복사
5. mv(move): 파일 혹은 디렉토리 이동 / 이름 변경
6. rm(remove): 파일이나 디렉토리 삭제 / 디렉토리를 삭제할 때에는 하위 디렉토리까지 모두 삭제되므로 주의!! 다시 복구 안됨!!
7. shutdown: 시스템 종료

##### 5. 주의사항
 1. Putty 창에서 sql문 쓸 때 테이블명만 대소문자 구분(workbench에서 CREATE TABLE cust ();로 썼다가 cust로 통일)

##### 6. 참고
1. '%': 모든 서버에 접속할 수 있다는 의미
![ww](https://user-images.githubusercontent.com/103159709/176360543-4a63529a-4963-463e-8a05-0f3f3308ce5c.png)


2. 초록색이 실행 중인 파일임을 의미
![리눅스](https://user-images.githubusercontent.com/103159709/176360986-5bb97439-e0bc-49d2-8792-019db8e9a2b4.png)

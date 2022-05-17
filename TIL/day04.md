# DAY04 (git hub특강)

## 1. GIT: 분산관리시스템


* why?

  * 백업
  * 복구
  * 협업

* how? 

  * git hub(분산관리시스템)을 이용해서

  

##### 1. git 초기 설정

* git config --global user.name "이름"
*  git config --global user.email "메일 주소"
*  git config --global -l 또는 git config --global --list: : 작성자가 올바르게 설정되었는지 확인

![git hub 4](https://user-images.githubusercontent.com/103159709/167358079-bc0f6fca-5bbe-4e39-b568-4ea62d34aa5d.png)



##### 2. git 기본 명령어

* git init: 현재 작업 중인 디렉토리를 Git으로 관리한다는 명령어
* git status: Working Directory와 Staging Area에 있는 파일의 현재 상태를 알려주는 명령어
* git add: Working Directory에 있는 파일을 Staging Area로 올리는 명령어
* git commit: Staging Area에 올라온 파일의 변경 사항을 하나의 버전(커밋)으로 저장하는 명령어
* git log: 커밋의 내역(ID, 작성자, 시간, 메세지 등)을 조회할 수 있는 명령어
* touch 파일 이름: 파일 생성
 * ctrl `: terminal 생성
 * ctrl l: 화면 깨끗이
 * ctrl s: 저장







# 2. GIT HUB: 원격 저장소를 이용해 다른 사람과 공유



##### 1. git remote: 로컬 저장소에 원격 저장소를 등록, 조회, 삭제할 수 있는 명령어

* 등록: git remote add <이름> <내 github 주소>
* 조회: git remote -v:
* 삭제: git remote rm <이름> 또는 git remote remove <이름>



##### 2. 원격 저장소에 업로드

* git add <파일 이름>
* git commit -m "<올리는 이유>"
* git log --oneline: 커밋 확인
* git push origin master



![git hub 13](https://user-images.githubusercontent.com/103159709/167358166-289f9e35-8ef8-4cab-b5ec-35fd779ec8f5.png)



##### 3. 주의 사항

* git init 안에 init하지 않기
* 상위 폴더 안에 init하지 않기
* github에서 init하지 않기


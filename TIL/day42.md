# DAY43

## 1. Spring day051 CRUD 완벽히 끝내기
* 추후에 수행평가로 제출 예정 (6월 20일)

## 2. 수업 내용
* Mapper에서 CateVO cate --> CateVO obj , int id --> int obj 로 바꾸면 복사붙여넣기 할 때 수정하기 편함


  * 예) 

  public void insert(CateVO cate) throws Exception;  --> public void insert(CateVO obj) throws Exception;
  
  public void delete(int id) throws Exception; --> public void delete(int obj) throws Exception;

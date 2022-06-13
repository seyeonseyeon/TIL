# DAY44

## 1. 개념

1. thymeleaf에서 value="" : <input>태그에서 데이터 값을 넣을 때 사용 

     * th:value : 값을 변경하고 출력하고자 하는 변수 입력

2. location.href: 특정 링크로 페이지를 이동할 때 사용

3. console.log(); : 설정한 값을 f12 콘솔에 표시

4. href: <a> 태그의 속성 중 하나로, <a> 태그가 가리키는 URL을 정의
  
      * th:href: "@{이동할경로}"

5. th:each : 반복할때 사용. for 문
  
6. th:text : 내용 변경할 때 사용
  
   예) 
    `<td th:text="${item.price}">10000</td>    -->   10000 값을 item.price 로 변경`
 
7. val(); form의 선택 요소 텍스트 값을 설정, 받아옴

# DAY45

## 1. 공지사항
**6/20**
1. 이클립스 spring day 051 / web day 051 수행평가로 제출 
2. 단원 시험 예정

## 2. 수업내용
1. id 값을 서버로 전송하는 방법 (#)
```
$(document).ready(function(){

	$('#searchbtn').click(function(){
		$('#searchform').attr({
			'action':'/search',
			'method':'get'
		});
		$('#searchform').submit();
	});
});

```
2. class값을 서버로 전송하는 방법(.)
```
$(document).ready(function(){

	$('#updatebtn').click(function(){
		$('.user').attr({
			'enctype': 'multipart/form-data',
			'action' : 'update'
			'method' : 'post',
		});
		$('.user').submit();
	});
});
	
```	

3. 차트를 서버에 보내는 방법
```
<script>
function display(){

};

function getdata(){
	display();
};

$(document).ready(function(){
	getdata();
});
</script>
```

## 3. 개념
1. concat: 두 개의 문자열을 하나의 문자열로 만들어주는 역활을 하는 함수이며, 입력값을 문자열 대신 배열을 사용하면 두 개의 배열을 하나의 배열로 만들어주는 역할도 하는 함수
	

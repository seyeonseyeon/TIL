# DAY45

## 1. 공지사항
6/20
1. 이클립스 spring day 051 / web day 051 수행평가로 제출 
2. 단원 시험 예정

## 2. 
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


2. class 값을 서버로 전송하는 방법(.)
```
$(document).ready(function(){

	$('#updatebtn').click(function(){
		$('.user').attr({
			'enctype': 'multipart/form-data',
			'method' : 'post',
		  'action' : 'update'
		});
		$('.user').submit();
	});
});



```
$(document).ready(function(){
	$('#updatebtn').click(function(){
		$('.user').attr({
			'enctype': 'multipart/form-data',
			'method' : 'post',
		    'action' : 'update'
		});
		$('.user').submit();
	});
});

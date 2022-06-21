# DAY51

## 1. Semi Project(DAY2)

##### 1. 오늘 할 일
* ~~login & logout 화면 완성하기~~
* 회원 register, update 완성하기 △
 
 
## 2. 수업 내용
* mybatis Logger

  * 하는 방법
1. maven library 추가
```
<!-- log4j2 -->   
<dependency>
	<groupId>org.bgee.log4jdbc-log4j2</groupId>
	<artifactId>log4jdbc-log4j2-jdbc4.1</artifactId>
	<version>1.16</version>
</dependency>
```
2. src/main/resources 폴더 아래 logback.xml 생성
```
<?xml version="1.0" encoding="UTF-8"?>
<configuration>

	<appender name="STDOUT"
		class="ch.qos.logback.core.ConsoleAppender">
		<encoder>
			<pattern>%d{yyyyMMdd HH:mm:ss.SSS} [%thread] %-3level %logger{5}-%msg %n</pattern>
		</encoder>
	</appender>
	
	<logger name="jdbc" level="OFF" />
	<logger name="jdbc.sqlonly" level="DEBUG" />
	<logger name="jdbc.sqltiming" level="DEBUG" />
	<logger name="jdbc.audit" level="OFF" />
	<logger name="jdbc.resultset" level="DEBUG" />
	<logger name="jdbc.resultsettable" level="DEBUG" />
	<logger name="jdbc.connection" level="OFF" />

	
	<root level="DEBUG">
		<appender-ref ref="STDOUT" />
	</root>

</configuration>
```

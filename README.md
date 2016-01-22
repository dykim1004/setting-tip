# setting-tip

#마이바티스(MyBatis) 쿼리 로그 출력 및 정렬하기 (출처 -http://addio3305.tistory.com/66)
log4jdbc-remix 사용
<dependency>
    <groupId>org.lazyluke</groupId>
    <artifactId>log4jdbc-remix</artifactId>
    <version>0.2.7</version>
</dependency>

# tomcat embedded get 방식 한글깨짐 처리
<plugin>
	<groupId>org.apache.tomcat.maven</groupId>
	<artifactId>tomcat7-maven-plugin</artifactId>
	<version>2.2</version>
	<configuration>
		<port>8080</port>
		<path>/</path>
		<systemProperties>
			<JAVA_OPTS>-Xms256m -Xmx768m -XX:MaxPermSize=256m</JAVA_OPTS>
		</systemProperties>
		<uriEncoding>UTF-8</uriEncoding>
	</configuration>
</plugin>

# web app Libraries 경로 인식이 안될때
\workspace\ .settings\org.eclipse.wst.common.component 파일안에  
source-path 확인

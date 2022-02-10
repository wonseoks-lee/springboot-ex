### 단독으로 스프링부트 프로젝트 사용시 예제
부모 스타터 지정을 무조건 기억해라 ( 꼭 해줘라 )

```xml
<!-- 부모 스타터 -->
	<parent>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-parent</artifactId>
		<version>2.5.6</version>
		<!-- 레포지토리 부모 검색 -->
		<relativePath/>
	</parent>
```
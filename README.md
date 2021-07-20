# "isolated" spring-graphql mvc example

Original example, embedded in `spring-graphql`: https://github.com/spring-projects/spring-graphql/tree/main/samples/webmvc-http

This is example is a little "simpliefied" (querydsl removed) because it only should demonstrate the missing `WebGraphqlTester` issue: https://github.com/spring-projects/spring-graphql/issues/96

Run tests:
`./mvnw clean verify`

-> Should fail with NotClassDefFoundError

Run:

`./mvnw spring-boot:run`

-> should start, but won't work correctly, as I removed the querydsl dependencies
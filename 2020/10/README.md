- 2020-10-06. Tue

```
📌 분류 : Java
📆 날짜 : 2020-10-06. Tue
🎯 제목 : 자바 뉴스
🧬 링크 : https://www.whiteship.me/java-news-2020-10-02/
📖 요약 : 자바 뉴스
```

- 2020-10-08. Thu

```
📌 분류 : Spring
📆 날짜 : 2020-10-08. Thu
🎯 제목 : SpringBoot에서 날짜 타입 JSON 변환에 대한 오해 풀기
🧬 링크 : https://jojoldu.tistory.com/361
📖 요약 : SpringBoot에서 날짜 타입 JSON 변환에 대한 오해 풀기
```

```
📌 분류 : Spring
📆 날짜 : 2020-10-08. Thu
🎯 제목 : Spring Boot에서 yyyy-MM 포맷으로 날짜 받고싶을때
🧬 링크 : https://jojoldu.tistory.com/527
📖 요약 : Spring Boot에서 yyyy-MM 포맷으로 날짜 받고싶을때
```

- 2020-10-12. Mon

```
📌 분류 : Spring
📆 날짜 : 2020-10-12. Mon
🎯 제목 : SpringBoot에서 날짜 타입 JSON 변환에 대한 오해 풀기
🧬 링크 : https://www.whiteship.me/java-news-2020-10-09/
📖 요약 : 자바뉴스, null 한정 서바이벌 가이드
```

- 2020-10-28. Wed

```
📌 분류 : Java
📆 날짜 : 2020-10-28. Wed
🎯 제목 : 함수형 프로그래밍에서의 에러처리
🧬 링크 : https://www.slipp.net/questions/449
📖 요약 : 함수형 프로그래밍에서의 에러처리
```

- 2020-10-30. Fri

```
📌 분류 : Java
📆 날짜 : 2020-10-30. Fri
🎯 제목 : @Transactional repository or service or seviceImpl
🧬 링크1 : https://stackoverflow.com/questions/1079114/where-does-the-transactional-annotation-belong
🧬 링크2 : http://javaprogrammingtips4u.blogspot.com/2010/04/how-to-use-transaction-manager-with.html
🧬 링크3 : https://stackoverflow.com/questions/5551541/where-to-put-transactional-in-interface-specification-or-implementation
🧬 링크4 : https://docs.spring.io/spring-framework/docs/3.0.x/spring-framework-reference/html/transaction.html
📖 요약 : @Transactional 의 적절한 위치는 세부 구현체에 두는게 맞다.
```
> Check out The Spring Docs -- "Tips" for more information.
>
> Spring recommends that you only annotate concrete classes (and methods of concrete classes) with the @Transactional annotation, as opposed to annotating interfaces. You certainly can place the @Transactional annotation on an interface (or an interface method), but this works only as you would expect it to if you are using interface-based proxies. The fact that Java annotations are not inherited from interfaces means that if you are using class-based proxies (proxy-target-class="true") or the weaving-based aspect (mode="aspectj"), then the transaction settings are not recognized by the proxying and weaving infrastructure, and the object will not be wrapped in a transactional proxy, which would be decidedly bad.
>
> Spring은 인터페이스에 주석을 추가하는 대신 @Transactional 주석으로 구체적인 클래스 (및 구체적인 클래스의 메서드)에만 주석을 달도록 권장합니다. 인터페이스 (또는 인터페이스 메소드)에 @Transactional 어노테이션을 배치 할 수 있지만 이는 인터페이스 기반 프록시를 사용하는 경우 예상 한 대로만 작동합니다. Java 주석이 인터페이스에서 상속되지 않는다는 사실은 클래스 기반 프록시 (proxy-target-class = "true") 또는 위빙 기반 측면 (mode = "aspectj")을 사용하는 경우 트랜잭션 설정이 다음과 같음을 의미합니다. 프록시 및 위빙 인프라에 의해 인식되지 않으며 객체가 트랜잭션 프록시에 래핑되지 않으므로 확실히 나쁠 것입니다.

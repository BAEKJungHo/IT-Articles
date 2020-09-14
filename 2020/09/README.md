- 2020-09-01. Tue

```
📌 분류 : IT
📆 날짜 : 2020-09-01. Tue
🎯 제목 : 자바 finalize 에 대한 아티클
🧬 링크 : https://brunch.co.kr/@oemilk/122
📖 요약 : 자바 finalize 에 대한 아티클
```

- 2020-09-02. Wed

```
📌 분류 : IT
📆 날짜 : 2020-09-02. Wed
🎯 제목 : 기술 면접 준비하기
🧬 링크 : https://velog.io/@hygoogi/%EA%B8%B0%EC%88%A0%EB%A9%B4%EC%A0%91-%EC%A4%80%EB%B9%84%ED%95%98%EA%B8%B0
📖 요약 : 기술 면접 준비하기
```

- 2020-09-03. Thu

```
📌 분류 : IT
📆 날짜 : 2020-09-03. Thu
🎯 제목 : 도커란 무엇인가?
🧬 링크 : https://subicura.com/2017/01/19/docker-guide-for-beginners-1.html#%EC%99%9C-%EC%9D%B4%EB%A0%87%EA%B2%8C-%ED%95%AB%ED%95%9C%EA%B0%80
📖 요약 : 도커란 무엇인가?
```


- 2020-09-04. Fri

```
📌 분류 : Design Pattern
📆 날짜 : 2020-09-04. Fri
🎯 제목 : 디자인패턴 전략패턴이란?
🧬 링크 : https://gmlwjd9405.github.io/2018/07/06/strategy-pattern.html
📖 요약 : 전략패턴에 대한 아티클
```

- 2020-09-05. Sat

```
📌 분류 : IT
📆 날짜 : 2020-09-05. Sat
🎯 제목 : 노코드의 시대
🧬 링크 : https://www.youtube.com/watch?v=2pPK2DjfaJc
📖 요약 : 중간단계(개발자)없이 간단한 웹 사이트를 개발할 수 있는 노코드 솔루션이 앞으로 대세가 될듯
```

- 2020-09-06. Sun

```
📌 분류 : Java
📆 날짜 : 2020-09-06. Sun
🎯 제목 : 일급컬렉션이란?
🧬 링크 : https://github.com/woowacourse/javable/blob/master/_posts/2020-05-08-First-Class-Collection.md
📖 요약 : 일급컬렉션에 대한 
```

- 2020-09-07. Mon

```
📌 분류 : Java
📆 날짜 : 2020-09-07. Mon
🎯 제목 : 자바 스레드
🧬 링크 : https://coding-factory.tistory.com/279
📖 요약 : 자바 스레드 
```

- 2020-09-08. Tue

```
📌 분류 : Design Pattern
📆 날짜 : 2020-09-08. Tue
🎯 제목 : 디자인패턴 팩토리 패턴
🧬 링크 : https://jusungpark.tistory.com/14
📖 요약 : 디자인패턴 팩토리 패턴에 대한 아티클
```

- 2020-09-10. Thu

```
📌 분류 : Spring
📆 날짜 : 2020-09-10. Thu
🎯 제목 : 스프링 빈이 아닌데 빈을 주입받고 싶은 경우
🧬 링크 : https://www.whiteship.me/spring-bean-dependency-injection/
📖 요약 : 컴포넌트 스캔 방식을 이용해서 빈으로 등록시켜서 주입받거나 직접 주입 시켜준다.
```

- 2020-09-11. Fri

```
📌 분류 : Java
📆 날짜 : 2020-09-11. Fri
🎯 제목 : 자바 Enum 의 활용
🧬 링크 : https://jojoldu.tistory.com/122
📖 요약 : VO 에 스트링 타입으로 선언된 경우 IDE 의 지원을 받을 수 없다(오타검증, 자동완성 등) 반면 상수나, Enum 은 IDE 지원을 받을 수 있다.
그리고 상수를 만드는 경우 인터페이스로 만들어서 Contract.xxx 이런식으로 사용할 수 있다.
```

- 코드 일부 발췌

```java
@RestController
public class ApiController {

    @GetMapping("/enum")
    public Map<String, Object> getEnum() {
        Map<String, Object> enums = new LinkedHashMap<>();

        // 이런식으로 점(.) 두 개를 사용한 이유는 EnumContract 라는 VO 에 선언된 Enum 타입을 통해서 가져오기 위함이다.
        // 이런식으로 해야 사용할때 더 명확하다. 바로 CommissionType 으로 하는경우 개발자의 경우는 CommissionType 를 사용해야한다는 걸 알지만
        // 처음 보는 사람들은 CommissionType 를 사용해야하는지 모른다.
        Class commissionType = EnumContract.CommissionType.class;
        Class commissionCutting = EnumContract.CommissionCutting.class;

        enums.put("commissionType", commissionType.getEnumConstants());
        enums.put("commissionCutting", commissionCutting.getEnumConstants());
        return enums;
    }
}
```


- 2020-09-14. Mon

```
📌 분류 : Java
📆 날짜 : 2020-09-14. Mon
🎯 제목 : 메서드 파라미터
🧬 링크 : https://jojoldu.tistory.com/232?category=635881
📖 요약 : 메서드를 파라미터로 전달하는 방법
```

- 2020-09-15. Tue

```
📌 분류 : Java
📆 날짜 : 2020-09-15. Tue
🎯 제목 : parseInt() 와 intValue() 의 차이
🧬 링크 : https://vitalholic.tistory.com/72
📖 요약 : parseInt() 는 String to int, intValue() 는 Integer 에서 int 값을 꺼내 쓰고 
```

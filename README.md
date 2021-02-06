# 코틀린 개념 정리

# 코틀린 특징

## 코틀린 특징

- 다양한 플랫폼 지원
    - JVM 기반의 서버, 안드로이드
    - 코틀린 자바스크립트
    - 코틀린- navtive
    - 코틀린-멀티 플랫폼-모바일(KMM)
- 정적 타입 언어
    - static typed lang ( Java, Kotlin)
    - dynamically tpyed lang  ( python)
- 타입 추론
    - val  x = 1 [//x는](//x는) 자동으로 integer
- 함수형 언어
- 오픈 소스

## 코틀린 철학

- 실용성
    - 이미 검증되고 많이 사용됨
- 간결성
    - getter/setter 사라짐
- 안정성
    - Null Safety
- 상호호완성
    - Java to Kotlin , Kotlin to Java 가능하다

## 패키지(Package)

- 자바와 달리 소스 파일의 위치와 이름을 정하는데에 제한이 없다
    - 패키지 구조와 디렉토리 구조가 일치할 필요가 없다

## 변수와 값(Variable & Value)

- val = value ( 지정된 값)
- var = variable(변경되는 값)
- 타입은 뒤에 선언함(타입추론을 통해 선언 필요없을 수도 있기에 덜 중요하여 뒤에 선언)

```kotlin
val a : Int = 1 //val a = 1 과 같음
var b : Int = 2
b = 3
```

## if 문

- 자바와 문법이 비슷하지만 statement가 아니라 expression으로 사용가능

    ```kotlin
    val x = if(a>10) "long" else "short"
    ```

## 타입 체크(is) , 타입 변환(as)

-

### String 템플릿

> **문자열 내에 변수나 표현식을 쉽게 삽입할 수 있는 기능
     -** 문자열을 더 간결하고 가독성 있게 작성할 수 있다
String 템플릿은 `$` 기호를 사용하여 변수를 참조하거나, 중괄호 `{}`를 사용하여 표현식을 포함한다
> 

변수참조

```kotlin
val name = "Kotlin"
val greeting = "Hello, $name!"
```

표현식 사용

```val a = 10
val b = 20
val result = "The sum of $a and $b is ${a + b}."
println(result)
```

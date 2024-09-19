### 함수 정의

<aside>
💡

함수는

- 특정한 동작을 하거나 원하는 결과값을 연산하는데 사용합니다

ex) main(), println()

Kotlin에서 함수는

- 내부적으로 기능을 가진 형태이지만 파라미터를 넣는다는 점 외에는 자료형이 결정된 변수라는 개념으로 적용된다.

</aside>

### infix함수

> Infix 함수는 두 개의 변수 가운데 오는 함수를 말한다.
**일반적인 함수 호출과는 다르게, 점(.)이나 괄호() 없이 사용할 수 있다**
> 

```kotlin
infix fun Int.add(x: Int): Int {
    return this + x
}

fun main() {
    println(3.add(5))		// 8
    println(3 add 5)		// 8
}
```

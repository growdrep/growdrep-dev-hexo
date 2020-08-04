---
title: kotlin-guide-01
date: 2020-08-04 11:36:14
categories:
- [Guide, JVM]
- [Guide, Kotlin]
---

# Kotlin Guide - 01

#### 이 가이드는 어느정도 프로그래밍과, Java 에 대해 아시는 분들에게 권장됩니다! 혹시 전혀 모르신다면, 다음에 한번 프로그래밍에 대해, 또 Java에 대해 Posting 해보겠습니다!

## 코틀린 가이드 - 코틀린이란 무엇인가

- Jetbrains 사가 개발한 JVM 바이트 코드 기반의 언어!
- 간결한 문법, Null로부터 안전한 언어
- 구글이 사랑하는, 안드로이드 개발의 표준 언어

## 특징

#### Kotlin
```kotlin
fun main(args: Array<String>) {
    println("Hello World!")
}
```

#### Java
```java
package me.growdrep.patrick;

public class Main() {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

- 정말 간단한 문법. Java를 해보셨다면 아시겠지만, Java의 문법은 정말로 깁니다...
- Class의 사용 규칙 변화. 파일명과 Public Class명이 일치하지 않아도 되며, 여러 클래스나 Class 없이 선언하기 등 왠만한게 모두 가능합니다!
- Null Safety! NullPointerException 오류를 볼 일이 상당히 줄어듭니다!
- 나머지 것들은 가이드를 작성하면서 하나하나 알아가도록 합시다!

## 다음 가이드 예고

다음 가이드에서는, Primitive Type을 비롯하여, Kotlin을 사용하기 전에 알아야 할 것들을 알아보도록 합시다!

감사합니다!

#### License

위 글은 2020년 8월 4일, post.growdrep.me에 올리는 글입니다.

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](http://creativecommons.org/licenses/by-nc-nd/4.0/).

이 저작물은 [크리에이티브 커먼즈 저작자표시-비영리-변경금지 4.0 국제 라이선스](http://creativecommons.org/licenses/by-nc-nd/4.0/)에 따라 이용할 수 있습니다.
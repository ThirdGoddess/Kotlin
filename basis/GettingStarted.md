

## 简介

Kotlin是一种在Java虚拟机上运行的静态类型编程语言，它也可以被编译成为JavaScript源代码。它主要是JetBrains开发团队所发展出来的编程语言，虽然与Java语法并不兼容，但在JVM环境中Kotlin被设计成可以和Java代码相互运作，并可以重复使用如Java集合框架等的现有Java引用的函数库。Hathibelagal写道，“如果你正在为Android开发寻找一种替代编程语言，那么应该试下Kotlin。它很容易在Android项目中替代Java或者同Java一起使用。”

---


## 为什么使用Kotlin，Java难道它不香吗？


- 早在2017年5月17日在旧金山召开的I/O开发者大会上，Google宣布Kotlin语言成为Android开发的第一语言。
- Kotlin检查异常，Kotlin提供检查异常，这是Java所没有的！因此，无需捕获或声明任何异常！
- 代码简洁，相比于Java，Kotlin代码更为简洁，在开发中，如果使用Kotlin，相比于Java可能会减少50%甚至更多！
- Kotlin和Java是完全兼容的！Kotlin可以直接调用Java所编写的代码！

---


## 已经会Java，还必须学习Kotlin吗？
建议学，毕竟，没有任何一门语言是无用的！孔子曰：“知之者不如好之者，好之者不如乐之者！”。

现在在招聘需求上，已经有很多要求会Kotlin的招聘！如果不会，岂不很尴尬！

---

## 简单了解
接下来简单了解下Kotlin！欣赏一下！

---

### Kotlin定义函数

```kotlin
fun main() {
    println("Hello World!")
}
```

由fun关键字进行函数的声明

---

### Kotlin定义变量

```kotlin
var a = 15
val b = 16
```

Kotlin关键字定义变量只有val和var，相当于一个有final修饰一个没有！

val b = 16 相当于Java中的 final int b = 16;

var a = 15 相当于Java中的 int a = 15;

---

### Kotlin逻辑控制 if条件语句

```kotlin
fun maxNum(num1: Int, num2: Int) {
    var value = 0

    if (num1 > num2) {
        value = num1
    } else {
        value = num2
    }
}
```

学过Java、C++等编程语言的都能看懂！

---

### Kotlin逻辑控制 when条件语句

```kotlin
fun main() {
    var value = 6
    var copyName = when (value) {
        1 -> "My name is 1"
        2 -> "My name is 2"
        3 -> "My name is 3"
        4 -> "My name is 4"
        5 -> "My name is 5"
        6 -> "My name is 6"
        else -> 0
    }
    print(copyName)
}
```
相当于Java中的switch结构，意思是：
如果value等于1，则copyName变量值为"My name is 1"
如果value等于2，则copyName变量值为"My name is 2"
...
如果以上条件都不符合，则copyName = 0。

---

### Kotlin for循环

```kotlin
fun main() {
    for(i in 0..100){
        print(i)
    }
}
```

循环0 - 100  （包括0和100）

---
### Kotlin while循环
```kotlin
fun main() {
    var a = 0
    while (a < 10) {
        a++
    }
}
```

如果a小于10，循环一次，执行a++

# raywenderlich.com Swift风格指南

因为该指南关注于网页上以及打印版的可读性，所以它与其他你可能阅读过的指南有所不同。为了保证那些在我们书中、教程里以及配套工程里的代码看上去美观且一致，我们写下了这份风格指南，尽管我们的书由许多不同作者共同创作而成。

我们的首要目标是让代码紧凑，可读性高且简洁。

正在用Objective-C写程序？也看看我们的[Objective-C风格指南][objc-style-guide]吧。

## 目录

* [语言](#语言)
* [间隔](#间隔)
* [注释](#注释)
* [注释](#注释)
* [类前缀](#类前缀)
* [类与结构体](#类与结构体)
* [函数声明](#函数声明)
* [闭包](#闭包)
* [类型](#类型)
  * [常量](#常量)
  * [Optionals](#Optionals)
  * [类型推断](#类型推断)
* [控制流](#控制流)
* [Self的使用](#Self的使用)
* [笑脸](#笑脸)
* [工作人员](#工作人员)

## 语言
	
使用美式英语拼写以匹配苹果的API

**优选**
```swift
var color = "red"
```

**不建议使用**
```swift
var colour = "red"
```

[objc-style-guide]: https://github.com/raywenderlich/objective-c-style-guide
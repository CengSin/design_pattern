# Bridge Pattern(桥接模式)

> 参考 [图说设计模式](https://design-patterns.readthedocs.io/zh_CN/latest/)

## 使用场景

设想一个场景，需要画一个矩形、圆形、椭圆形，绘制的图形需要具有不同的颜色，比如红色、蓝色、绿色等等。
这时候就需要又两种方案：

1. 每种图形都提供各种颜色的实现
2. 将图形的实现和颜色的实现分别提供一套，在使用的时候进行组合

对于有多个变化维度（五个以下）的系统，采用方案二来设计系统，可以使用更少的类，且系统拓展更方便。同样，2.方案就是桥接模式的应用，在桥接模式中，
将不同维度的变化拆分开来，通过关联关系将其组合到一块形成所需要的对象，降低了不同维度之间的耦合度，减少了代码编写量。

## 桥接模式是什么

桥接模式：把事物对象和其具体行为、具体特称分离开来，使他们可以个子独立的变化。事物对象仅是一个抽象概念。

wiki:https://zh.wikipedia.org/wiki/%E6%A9%8B%E6%8E%A5%E6%A8%A1%E5%BC%8F

## 桥接模式怎么用

在使用代码实现桥接模式之前，首先要了解/抽象桥接模式中的对象。通常来说，桥接模式可以抽象为下面的四个/多个（不要局限于数字）对象。

- Abstraction 事物的抽象声明，是一个抽象类。其中包含了事物里的属性声明。
- 

## 桥接模式的优缺点


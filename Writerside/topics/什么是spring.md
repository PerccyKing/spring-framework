# 什么是spring

> 什么是spring

> 对spring的理解

特性：IOC（控制反转）、AOP（面向切面编程）


- 容器
  - 管理bean对象
  - 管理bean的生命周期
- 生态
  - spring boot
  - spring cloud
  - 。。。
- 基础
  - 所有spring生态都以spring作为基础进行扩展开发
- IOC和AOP

> spring 是一个java基础框架，同时提供了一个bean的容器，用于管理bean对象以及其生命周期，
> 没有spring的时候，我们需要使用new来创建对象，有了spring 容器过后，所有的对象都交由spring进行同样管理，
> 并且在spring的基础之上，有SpringBoot、spring cloud等组件，都是基于spring进行扩展开发的。
> 
> spring中有两个很重要的特性 IOC和AOP
> IOC 控制反转，之前需要我们自己进行new的对象，都可以由spring进行管理，调用的时候，不用关注bean的创建流程，只需要进行使用
> AOP 面向切面编程，使用AOP可以对业务进行一些扩展增强，日志、权限、事务等功能都可以使用AOP来实现
{style=note}
## 2.1 Dependency Injection and Inversion of Control

# 2.1 依赖注入和控制反转 {#依赖注入和控制反转}

A Java application — a loose term that runs the gamut from constrained, embedded applications to n-tier, server-side enterprise applications — typically consists of objects that collaborate to form the application proper. Thus the objects in an application have_dependencies_on each other.

Java 应用程序--运行在各个松散的领域,从受限的嵌入式应用程序,到 n 层架构的服务端企业级应用程序--通常由来自应用适当的对象进行组合合作。因此,对象在应用程序中是彼此依赖。

Although the Java platform provides a wealth of application development functionality, it lacks the means to organize the basic building blocks into a coherent whole, leaving that task to architects and developers. Although you can use design patterns such as_Factory_,_Abstract Factory_,_Builder_,_Decorator_, and_Service Locator_to compose the various classes and object instances that make up an application, these patterns are simply that: best practices given a name, with a description of what the pattern does, where to apply it, the problems it addresses, and so forth. Patterns are formalized best practices that_you must implement yourself_in your application.

尽管 Java 平台提供了丰富的应用程序开发功能,但它缺乏来组织基本构建块成为一个完整的方法。这个任务留给了架构师和开发人员。虽然您可以使用设计模式,例如 Factory, Abstract Factory, Builder, Decorator, 和 Service Locator 来组合各种类和对象实例构成应用程序,这些模式是:给出一个最佳实践的名字,描述什么模式,哪里需要应用它,它要解决什么问题,等等。模式是形式化的最佳实践,但你必须在应用程序中_自己来实现_。

The Spring Framework_Inversion of Control_\(IoC\) component addresses this concern by providing a formalized means of composing disparate components into a fully working application ready for use. The Spring Framework codifies formalized design patterns as first-class objects that you can integrate into your own application\(s\). Numerous organizations and institutions use the Spring Framework in this manner to engineer robust,_maintainable_applications.

Spring Framework 的_Inversion of Control_\(IoC\) 组件旨在通过提供正规化的方法来组合不同的组件成为一个完整的可用的应用。 Spring Framework 将规范化的设计模式作为一等的对象,您可以集成到自己的应用程序。许多组织和机构使用 Spring Framework 以这种方式来开发健壮的、可维护的应用程序。

```
Background
"The question is, what aspect of control are [they] inverting?" Martin Fowler posed this question about Inversion of Control (IoC)
on his site
in 2004. Fowler suggested renaming the principle to make it more self-explanatory and came up withDependency Injection.
```

```
控制反转和依赖注入的背景
“问题是，[他们]哪些方面的控制被反转？”这个问题由 Martin Fowler在他的 Inversion of Control (IoC)
网站http://martinfowler.com/articles/injection.html
在 2004 年提出。 Fowler 建议重新命名这个说法,使得他更加好理解,并且提出了 Dependency Injection（依赖注入） 这个新的说法。
```



## 

  



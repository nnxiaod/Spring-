The Spring Framework is a lightweight solution and a potential one-stop-shop for building your 
enterprise-ready applications. 

Spring框架是一个轻量级、一站式的企业级应用解决方案。


However, Spring is modular, allowing you to use only those parts that you need, 
without having to bring in the rest. 

并且Spring是模块化的，允许你只使用你需要的部分，而无须全部引用。


You can use the IoC container, with any web framework on top, 
but you can also use only the Hibernate integration code or the JDBC abstraction layer. 

你可以将IoC容器和任何顶层框架同时使用，也可以只使用Hibernate集成代码或者JDBC抽象层。


The Spring Framework supports declarative transaction management, 
remote access to your logic through RMI or web services, 
and various options for persisting your data. 

Spring框架支持声明式事务管理，支持RMI或者web service远程调用，还提供各种数据持久化选项。


It offers a full-featured MVC framework, 
and enables you to integrate AOP transparently into your software.

它提供了完整的MVC框架，并且可以容易地集成AOP功能。


Spring is designed to be non-intrusive, 
meaning that your domain logic code generally has no dependencies on the framework itself. 

Spring是非侵入的，这意味着你的领域逻辑代码通常不依赖框架本身。


In your integration layer (such as the data access layer), 
some dependencies on the data access technology and the Spring libraries will exist. 

在集成方面（比如数据访问层），Spring提供一些数据访问技术相关的依赖和库文件。


However, it should be easy to isolate these dependencies from the rest of your code base.

但是，将你的业务代码和这些依赖隔离开来是很容易的。


This document is a reference guide to Spring Framework features. 

本文档是Spring框架特征的参考指南。


If you have any requests, comments, or questions on this document, 
please post them on the user mailing list. 

如果你对本文档有任何要求、想法或疑问，请在用户邮件列表中提出。


Questions on the Framework itself should be asked on StackOverflow (see https://spring.io/questions).

对于Spring框架本身的问题，可以在StackOverflow网站进行提问（详见 https://spring.io/questions ）。
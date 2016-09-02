# Fagena
Web Application Using Spring MVC

Spring framework helps you build java applications faster because it allows you to focus on you business problem rather nam the plumbing code that connects components and systems. The framework, in broader sense, can be defined as a structure where we find solution of the various technical problems.
The Spring framework comprises several modules such as IOC, AOP, DAO, Context, ORM, WEB MVC etc. 
 
Features of Spring: 

Modem Web: complete support for modern applications including REST, HTML5, Conversation and Ajax 
Data Access: support traditional RDBMS as well as new noSQL solutions, Map-reduce frameworks and cloud base data access.
Integration: enterprice orchestration and adapters for distributed applications and batch application
Mobile: web support for mobile client platforms including Android and iPhone 
Social: intergration with Fracebook, Twitter, LinkedIn and other prominat social networks
Security: Authorization control for all tiers and authorization integration to dozens of providers  
Cloud Ready: Spring applications are supported on all popular cloud platforms like Cloud Foundry, Google App Engine, and Amazon EC2.  

Whats special about spring
Spring support dependencies Injection: Basically if you have one java object which depends on another java object, you can inject the second java object to the first java object using XML bolt the two objects together. 
Aspect Oriented: This added functionality for your existing classes. 


IOC (Inversion Of Control) And Dependency Injection:

These are the design patterns that are used to remove dependency from the programming code. They make the code easier to test and maintain.   IOC makes the code loosely coupled. In such case, there is no need to modify the code if our logic is moved to new environment.
In Spring framework, IOC container is responsible to inject the dependency. We provide metadata to the IOC container either by XML file or annotation.
Advantages of Dependency Injection: makes the code loosely coupled so easy to maintain and makes the code easy to test. 

Advantage of Spring Framework:
Predefined Templates: Spring framework provides templates for JDBC, Hibernate, JPA etc. technologies. So there is no need to write too much code. It hides the basic steps of these technologies.Let's take the example of JdbcTemplate, you don't need to write the code for exception handling, creating connection, creating statement, committing transaction, closing connection etc. You need to write the code of executing query only. Thus, it save a lot of JDBC code.
Loose Coupling: Spring application are loosely coupled because of dependency injection. 
Easy to test: The Dependency Injection makes easier to test the application. The EJB or Struts application require server to run the application but Spring framework doesn't require server.
Lightweight: Spring framework is lightweight because of its POJO implementation. The Spring Framework doesn't force the programmer to inherit any class or implement any interface. That is why it is said non-invasive.
Fast Development: The Dependency Injection feature of Spring Framework and it support to various frameworks makes the easy development of JavaEE application.
Powerfull abstraction: It provides powerful abstraction to JavaEE specifications such as JMS, JDBC, and JTA. 
Declarative support: it provides declarative support for caching, validation, transactions  and formatting.

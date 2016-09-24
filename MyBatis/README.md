---
 title: JavaWeb学习之MyBatis
---

## JavaWeb学习之MyBatis

###一、MyBatis简介：
1、MyBatis是一个数据持久层(ORM)框架，把实体类和SQL语句之间建立了映射关系，是一种半自动化的ORM实现。
2、MyBatis消除了几乎所有的JDBC代码和参数的手动设置以及结果集的检索。
3、MyBatis使用简单的XML或注解用于配置和原始映射，将接口和Java的POJOs(Plan Old Java Objects，普通的Java对象)映射成数据库中的记录。
4、MyBatis优点：
	- 基于SQL语法，简单易学
	- 能了解底层组装过程
	- SQL语句封装在配置文件中，便于统一管理与维护，降低了程序的耦合度
	- 程序调试方便

5、ORM工具的基本思想：
	无论是用过hibernate，mybatis，都可以发现一个共同点：
	- 从配置文件(通常是XML配置文件中)得到sessionfactory。
	- 有sessionfactory产生session
	- 在session中完成对数据的增删改查和事务提交等。
	- 在用完之后关闭session。
	- 在Java对象和数据库之间有做mapping的配置文件，也通常是xml文件。
	

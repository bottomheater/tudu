##tudu

本项目是基于Tudu Lists 2.3重构，Tudu lists是一个WEb应用的开源项目，用于管理todo的，也可以用于项目管理。

网站：http://www.julien-dubois.com/tudu-lists.html

项目源码：https://github.com/jdubois/Tudu-Lists



##关于本项目

本项目是基于Tudu Lists 2.3重构，目前涉及到两个子项目tudu-dwr和tudu-core，其中tudu-dwr为Action层，tudu-core为Service层和Domain层，前者通过Maven引用后者。

目前的目标：

1.国际化添加中文。

2.使用Struts2或SpringMVC重构Action层。

3.使用EasyUI重构前端页面。

4.更新涉及的技术框架。



##涉及技术

前端：JSP(Ver 2.4)、DWR(Ver 2.0.2)、GWT、Portlet

逻辑层：Spring(Ver 2.5.6，包括Spring Web Flow和Spring MVC)，Struts(Ver 1.2.9，包括Struts-Menu)，Acegi(Ver 1.0.6)、DBUnit(Ver 2.1)

持久层：JPA/Hibernate(Ver 3.3)、Encache(Ver 1.4.0)

数据库：MySQL、HSQLDB(Ver 1.8.0.7)

WebService框架：Axis、xfire

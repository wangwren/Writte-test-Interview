## JSP与Servlet的区别
### JSP出现背景
Servlet体系是基于B/S架构开发的web应用程序，使用Servlet类将HTTP请求和响应封装在标准Java类中来实现各种web应用方案的。当大量的B/S架构程序开发出来以后出现了很多问题:首先servlet类有大量冗余代码，其次是开发Servlet的没法做到有精美的页面效果。所以sun提出将服务器端代码添加在已经设计好的静态页面上，**经过JSP容器对JSP文件进行自动解析并转换成Servlet类来交给web服务器运行**。  
### JSP本质
JSP在本质上就是Servlet，但是两者的创建方式不一样。Servlet都是有Java程序代码构成，用于流程控制和事务处理，通过Servlet来生成动态网页很不直观。而JSP由HTML代码和JSP标签构成，可以方便地编写动态网页。
### JSP与Servlet不同
- 编译:JSP修改后可以立即看到结果，不需要编译；而Servlet需要编译。
- 转换:JSP是动态网页开发技术，是运行在服务器端的脚本语言。而Servlet是web服务器端编程技术。所以**JSP运行时就是转换为Servlet**，也就是java程序来执行。
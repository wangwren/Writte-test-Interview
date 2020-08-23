# 记录笔试和面试遇到的问题
# 笔试.
- [单例设计模式](http://wangwren.com/2019/06/%E5%8D%95%E4%BE%8B%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F/)

# 面试
## Java相关
- [线程](https://github.com/wangwren/JUC)
- [List、Set、Map区别(目前公司都爱问)](https://github.com/wangwren/Written-test-Interview/blob/master/List、Set、Map区别.md)
- [为什么说ArrayList是线程不安全的](https://github.com/wangwren/Written-test-Interview/blob/master/%E4%B8%BA%E4%BB%80%E4%B9%88%E8%AF%B4ArrayList%E6%98%AF%E7%BA%BF%E7%A8%8B%E4%B8%8D%E5%AE%89%E5%85%A8%E7%9A%84.md)
- 说一说hashSet
- HashSet与HashMap区别
- HashMap的底层实现
- [foreach遍历集合时进行remove操作的问题](http://wangwren.com/2019/02/foreach%E9%81%8D%E5%8E%86%E9%9B%86%E5%90%88%E6%97%B6%E8%BF%9B%E8%A1%8Cremove%E6%93%8D%E4%BD%9C%E7%9A%84%E9%97%AE%E9%A2%98/)
- Java回收机制
- Java异常处理，以及常见的异常※

### Servlet

- [EL表达式的内置对象](https://github.com/wangwren/Written-test-Interview/blob/master/EL%E8%A1%A8%E8%BE%BE%E5%BC%8F%E5%86%85%E7%BD%AE%E5%AF%B9%E8%B1%A1.md)
  - 扩充:[jsp的九大内置对象](https://github.com/wangwren/Written-test-Interview/blob/master/JSP%E4%B9%9D%E5%A4%A7%E5%86%85%E7%BD%AE%E5%AF%B9%E8%B1%A1%E5%8F%8A%E5%9B%9B%E4%B8%AA%E4%BD%9C%E7%94%A8%E5%9F%9F.md)

- [jsp与servlet区别](https://github.com/wangwren/Written-test-Interview/blob/master/JSP%E4%B8%8EServlet%E5%8C%BA%E5%88%AB.md)

- jsp作用域※

- 说一说cookie和session(今日头条)

- cookie和session从哪产生(东软)

- 如何实现网站用户三个月免登录(东软)

- Servlet的生命周期※



## 框架

#### MyBatis

- [自定义持久层框架](https://github.com/wangwren/all_homework/tree/master/mybatis/code)
- [Mybatis动态sql是做什么的？都有哪些动态sql？简述一下动态sql的执行原理？](https://github.com/wangwren/all_homework/tree/master/mybatis/%E7%AE%80%E7%AD%94%E9%A2%98#mybatis%E5%8A%A8%E6%80%81sql%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B%E5%8A%A8%E6%80%81sql%E7%AE%80%E8%BF%B0%E4%B8%80%E4%B8%8B%E5%8A%A8%E6%80%81sql%E7%9A%84%E6%89%A7%E8%A1%8C%E5%8E%9F%E7%90%86)
- [动态sql执行原理](https://github.com/wangwren/all_homework/tree/master/mybatis/%E7%AE%80%E7%AD%94%E9%A2%98#%E5%8A%A8%E6%80%81sql%E6%89%A7%E8%A1%8C%E5%8E%9F%E7%90%86)
- [Mybatis是否支持延迟加载？如果支持，它的实现原理是什么？](https://github.com/wangwren/all_homework/tree/master/mybatis/%E7%AE%80%E7%AD%94%E9%A2%98#mybatis%E6%98%AF%E5%90%A6%E6%94%AF%E6%8C%81%E5%BB%B6%E8%BF%9F%E5%8A%A0%E8%BD%BD%E5%A6%82%E6%9E%9C%E6%94%AF%E6%8C%81%E5%AE%83%E7%9A%84%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86%E6%98%AF%E4%BB%80%E4%B9%88)
- [Mybatis都有哪些Executor执行器？它们之间的区别是什么？](https://github.com/wangwren/all_homework/tree/master/mybatis/%E7%AE%80%E7%AD%94%E9%A2%98#mybatis%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9Bexecutor%E6%89%A7%E8%A1%8C%E5%99%A8%E5%AE%83%E4%BB%AC%E4%B9%8B%E9%97%B4%E7%9A%84%E5%8C%BA%E5%88%AB%E6%98%AF%E4%BB%80%E4%B9%88)
- [简述下Mybatis的一级、二级缓存（分别从存储结构、范围、失效场景。三个方面来作答）？](https://github.com/wangwren/all_homework/tree/master/mybatis/%E7%AE%80%E7%AD%94%E9%A2%98#%E7%AE%80%E8%BF%B0%E4%B8%8Bmybatis%E7%9A%84%E4%B8%80%E7%BA%A7%E4%BA%8C%E7%BA%A7%E7%BC%93%E5%AD%98%E5%88%86%E5%88%AB%E4%BB%8E%E5%AD%98%E5%82%A8%E7%BB%93%E6%9E%84%E8%8C%83%E5%9B%B4%E5%A4%B1%E6%95%88%E5%9C%BA%E6%99%AF%E4%B8%89%E4%B8%AA%E6%96%B9%E9%9D%A2%E6%9D%A5%E4%BD%9C%E7%AD%94)



#### Spring

[Spring事务的传播行为](http://wangwren.com/2019/02/Spring%E4%BA%8B%E5%8A%A1%E7%9A%84%E4%BC%A0%E6%92%AD%E8%A1%8C%E4%B8%BA/#more)





## 计算机网络
### TCP协议，Http协议(阿里，微鲤科技)
### 三次握手(阿里，微鲤科技，今日头条)
### 四次挥手(今日头条)
#### 四次挥手最后客户端有个time_wait
### HTTP状态码(今日头条，艾漫数据)

### 控制台运行一个程序按ctrl+c就会终止，此时都发生了什么(今日头条)
## 数据库
### Redis(必问，数据结构，持久化)
### 索引※

### [数据库事务的特性和隔离级别](http://wangwren.com/2019/02/%E6%95%B0%E6%8D%AE%E5%BA%93%E4%BA%8B%E5%8A%A1%E7%9A%84%E7%89%B9%E6%80%A7%E4%BB%A5%E5%8F%8A%E9%9A%94%E7%A6%BB%E7%BA%A7%E5%88%AB/)

### mysql索引(今日头条)

### 左右连接区别※

### MySQL引擎※

## 数据结构
### 如何使用两个栈来实现一个队列(今日头条)

## Nginx
### Nginx负载均衡策略
# springboot-multipledatasources
springboot中多数据源整合的总结

sql脚本在multipledatasources中，4个项目都是同一个sql脚本

multipledatasources：
jpa-mybatis-多数据源的整合，其目的就是jpa用来增删改，mybatis用来查询，我认为没有比mybatis更适合查询的框架了。
还有就是测试了异步和定时任务的功能

multipledatasources2：
通过分包实现多数据源的，检测多数据源存在的事务管理问题

multipledatasources3：
通过jta-atomikos解决传统项目多数据源事务管理问题

multipledatasources4：
通过aop的方式实现多数据源

multipledatasources5：
通过aop的方式实现多数据源  spring boot 2.0

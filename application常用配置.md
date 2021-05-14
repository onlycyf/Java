Java中Mysql常用配置

application

```
# mysql
spring:
  datasource:
    username: root
    password: 123456
    url: jdbc:mysql://localhost:3306/Java_test?userSSL=false&userUnicode=true&characterEncoding=utf-8&serverTimezone=GMT%2B8
    driver-class-name: com.mysql.cj.jdbc.Driver
    
# mybatis配置日志
mybatis-plus:
  configuration:
    log-impl: org.apache.ibatis.logging.stdout.StdOutImpl

```
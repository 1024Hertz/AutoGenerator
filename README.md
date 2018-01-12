# AutoGenerator
自动生成器


# Maven添加Oracle数据库JDBC驱动

* Maven生成的pom格式 

```
<dependency>
    <groupId>com.oracle</groupId>
    <artifactId>ojdbc6</artifactId>
    <version>11.2.0.1.0</version>
</dependency>
```
* 执行语句

```
mvn install:install-file -DgroupId=com.oracle -DartifactId=ojdbc6 -Dversion=11.2.0.1.0 -Dpackaging=jar -Dfile=ojdbc6.jar
```
* 附件

[Oracle驱动下载地址](http://www.oracle.com/technetwork/database/enterprise-edition/jdbc-112010-090769.html)


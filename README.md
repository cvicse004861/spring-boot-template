# Spring Boot Template

> spring boot 工程模板
> 
> 包含maven友好的打包命令

## 使用
 
获取模板后参照`pom.xml`和`application.yml`文件中的注释进行修改

## 运行

```shell
mvn spring-boot:run #可以使用Ctrl+C停止
mvn spring-boot:start #只能使用mvn spring-boot:stop停止
```

## 打包

```shell
mvn package -P jar-dev #打开发jar包
mvn package -P jar-test #打测试jar包
mvn package -P jar-prod #打生产jar包
mvn package -P war-dev #打开发war包
mvn package -P war-test #打测试war包
mvn package -P war-prod #打生产war包
```
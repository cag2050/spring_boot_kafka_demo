Spring Boot 2.x 集成 Kafka

### 步骤一：创建 Kafka 容器
1.下载镜像：
```
docker pull landoop/fast-data-dev:2.3.0
```
2.创建容器：
```
docker run -p 2181:2181 -p 3030:3030 -p 8081:8081 -p 8082:8082 -p 8083:8083 -p 9092:9092 -e ADV_HOST=127.0.0.1 landoop/fast-data-dev:2.3.0
```
> 参考：https://www.jianshu.com/p/daea2db9cceb

### 步骤二：创建项目，编写代码
> 参考：http://www.54tianzhisheng.cn/2018/01/05/SpringBoot-Kafka/

### 参考：
参考资料 | 网址
--- | ---
KAFKA 测试/开发环境快速构建（docker 使用部分） | https://www.jianshu.com/p/daea2db9cceb
Spring Boot系列文章（一）：SpringBoot Kafka 整合使用（项目创建及代码部分）| http://www.54tianzhisheng.cn/2018/01/05/SpringBoot-Kafka/
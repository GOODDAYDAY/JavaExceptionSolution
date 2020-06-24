* 类型
    * com.netflix.discovery.shared.transport.TransportException

* 关键字
    * eureka
    * login
    * 无法注册
    * 注册报错

* 报错情形描述
    * 一、Cannot execute request on any known server

* 解决方案
    * 一、检查url是否正确，是否可以路由到相应的eureka上。

    * 二、修改.yaml、.properties文件(该方法治标不治本，还是无法连接到eureka上)

    ```yaml
    eureka.client.registerWithEureka=false   #是否要注册到其他Server上   registerWithEureka等同于register_with_eureka
    eureka.client.fetchRegistry=false        #是否需要拉取服务信息       fetchRegistry等同于 fetch-registry
    ```

    * 三、清空eureka依赖包，重新下载对应版本依赖。

    ```pom
    <dependency>
        <groupId>org.springframework.cloud</groupId>
        <artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
        <version>x.x.x.RELEASE</version>
    </dependency>
    ```

* [返回首页](https://github.com/GOODDAYDAY/JavaExceptionSolution)
<p>&nbsp;</p>
<div align="center">
	<img alt="logo" src="https://gh-proxy.com/github.com/Rukawalee/cloud-images/blob/master/images/cloud-me-nobg.png" width="200">
</div>
<h4 align="center">基于 SpringBoot 3 / SpringCloud & Alibaba 集成的分布式微服务架构体系</h4>



> [!Note]
>
> Java 开发已有些年头，感受时间变迁，时代进步，科技创新。回头看，这几年沉淀欠缺，要丰富过去的凝练总结。我想基于 Spring
> 落地一个后端脚手架，归纳过去开发经验沉淀而成的分布式微服务架构体系。

#### 目标

&nbsp; &nbsp; &nbsp; &nbsp;总结开发经验，研习 Spring 生态，集成优秀的开源框架，沉淀一套可用的微服务架构体系。

#### 架构

![cloud-me 架构](https://gh-proxy.com/github.com/Rukawalee/draw.io/blob/master/cloud-me/cloud-me-architecture.drawio.svg)

#### 特性

* 依赖 [Nacos](https://nacos.io/) 动态配置管理、服务发现管理。

* 依赖 [Dubbo](https://cn.dubbo.apache.org/zh-cn/overview/what/) 解决微服务架构下的服务治理与通信。
* 依赖 [Seata](https://seata.apache.org/zh-cn/) 提供高性能和简单易用的分布式事务服务。
* 依赖 [Kafka](https://kafka.apache.org/) 高吞吐消息队列。
* 依赖 [SkyWalking](http://skywalking.apache.org/) 分布式追踪、服务网格遥测分析、度量聚合。
* 依赖 [Sentinel](https://sentinelguard.io/zh-cn/index.html) 流量控制、流量路由、熔断降级。
* 依赖 [PowerJob](http://www.powerjob.tech/) 分布式任务调度。
* 依赖 [SpringBoot](https://spring.io/projects/spring-boot) 轻松创建独立的生产级应用程序。
* 依赖 [MyBatis](https://mybatis.org/mybatis-3/zh_CN/index.html) 持久层框架映射数据库记录。
* 依赖 [MariaDB](https://mariadb.org/)  持久化业务数据。
* 依赖 [Redis](https://redis.io/downloads/) 高性能缓存数据库。
* 依赖 [Elasticsearch](https://www.elastic.co/cn/elasticsearch) 搜索和分析引擎。
* 依赖 [MinIO](https://www.minio.org.cn/) 高性能对象存储。

# 企业级 Prometheus 监控设计与部署

## 一、技能描述

- 能够熟练安装、配置和管理 Prometheus 监控系统，包括配置文件编写、数据存储和查询等方面；
- 能够熟练使用 Prometheus 常见的 Exporters，如 Node Exporter、MySQL Exporter、Blackbox Exporter、Pushgateway 等，在业务应用中对关键性能指标进行监控；
- 熟悉 Prometheus 告警机制，能够编写和配置 Alertmanager 规则文件，进行告警通知和故障处理；
- 熟悉 Grafana 可视化工具，能够结合 Prometheus 数据源创建仪表盘和图表，对数据图像化展示和监控定制化进行实现；
- 熟悉 Kubernetes 集群监控，能够使用 Prometheus-Operator 或 kube-prometheus 方案进行定制化监控；
- 熟悉 Prometheus 故障排查和性能优化，能够使用 PromQL 进行高级查询和分析，提高监控数据的有效性和可靠性。

## 二、项目经验

**1、系统层监控**

> **系统监控**：CPU、Memory、Disk、Disk IO、Load、Processes ...
>
> **网络监控**：网络延迟、丢包率、网络设备、工作负载 ...

![image-20230403162430367](https://csdn-rab.oss-cn-chengdu.aliyuncs.com/img/image-20230403162430367.png)

部分截图！

**2、中间件监控**

> **消息中间件**：Kafka、RacketMQ、RabbitMQ ...
>
> **Web 中间件**：Nginx、Tomcat、Jetty ...
>
> **DB 及缓存系统**：MySQL、PostgreSQL、MongoDB、ES ...
>
> **存储系统**：Ceph、MinIO ...

![image-20230403163944514](https://csdn-rab.oss-cn-chengdu.aliyuncs.com/img/image-20230403163944514.png)

![image-20230403174259684](https://csdn-rab.oss-cn-chengdu.aliyuncs.com/img/image-20230403174259684.png)

![image-20230609115131215](https://csdn-rab.oss-cn-chengdu.aliyuncs.com/img/image-20230609115131215.png)

部分截图！

**3、应用层监控**

> 应用程序代码状态、性能，各类应用层协议。

![image-20230403162227697](https://csdn-rab.oss-cn-chengdu.aliyuncs.com/img/image-20230403162227697.png)

部分截图！

**4、业务层监控**

待补充...

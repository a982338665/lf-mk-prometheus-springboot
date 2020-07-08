# lf-mk-prometheus-springboot
实现监控系统Prometheus。介绍CNCF云原生及微服务实际监控需求，介绍Devops、MDD、CNCF、Prometheus等概念，搭建基于Spring Boot2的实战监控体系，体会企业项目面向DevOps开发的监控情景。
面向运维和开发者

## 1.课程重点

>监控的意义  
>Metrics Driven Development：MDD理念  
>CNCF第二个毕业项目Prometheus剖析  
>Prometheus + Grafana 监控实战  
>SpringBoot2 基于Prometheus支付场景监控及告警实战   
>Prometheus深度探讨
>k8s与Prometheus由Google开源

## 2.微服务与云原生下的监控图景

  1.监控目的：  
  * 长期趋势分析
  * 对照分析
  * 告警
  * 故障分析和定位  
  
  2.Prometheus：参考官方文档
  * 监控微服务
  * node_exporter监控操作系统
  * mysqld——exporter监控mysql
  * 监控redis
  * 监控Flink
  * 监控RabbitMQ/Kafka
  * 监控etcd [Prometheus Operate]
  * 监控k8s
  * 监控其他
 
  3.MDD：
  * 软件研发：实时感知应用各项指标，聚焦应用优化
  * 运维人员：实时感知系统各项指标，快速定位问题
  
### 3.Prometheus监控实践
#### 3.1 Prometheus介绍与架构

   1.开发语言：go语言实现  
   2.以拉模式为主  
   3.多维度-标签  
   4.黑盒白盒支持 
   5.单机性能强劲，上千target，每秒百万级时间序列   
   
#### 3.2 Prometheus环境搭建
#### 3.3 Prometheus环境文件及存储解析
#### 3.4 Grafana环境搭建
#### 3.5 Grafana集成Prometheus实战
### 4.Springboot2.x集成Prometheus
#### 4.1 Springboot Micrometer
#### 4.2 Prometheus分层监控结构实验
#### 4.3 Springboot，Prometheus
### 5.Prometheus告警实战
### 6.Prometheus高级拓展
### 7.课后总结，学习方法
  

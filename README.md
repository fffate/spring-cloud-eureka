# spring-cloud-eureka

spring-cloud-eureka学习笔记

CAP原理：
C：一致性
A：可用性
P：分区兼容性

eureka主要完成为服务架构中的服务治理功能
spring-cloud 为eureka增加了spring-boot风格的自动化配置，实现和spring-boot的整合


服务治理：是为服务架构中的基础和最核心模块，主要用来实现各个微服务实例的自动化注册和发现。

问题：为什么要用服务治理模块？没有该模块为怎样？

名词解释：注册中心、服务单元、服务注册、服务发现、心跳检测、服务剔除


Netflix Eureka 包含了服务端和客户端组件。

 Eureka服务端，也称为服务注册中心。  支持高可用配置。
 Eureka客户端，主要处理服务的注册和发现。
 


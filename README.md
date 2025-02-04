点击关注[公众号](#公众号)及时获取笔主最新更新文章，并可免费领取本文档配套的《Java面试突击》以及Java工程师必备学习资源。

**[推荐一下阿里云双12的活动，优惠福利比双11还大系列，新老用户同享！（新用户 ECS 1 核 2g 一年只要 89!）](https://www.aliyun.com/minisite/goods?userCode=hf47liqn&share_source=copy_link)**

<p align="center">
<a href="https://github.com/Snailclimb/JavaGuide" target="_blank">
	<img src="https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-3/logo - 副本.png" width=""/>
</a>
</p>

<p align="center">
  <a href="https://snailclimb.gitee.io/javaguide"><img src="https://img.shields.io/badge/阅读-read-brightgreen.svg" alt="阅读"></a>
  <a href="#联系我"><img src="https://img.shields.io/badge/chat-微信群-blue.svg" alt="微信群"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-JavaGuide-lightgrey.svg" alt="公众号"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/PDF-Java面试突击-important.svg" alt="公众号"></a>
  <a href="#投稿"><img src="https://img.shields.io/badge/support-投稿-critical.svg" alt="投稿"></a>
  <a href="https://xiaozhuanlan.com/javainterview?rel=javaguide"><img src="https://img.shields.io/badge/Java-面试指南-important" alt="投稿"></a>
</p>

<h3 align="center">Sponsor</h3>
<p align="center">
  <a  href="https://url.163.com/hXm" >
<img src="https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-7/WechatIMG1.png"width="" style="margin: 0 auto;"/>
  </a >
</p>

推荐使用  https://snailclimb.gitee.io/javaguide 在线阅读，在线阅读内容本仓库同步一致。这种方式阅读的优势在于：阅读体验会更好。

## 目录

- [Java](#java)
    - [基础](#基础)
    - [容器](#容器)
    - [并发](#并发)
    - [JVM](#jvm)
    - [I/O](#io)
    - [Java 8](#java-8)
    - [优雅 Java 代码必备实践(Java编程规范)](#优雅-java-代码必备实践java编程规范)
- [网络](#网络)
- [操作系统](#操作系统)
    - [Linux相关](#linux相关)
- [数据结构与算法](#数据结构与算法)
    - [数据结构](#数据结构)
    - [算法](#算法)
- [数据库](#数据库)
    - [MySQL](#mysql)
    - [Redis](#redis)
    - [数据库扩展](#数据库扩展)
- [系统设计](#系统设计)
    - [常用框架(Spring/SpringBoot、Zookeeper ... )](#常用框架)
    - [数据通信/中间件(消息队列、RPC ... )](#数据通信中间件)
    - [权限认证](#权限认证)
    - [分布式 & 微服务](#分布式--微服务)
      - [API 网关](#api-网关)
      - [配置中心](#配置中心)
      - [唯一 id 生成](#唯一-id-生成)
      - [服务治理：服务注册与发现、服务路由控制](#服务治理服务注册与发现服务路由控制)
    - [架构](#架构)
    - [设计模式(工厂模式、单例模式 ... )](#设计模式)
- [面试指南](#面试指南)
    - [备战面试](#备战面试)
    - [面经](#面经)
- [Java学习常见问题汇总](#java学习常见问题汇总)
- [工具](#工具)
    - [Git](#git)
    - [Docker](#Docker)
- [资源](#资源)
    - [书单](#书单)
    - [Github榜单](#Github榜单)
- [待办](#待办)
- [说明](#说明)

## Java

### 基础

* **[Java 基础知识回顾](docs/java/Java基础知识.md)**
* **[Java 基础知识疑难点/易错点](docs/java/Java疑难点.md)**
* **[一些重要的Java程序设计题](docs/java/Java程序设计题.md)**
* [J2EE 基础知识回顾](docs/java/J2EE基础知识.md)

### 容器

* **[Java容器常见面试题/知识点总结](docs/java/collection/Java集合框架常见面试题.md)**
* [ArrayList 源码学习](docs/java/collection/ArrayList.md)  
* [LinkedList 源码学习](docs/java/collection/LinkedList.md)   
* [HashMap(JDK1.8)源码学习](docs/java/collection/HashMap.md)  

### 并发

* **[Java 并发基础常见面试题总结](docs/java/Multithread/JavaConcurrencyBasicsCommonInterviewQuestionsSummary.md)**
* **[Java 并发进阶常见面试题总结](docs/java/Multithread/JavaConcurrencyAdvancedCommonInterviewQuestions.md)**
* [并发容器总结](docs/java/Multithread/并发容器总结.md)
* **[Java线程池学习总结](./docs/java/Multithread/java线程池学习总结.md)**
* [乐观锁与悲观锁](docs/essential-content-for-interview/面试必备之乐观锁与悲观锁.md)
* [JUC 中的 Atomic 原子类总结](docs/java/Multithread/Atomic.md)
* [AQS 原理以及 AQS 同步组件总结](docs/java/Multithread/AQS.md)

### JVM

* **[一 Java内存区域](docs/java/jvm/Java内存区域.md)**
* **[二 JVM垃圾回收](docs/java/jvm/JVM垃圾回收.md)**
* [三 JDK 监控和故障处理工具](docs/java/jvm/JDK监控和故障处理工具总结.md)
* [四 类文件结构](docs/java/jvm/类文件结构.md)
* **[五 类加载过程](docs/java/jvm/类加载过程.md)**
* [六 类加载器](docs/java/jvm/类加载器.md)
* **[【待完成】八 最重要的 JVM 参数指南（翻译完善了一半）](docs/java/jvm/最重要的JVM参数指南.md)**
* [九 JVM 配置常用参数和常用 GC 调优策略](docs/java/jvm/GC调优参数.md)

### I/O

* [BIO,NIO,AIO 总结 ](docs/java/BIO-NIO-AIO.md)
* [Java IO 与 NIO系列文章](docs/java/Java%20IO与NIO.md)

### Java 8 

* [Java 8 新特性总结](docs/java/What's%20New%20in%20JDK8/Java8Tutorial.md)
* [Java 8 学习资源推荐](docs/java/What's%20New%20in%20JDK8/Java8教程推荐.md)
* [Java8 forEach 指南](docs/java/What's%20New%20in%20JDK8/Java8foreach指南.md)

### 优雅 Java 代码必备实践(Java编程规范)

* [Java 编程规范以及优雅 Java 代码实践总结](docs/java/Java编程规范.md)

## 网络

* [计算机网络常见面试题](docs/network/计算机网络.md)
* [计算机网络基础知识总结](docs/network/干货：计算机网络知识总结.md)
* [HTTPS中的TLS](docs/network/HTTPS中的TLS.md)

## 操作系统

### Linux相关

* [后端程序员必备的 Linux 基础知识](docs/operating-system/后端程序员必备的Linux基础知识.md)  
* [Shell 编程入门](docs/operating-system/Shell.md) 

## 数据结构与算法

### 数据结构

- [不了解布隆过滤器？一文给你整的明明白白！](docs/dataStructures-algorithms/data-structure/bloom-filter.md)
- [数据结构知识学习与面试](docs/dataStructures-algorithms/数据结构.md)

### 算法

- [算法学习资源推荐](docs/dataStructures-algorithms/算法学习资源推荐.md)  
- [几道常见的字符串算法题总结 ](docs/dataStructures-algorithms/几道常见的子符串算法题.md)
- [几道常见的链表算法题总结 ](docs/dataStructures-algorithms/几道常见的链表算法题.md)   
- [剑指offer部分编程题](docs/dataStructures-algorithms/剑指offer部分编程题.md)
- [公司真题](docs/dataStructures-algorithms/公司真题.md)
- [回溯算法经典案例之N皇后问题](docs/dataStructures-algorithms/Backtracking-NQueens.md)

## 数据库

### MySQL

* **[【推荐】MySQL/数据库 知识点总结](docs/database/MySQL.md)**
* **[阿里巴巴开发手册数据库部分的一些最佳实践](docs/database/阿里巴巴开发手册数据库部分的一些最佳实践.md)**
* **[一千行MySQL学习笔记](docs/database/一千行MySQL命令.md)**
* [MySQL高性能优化规范建议](docs/database/MySQL高性能优化规范建议.md)
* [数据库索引总结](docs/database/MySQL%20Index.md)
* [事务隔离级别(图文详解)](docs/database/事务隔离级别(图文详解).md)
* [一条SQL语句在MySQL中如何执行的](docs/database/一条sql语句在mysql中如何执行的.md)

### Redis

* [Redis 总结](docs/database/Redis/Redis.md)
* [Redlock分布式锁](docs/database/Redis/Redlock分布式锁.md)
* [如何做可靠的分布式锁，Redlock真的可行么](docs/database/Redis/如何做可靠的分布式锁，Redlock真的可行么.md)
* [几种常见的 Redis 集群以及使用场景](docs/database/Redis/redis集群以及应用场景.md) 

### 数据库扩展

代办......

## 系统设计

### 常用框架

#### Spring/SpringBoot

- [Spring 学习与面试](docs/system-design/framework/spring/Spring.md)
- **[Spring 常见问题总结](docs/system-design/framework/spring/SpringInterviewQuestions.md)**
- **[SpringBoot 指南/常见面试题总结](https://github.com/Snailclimb/springboot-guide)**
- [Spring中bean的作用域与生命周期](docs/system-design/framework/spring/SpringBean.md)
- [SpringMVC 工作原理详解](docs/system-design/framework/spring/SpringMVC-Principle.md)
- [Spring中都用到了那些设计模式?](docs/system-design/framework/spring/Spring-Design-Patterns.md)

#### ZooKeeper

- [ZooKeeper 相关概念总结](docs/system-design/framework/ZooKeeper.md)
- [ZooKeeper 数据模型和常见命令](docs/system-design/framework/ZooKeeper数据模型和常见命令.md)

### 数据通信/中间件

- [数据通信(RESTful、RPC、消息队列)相关知识点总结](docs/system-design/data-communication/summary.md)

#### RPC

- [Dubbo 总结：关于 Dubbo 的重要知识点](docs/system-design/data-communication/dubbo.md)
- [服务之间的调用为啥不直接用 HTTP 而用 RPC？](docs/system-design/data-communication/why-use-rpc.md)

#### 消息队列

- [消息队列总结](docs/system-design/data-communication/message-queue.md)
- [RabbitMQ 入门](docs/system-design/data-communication/rabbitmq.md)
- [RocketMQ的几个简单问题与答案](docs/system-design/data-communication/RocketMQ-Questions.md)
- [Kafka入门看这一篇就够了](docs/system-design/data-communication/Kafka入门看这一篇就够了.md)
- [Kafka系统设计开篇-面试看这篇就够了](docs/system-design/data-communication/Kafka系统设计开篇-面试看这篇就够了.md)

### 权限认证

- **[权限认证基础:区分Authentication,Authorization以及Cookie、Session、Token](docs/system-design/authority-certification/basis-of-authority-certification.md)**
- **[JWT 优缺点分析以及常见问题解决方案](docs/system-design/authority-certification/JWT-advantages-and-disadvantages.md)**
- **[适合初学者入门 Spring Security With JWT 的 Demo](https://github.com/Snailclimb/spring-security-jwt-guide)**

### 分布式 & 微服务

- [分布式应该学什么](docs/system-design/website-architecture/分布式.md)

#### API 网关

网关主要用于请求转发、安全认证、协议转换、容灾。

- [浅析如何设计一个亿级网关(API Gateway)](docs/system-design/micro-service/API网关.md)

#### 配置中心

代办......

#### 唯一 id 生成

 [分布式id生成方案总结](docs/system-design/micro-service/分布式id生成方案总结.md)

#### 服务治理：服务注册与发现、服务路由控制

代办......

### 架构

- [8 张图读懂大型网站技术架构](docs/system-design/website-architecture/8%20张图读懂大型网站技术架构.md)
- [【面试精选】关于大型网站系统架构你不得不懂的10个问题](docs/system-design/website-architecture/关于大型网站系统架构你不得不懂的10个问题.md)

### 设计模式

- [设计模式系列文章](docs/system-design/设计模式.md)

## 面试指南

### 备战面试

* **[【备战面试1】程序员的简历就该这样写](docs/essential-content-for-interview/PreparingForInterview/程序员的简历之道.md)**
* **[【备战面试2】初出茅庐的程序员该如何准备面试？](docs/essential-content-for-interview/PreparingForInterview/interviewPrepare.md)**
* **[【备战面试3】7个大部分程序员在面试前很关心的问题](docs/essential-content-for-interview/PreparingForInterview/JavaProgrammerNeedKnow.md)**
* **[【备战面试4】Github上开源的Java面试/学习相关的仓库推荐](docs/essential-content-for-interview/PreparingForInterview/JavaInterviewLibrary.md)**
* **[【备战面试5】如果面试官问你“你有什么问题问我吗？”时，你该如何回答](docs/essential-content-for-interview/PreparingForInterview/面试官-你有什么问题要问我.md)**
* [【备战面试6】应届生面试最爱问的几道 Java 基础问题](docs/essential-content-for-interview/PreparingForInterview/应届生面试最爱问的几道Java基础问题.md)
* **[【备战面试6】美团面试常见问题总结(附详解答案)](docs/essential-content-for-interview/PreparingForInterview/美团面试常见问题总结.md)**
* **[【备战面试7】一些刁难的面试问题总结](https://xiaozhuanlan.com/topic/9056431872)**

### 面经

- [5面阿里,终获offer(2018年秋招)](docs/essential-content-for-interview/BATJrealInterviewExperience/5面阿里,终获offer.md)
- [蚂蚁金服2019实习生面经总结(已拿口头offer)](docs/essential-content-for-interview/BATJrealInterviewExperience/蚂蚁金服实习生面经总结(已拿口头offer).md)
- [2019年蚂蚁金服、头条、拼多多的面试总结](docs/essential-content-for-interview/BATJrealInterviewExperience/2019alipay-pinduoduo-toutiao.md)

## Java学习常见问题汇总

- [Java学习路线和方法推荐](docs/questions/java-learning-path-and-methods.md)
- [Java培训四个月能学会吗？](docs/questions/java-training-4-month.md)
- [新手学习Java，有哪些Java相关的博客，专栏，和技术学习网站推荐？](docs/questions/java-learning-website-blog.md)

## 工具

### Git

* [Git入门](docs/tools/Git.md)

### Docker

* [Docker 基本概念解读](docs/tools/Docker.md)
* [一文搞懂 Docker 镜像的常用操作！](docs/tools/Docker-Image.md)

### 其他

- [阿里云服务器使用经验](docs/tools/阿里云服务器使用经验.md)

## 资源

### 书单

- [Java程序员必备书单](docs/data/java-recommended-books.md)

### 实战项目推荐

- [Github 上热门的 Spring Boot 项目实战推荐](docs/data/spring-boot-practical-projects.md)

### Github

- [Github 上 Star 数最多的 10 个项目，看完之后很意外!](docs/tools/github/github-star-ranking.md)
- [Java 项目月榜单](docs/github-trending/JavaGithubTrending.md)

***

## 待办

- [x] Java 多线程类别知识重构
- [ ] Netty 总结(---正在进行中---)
- [ ] 数据结构总结重构(---正在进行中---)

## 说明

### JavaGuide介绍

*  **对于 Java 初学者来说：** 本文档倾向于给你提供一个比较详细的学习路径，让你对于Java整体的知识体系有一个初步认识。另外，本文的一些文章
也是你学习和复习 Java 知识不错的实践；
*  **对于非 Java 初学者来说：** 本文档更适合回顾知识，准备面试，搞清面试应该把重心放在那些问题上。要搞清楚这个道理：提前知道那些面试常见，不是为了背下来应付面试，而是为了让你可以更有针对的学习重点。

Markdown 格式参考：[Github Markdown格式](https://guides.github.com/features/mastering-markdown/)，表情素材来自：[EMOJI CHEAT SHEET](https://www.webpagefx.com/tools/emoji-cheat-sheet/)。

利用 docsify 生成文档部署在 Github pages: [docsify 官网介绍](https://docsify.js.org/#/)



# shigebeyond 的开源技术
## 概述

|  开源项目 | 语言 | 介绍  |
| ------------ | ------------ | ------------ |
| [k8scmd](https://github.com/shigebeyond/k8scmd) | python | 精简k8s与 Argo Workflows 命令 |
| [K8sBoot](https://github.com/shigebeyond/K8sBoot) | python | 简化k8s资源定义文件 |
| [ArgoFlowBoot](https://github.com/shigebeyond/ArgoFlowBoot) | python | 简化 Argo Workflows 工作流定义文件 |
| [SparkBoot](https://github.com/shigebeyond/SparkBoot) | python | yaml 驱动 Spark 开发 |
| [ExcelBoot](https://github.com/shigebeyond/ExcelBoot) | python | yaml 驱动 Excel 生成 |
| [HttpBoot](https://github.com/shigebeyond/HttpBoot) | python | yaml驱动的接口自动化与压测 |
| [SeleniumBoot](https://github.com/shigebeyond/SeleniumBoot) | python | yaml驱动的web 自动化 |
| [AppiumBoot](https://github.com/shigebeyond/AppiumBoot) | python | yaml驱动的app 自动化 |
| [MiniumBoot](https://github.com/shigebeyond/MiniumBoot) | python | yaml驱动的小程序自动化 |
| [jktest](https://www.zhihu.com/zvideo/1630268717249634304) | python | 测试平台 |
| [MonitorBoot](https://github.com/shigebeyond/MonitorBoot) | python | yaml 驱动 linux 系统监控与 jvm 监控与告警  |
| [pyutilb](https://github.com/shigebeyond/pyutilb) | python | python 开发工具类集 |
| [HttpRunnerManager](https://github.com/shigebeyond/HttpRunnerManager) | python | HttpRunnerManager 改造 |
| [swg2hrun](https://github.com/shigebeyond/swg2hrun) | python | Swagger api转HttpRunnerManager用例 |
| [jkcfg](https://github.com/shigebeyond/jkcfg) | python | 配置信息同步器 |
| [m3u8dwn](https://github.com/shigebeyond/m3u8dwn) | python | m3u8视频下载器 |
| [async4jsonrpc](https://github.com/shigebeyond/async4jsonrpc) | python | python的json rpc框架 |
| [pynput_recorder](https://github.com/shigebeyond/pynput_recorder)  | python | 键鼠录制与重放 |
| [skmvc](https://github.com/shigebeyond/skmvc) | php | php mvc框架 |
| [jkmvc](https://github.com/shigebeyond/jkmvc) | kotlin/java | java mvc框架 |
| [jksoa](https://github.com/shigebeyond/jksoa) | kotlin/java | java微服务框架 |
| [jkutil](https://github.com/shigebeyond/jkutil) | kotlin/java | java工具类集 |
| [jkmq](https://github.com/shigebeyond/jkmq) | kotlin/java | 封装了多个mq client |
| [jkjob](https://github.com/shigebeyond/jkjob) | kotlin/java | 轻量级分布式作业调度库 |
| [jkguard](https://github.com/shigebeyond/jkguard) | kotlin/java | 流量守护者 |
| [jphp-java-ext](https://github.com/shigebeyond/jphp-java-ext) | kotlin/java | jphp 扩展 |
| [codegen](https://github.com/shigebeyond/codegen) | kotlin/java/jphp | 旧版代码生成器 |
| [jk-yapix](https://github.com/shigebeyond/jk-yapix) | kotlin/java | yapix(idea 插件)改造 |
| [tenancy](https://github.com/shigebeyond/tenancy) | kotlin/java | 基于 jkmvc 框架的多租户实现 |
| [chrome-ext](https://github.com/shigebeyond/chrome-ext) | js | chrome 扩展 |
| [wechat-components](https://github.com/shigebeyond/wechat-components) | js | 封装了常用的小程序组件 |

## k8s工具体系
1. [k8scmd](https://github.com/shigebeyond/k8scmd): 精简k8s与 Argo Workflows 命令
2. [K8sBoot](https://github.com/shigebeyond/K8sBoot): 简化k8s资源定义文件
3. [ArgoFlowBoot](https://github.com/shigebeyond/ArgoFlowBoot): 简化 Argo Workflows 工作流定义文件

## 大数据体系
1. [SparkBoot](https://github.com/shigebeyond/SparkBoot): SparkBoot: yaml 驱动 Spark 开发, 仅编写 yaml与 sql 即可实现复杂的 Spark 编程 
2. [ExcelBoot](https://github.com/shigebeyond/ExcelBoot): ExcelBoot: yaml 驱动 Excel 生成 

## 自动化测试技术体系
1. [HttpBoot](https://github.com/shigebeyond/HttpBoot): yaml驱动的接口自动化与压测
2. [SeleniumBoot](https://github.com/shigebeyond/SeleniumBoot): yaml驱动的web 自动化
3. [AppiumBoot](https://github.com/shigebeyond/AppiumBoot): yaml驱动的app 自动化
4. [MiniumBoot](https://github.com/shigebeyond/MiniumBoot): yaml驱动的小程序自动化
5. [jktest 测试平台](https://www.zhihu.com/zvideo/1630268717249634304): 基于 flask+vue 3实现，打通4端自动化测试技术
6. [HttpRunnerManager](https://github.com/shigebeyond/HttpRunnerManager): HttpRunnerManager 改造: 根据测试流程与测试团队的需求，改造自动化测试 python 框架 HttpRunnerManager ，支持套件内有序、在报告中输出变量与 curl 命令、请求带 cookie 等功能 
7. [swg2hrun](https://github.com/shigebeyond/swg2hrun): 解析 Swagger api ，自动生成 HttpRunnerManager 测试用例，兼容 Swagger v2 与 v3 版本 

## web框架
1. [jkmvc](https://github.com/shigebeyond/jkmvc): 用 kotlin 实现的java web 极速开发框架
```
1 精简的 mvc, 少配置少注解, 支持 ssh或 ssm 大部分功能, 还支持异步 servlet/ThreadLocal 安全/手脚架等，简单易用;
2 支持完备的数据库 ORM, ActiveRecord 模式, 支持 query builder /校验器/联合主键/复杂关联关系/多数据库分页/读写分离;
3 支持 Elasticsearch ORM, 底层基于 jest, 提供 ORM 实体/仓库类/query dsl, 比市面上的 es client 库都要简单/灵活/易写;
4 支持 jphp写 controller, 结合 php 的动态性与容错框架 jkguard, 可充当网关.
```
2. [skmvc](https://github.com/shigebeyond/skmvc): skmvc 框架: 使用 php 实现的 mvc/orm 框架 

## 微服务框架
1. [jksoa](https://github.com/shigebeyond/jksoa): 用 kotlin 实现的 java 微服务框架，组件如下
```
1 jksoa-rpc: 分布式异步 rpc 组件, 包含 registry / rpc-client / rpc-server 的3个子组件;
2 jksoa-guard: 应用守护者组件, 提供了请求合并/流量统计/熔断/限流/降级/缓存等多功能的守护;
3 jksoa-tracer: 分布式跟踪的组件, 支持 jaeger 实现;
4 jksoa-dtx: 分布式事务的组件, 包含 dtx-mq / dtx-tcc 的2个子组件;
5 支持 jphp 调用;
6 支持接入k8s，并利用其服务发现机制，无需 registry.
```

2. [async4jsonrpc](https://github.com/shigebeyond/async4jsonrpc): 基于asyncio来实现json rpc的python异步框架

## 通用的开发库
1. [pyutilb](https://github.com/shigebeyond/pyutilb): python 开发工具类集，涵盖文件读写、日志、时间转换、线程池、图像识别、ThreadLocal 、原子操作、定时器、延迟属性、订阅文件变化、基于 zookeeper 实现的远程配置文件等工具类 
2. [jkutil](https://github.com/shigebeyond/jkutil): 一些常用的轻量的java工具类
3. [jkmq](https://github.com/shigebeyond/jkmq): 是封装了多个mq client, 简化mq的生产与消费, 目前仅支持 kafka / rabbitmq / redis, 同时仅 kafka 实现支持广播。 
4. [jkjob](https://github.com/shigebeyond/jkjob): 是一个轻量级分布式作业调度库
5. [jkguard](https://github.com/shigebeyond/jkguard): 是流量守护者, 提供了请求合并/流量统计/熔断/限流/降级/缓存等多功能的守护
6. [jkcfg](https://github.com/shigebeyond/jkcfg): 配置信息同步器
7. [jphp-java-ext](https://github.com/shigebeyond/jphp-java-ext): jphp 扩展，增强 jphp对 java 对象的操作能力; 已集成到 jkmvc/jksoa, 支持在 jvm 上使用 php 语言来实现 web与 rpc, 可做模板与网关等 
8. [tenancy](https://github.com/shigebeyond/tenancy): 基于 jkmvc 框架的多租户实现, 支持租户识别、日志隔离、db 隔离、缓存隔离、文件系统隔离、分库等特性 

## 低代码开发平台
1. GeekerPlus 低代码开发平台: 未开源，demo: http://jkerp.junianhua.com/jkerp ，账号是admin

## 代码自动生成器
1. [codegen](https://github.com/shigebeyond/codegen): 基于 jkmvc + jphp 实现的的代码生成器，只开源了旧版实现，新版未开源

## idea插件
1. [jk-yapix](https://github.com/shigebeyond/jk-yapix): yapix(idea 插件)改造，支持解析 kotlin 代码、导出 jkmvc 框架的 api 接口、根据 jksoa 框架中的 java 服务接口来生成 php 映射类 

## chrome插件
1. [chrome-ext](https://github.com/shigebeyond/chrome-ext): chrome 扩展，支持以下功能：复制知乎回答、网页剪报、翻译、远程打开、备份标签页、导出 http 请求(导出格式有 curl/HttpRunner/HttpBoot/LocustBoot) 

## 监控
1. [MonitorBoot](https://github.com/shigebeyond/MonitorBoot): yaml 驱动 linux 系统监控与 jvm 监控与告警 

## 下载器
1. [m3u8dwn](https://github.com/shigebeyond/m3u8dwn): m3u8视频下载器，支持多协程异步下载 

## 键鼠录制与重放
1. [pynput_recorder](https://github.com/shigebeyond/pynput_recorder): 键鼠录制与重放

## 小程序组件
1. [wechat-components](https://github.com/shigebeyond/wechat-components): 封装了常用的小程序组件

## react-native组件
TODO: 我开发的组件库已跟不上react-native频繁更新的版本，因此暂不列出
# 联系方式

* 手机/微信号：18220000775
* Email：ponder09@outlook.com

# 个人信息

* 王鑫/男/25岁
* 软件工程/本科
* 工作年限：4年
* 应聘职位：Java开发工程师
* 应聘城市：西安
* 期望薪资：面议

# 技能清单

* 熟练使用Java，包括多线程、线程池、锁、CompletableFuture、反射、JUC等
* 熟练使用SpringBoot、SpringCloud、SpringSecurity、MyBatis、Netty等框架
* 熟练使用MySQL、Redis、ElasticSearch、ClickHouse
* 熟练使用常见的分布式组件，有Redisson，Xxl-job组件的项目实战经验
* 熟练使用RabbitMQ，Kafka消息队列，熟悉常见消息队列问题的解决方案
* 丰富的系统优化经验，包括SQL优化，索引优化，慢接口优化等
* 熟练使用常见设计模式，有良好的编码习惯，对代码质量有较高要求
* 有从0到1的项目需求分析、表结构设计、业务编码的经验
* 熟练使用前端框架Vue，ElementUI
* 了解Linux基本操作、Docker基本使用
* 了解Kubernetes的Pod、Deployment、Service、Ingress等基本组件的使用
* 了解Golang，Python





# 工作经历

## CDP集团（上海 2021年3月 ~ 2023年2月）

### 绩效管理系统

项目简介：该项目是基于公司SaaS体系下的一个应用模块，主要为租户提供员工绩效考核、审批的数字化。主要功能有考核流程配置，待办超时提醒，考核打分，结果申诉等。

职责描述：

1. 从0到1负责该项目，从项目的需求分析到表设计，再到功能实现
2. 独立编写简易工作流引擎，包含流程节点自定义，流转，驳回等功能
3. 独立编写绩效得分计算核心业务，使用策略模式解决多种计算模式的组合问题
4. 利用Java反射实现了可配置的、字段级别的数据权限功能，解决绩效系统的数据比较敏感的问题
5. 利用MySQL的JSON字段类型，支持了数据多语言功能，使得代码改动较小
6. 集成企业微信、钉钉、飞书第三方服务商，为租户提供消息通知功能
7. 使用CompletableFuture解决项目中批量任务时接口超时问题
8. 引入QLExpress，使租户可自定义配置指标得分的计算公式
9. 二次开发mzt-biz-log的操作日志组件，记录项目运行中的操作日志（xx在xx时间做了xx操作，改动了xx资源）

## 东联信息技术有限公司 （西安 2019年4月 ~ 2021年3月）

### 智能云联系统

项目简介：该项目是一个物联网的平台，主要面向运营商，便于基站维护人员的日常维护和操作。主要功能包含智能锁，手机连接蓝牙即可开锁；节能设备，通过AI分析，计算适合节能的时间段，并下发给硬件去执行；智能电表，可以在平台上实时看到电量的使用情况。

职责描述：

1. 重构处理硬件数据的服务，引入RabbitMQ消息队列，降低系统瞬时处理的并发量
3. 硬件上报数据量巨大，为减轻mysql数据库的读写压力，使用SQLite存储冷数据
4. 负责硬件终端数据上报的解析及存储，包括电量上报，告警上报等
6. 负责编写下发指令的代码，包括策略下发，终端配置文件下发等

# 开源项目和技术文章（PDF可点击访问）

## 开源项目
[后台管理系统框架](https://github.com/WangXin3/Spirngboot_vue)：前端使用Vue+ElementUI，后端使用Spring Boot、Mybatis、JWT、Spring Security等框架实现的前	后端分离的后台管理系统。可用于快速搭建前后端分离的管理系统，也被人用于大学毕设的脚手架项目。

[图书管理系统](https://github.com/WangXin3/library-management)：本人的本科毕设，基于后台管理系统框架。前端使用Vue+ElementUI，后端使用Spring Boot、MybatisPlus、Spring Security、Redis、MySQL等框架。包含了用户管理，角色管理，权限管理，图书分类管理，图书管理，借阅管理等功能。代码逻辑清晰，代码规范，可用作毕设参考项目。

## 技术文章

* [RabbitMQ消息模型详解，你只需要这一篇](https://blog.csdn.net/w306026355/article/details/105467182)
* [Kafka基本概念以及整合SpringBoot](https://blog.csdn.net/w306026355/article/details/128584232)
* [玩转CompletableFuture线程异步编排，看这一篇就够了](https://blog.csdn.net/w306026355/article/details/109707269)
* [简简单单学习ThreadPoolExecutor线程池](https://blog.csdn.net/w306026355/article/details/109586661)

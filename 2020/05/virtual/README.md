# 第 10 届 Service Mesh Meetup 暨 Service Mesh Virtual Meetup #1

因为疫情的原因，ServiceMesher 社区暂时无法举办线下 meetup，因此我们将活动改为线上，将采用 B 站直播的形式。本期为第一届 Service Mesh Virtual Meetup 线上系列直播，邀请了四位来自不同公司的嘉宾，从四个角度对 Service Mesh 的应用实践展开分享。

本次线上 meetup 分享涵盖 Service Mesh 的可观察性和生产实践。为大家介绍 Service Mesh 中的可观察性与传统微服务中可观察性的区别，如何使用 SkyWalking 来观测 Service Mesh，还有来自百度和陌陌的 Service Mesh 生产实践。

### 直播安排

- 直播地址：https://live.bilibili.com/21954520
- 视频回放：https://space.bilibili.com/228717294/channel/detail?cid=126804

| 时间       | 分享主题                                           | 分享嘉宾                  |
| :--------- | :------------------------------------------------- | :------------------------ |
| 5 月 6 日  | 陌陌的 Service Mesh 实践                           | 高飞航 陌陌中间件架构师   |
| 5 月 7 日  | Apache SkyWalking 在 Service Mesh 中的可观察性应用 | 高洪涛 Tetrate 创始工程师 |
| 5 月 13 日 | Service Mesh 高可用在企业级生产中的实践            | 罗广明 百度高级研发工程师 |
| 5 月 14 日 | Service Mesh 中的可观察性实践                      | 叶志远 G7 微服务架构师    |

### 陌陌的 Service Mesh 实践

- 时间：2020/5/6（周三） 19:00-20:00
- 嘉宾：高飞航 陌陌中间件架构师
- 嘉宾简介：在微服务、多机房架构及中间件产品领域有较为深入的研究，当前关注 Service Mesh、云原生等技术方向。
- Topic 简介：本期分享讲介绍陌陌从传统微服务架构转向 Service Mesh 架构的探索历程，以及在 Service Mesh 落地实践中关键方案与思考。

### Apache SkyWalking 在 Service Mesh 中的可观察性应用

- 时间：2020/5/6（周四） 19:00-20:00
- 嘉宾：高洪涛 Tetrate 创始工程师
- 嘉宾简介：FoundingEngineer 美国 Service Mesh 服务商 Tetrate 创始工程师。原华为软件开发云技术专家，对云原生产品有丰富的设计，研发与实施经验。对分布式数据库、容器调度、微服务、Servic Mesh 等技术有深入的了解。目前为 Apache ShardingSphere 和 Apache SkyWalking 核心贡献者，参与该开源项目在软件开发云的商业化进程。前当当网系统架构师，开源达人，曾参与 Elastic-Job 等知名开源项目。对开源项目的管理，推广和社区运营有丰富的经验。
- Topic 简介：Service Mesh 的可观测性是其重要的实践领域。业界翘楚 Istio 使用 Jaeger+Promethues 技术打造其可观测体系。而各个云提供商也分别将自己的监控方案融合在对 Service Mesh 的观测中。可观测性一般包含三个领域：Metric 监控指标、Tracing 分布式追踪和日志搜集。SkyWalking 对前两个领域都有涉猎。SkyWalking 是较早涉足了对 Istio 的 Metric 指标分析的开源项目。从早期的 Mixer 方案一直追踪到后期的与 Envoy 融合方案，同时得益于 MOSN 社区的支持，目前完成 MOSN 对 SkyWalking 追踪模型的支持。本次分享将分别以 Isito 与 MOSN 为例，介绍 SkyWalking 对 Service Mesh 的可观测性的支持。

### Service Mesh 高可用在企业级生产中的实践

- 时间：2020/5/13（周三） 19:00-20:00
- 嘉宾：罗广明 百度高级研发工程师
- 嘉宾简介：百度高级研发工程师，开源项目与云原生技术爱好者，ServiceMesher 社区治理委员会核心成员，对微服务架构、模型、中间件有深入研究。
- Topic 简介：Service Mesh 在企业落地中有诸多挑战，当与传统微服务应用共同部署治理时可用性挑战更为严峻。本次分享将以 Service Mesh 与 Spring Cloud 应用“互联互通、共同治理”为出发点，着重介绍基于 consul 的注册中心的高可用方案，通过智能路由策略实现服务间调用的高可用，以及通过各种限流、熔断策略保证后端服务的高可用。

### Service Mesh 中的可观察性实践

- 时间：2020/5/14（周四） 19:00-20:00
- 嘉宾：叶志远 G7 微服务架构师
- 嘉宾简介：Spring Cloud 中国社区联合创始人，ServiceMesher 社区成员，《重新定义 Spring Cloud 实战》作者，国内微服务领域早期实践者，云原生追随者。
- Topic 简介：监控是一个老生常谈的话题，而云原生的出现，将监控提升到了一个新的高度，那就是 Oberservability，译作可观察性，它是一种理念，是一种与伸缩性、可用性等非业务性需求同等重要的理念。Service Mesh 是云原生架构中专门治理服务间通讯问题的代理组件，我们有必要随时了解它的运行情况。本次分享将介绍 CNCF Oberservability Landscape，传统监控与可观察性在方法论上的区别，以现实的角度思考 Tracing、Logging、Metrics 三大问题，以及 Service Mesh 可观察性中间件的选型哲学。
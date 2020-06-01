# Service Mesh Webinar #1 多点生活在 Service Mesh 上的实践——Istio + MOSN 在 Dubbo 场景下的探索之路

Service Mesh Webinar 是由 ServiceMesher 社区和 CNCF 联合发起的线上直播活动，活动将不定期举行，邀请社区成员为大家带来 Service Mesh 领域的知识和实践分享。

Service Mesh Webinar#1，邀请多点生活平台架构组研发工程师陈鹏，带来分享《多点生活在 Service Mesh 上的实践——Istio + MOSN 在 Dubbo 场景下的探索之路》。

随着多点生活的业务发展，传统微服务架构的面临升级困难的问题。在云原生的环境下，Service Mesh 能给我们带来什么好处。如何使用社区解决方案兼容现有业务场景，落地成符合自己的 Service Mesh 成为一个难点。服务之间主要通过 Dubbo 交互，本次分享将探索 Istio + MOSN 在 Dubbo 场景下的改造方案。

**直播时间：**2020年5月28日（周四）20:00-21:00

**直播回放：**https://www.bilibili.com/video/BV15k4y1r7n8

## 分享嘉宾

陈鹏，多点生活平台架构组研发工程师，开源项目与云原生爱好者，有多年的网上商城、支付系统相关开发经验，2019年至今从事云原生和 Service Mesh 相关开发工作。

## 详情

**解决思路:**

从 MCP、Pilot、xDS、MOSN 技术，对 Service Mesh 的可切入点分析。

**成果：**

结合现有业务场景和可切入点，明确需要修改的场景，制定符合自己业务场景的 Service Mesh 落地方案，介绍多点生活在 Dubbo 案例的探索及改造方案。

**大纲：**

- 传统微服务架构与 Service Mesh 架构
  - 传统微服务架构在多点遇到的痛点
  - Service Mesh 架构能带来的福利
- Istio 技术点介绍
- 在 Dubbo 场景下的改造分析
  - 对比 MOSN 和 Envoy 对现有场景的支持
  - Istio+MOSN 和 Istio+Envoy 在 Dubbo 场景下如何改造
- MOSN + Istio 具体实现探索
  - MOSN 配置文件介绍、从一个流量进来到转发到具体的远端的流程分析
  - Provider 配置信息如何下发到 Sidecar
  - 从多点现在的实际场景对现有的 Dubbo 改造方案
- Demo 演示
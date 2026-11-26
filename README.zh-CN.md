[English](./README.md) · [简体中文](./README.zh-CN.md)

# 你好，我是 CoderBruis 👋

**资深后端工程师 · 全栈 · 分布式系统 · 中间件 · AI Agent**

我是一名以 Java 为主的资深后端工程师，具备全栈开发经验。我的核心方向是分布式系统和中间件，包括 Kafka、RocketMQ、Dubbo 和 Netty。我喜欢阅读源码，把问题追到具体实现，并向上游开源项目贡献小而精、带测试的修复。

在 AI 方向，我使用 Python、FastAPI、LangChain、LangGraph 和 AgentScope 构建 Agent 应用，并通过 Docker 和 Kubernetes 部署。

📫 联系方式：[luohaiyangvs@qq.com](mailto:luohaiyangvs@qq.com) / [tzylhy83@gmail.com](mailto:tzylhy83@gmail.com)

## 技术栈

<picture><source media="(prefers-color-scheme: dark)" srcset="./profile/tech-stack/java-dark.svg"><img src="./profile/tech-stack/java-light.svg" width="400" alt="JAVA &amp; SPRING: Java, Spring Boot, Spring Cloud"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="./profile/tech-stack/middleware-dark.svg"><img src="./profile/tech-stack/middleware-light.svg" width="400" alt="MIDDLEWARE &amp; NETWORKING: Kafka, RocketMQ, Dubbo, Netty"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="./profile/tech-stack/ai-dark.svg"><img src="./profile/tech-stack/ai-light.svg" width="400" alt="AI &amp; AGENTS: Python, FastAPI, LangChain, LangGraph, AgentScope"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="./profile/tech-stack/devops-dark.svg"><img src="./profile/tech-stack/devops-light.svg" width="400" alt="CLOUD &amp; DEVOPS: Docker, Kubernetes"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="./profile/tech-stack/web-dark.svg"><img src="./profile/tech-stack/web-light.svg" width="400" alt="WEB: Vue, JavaScript, TypeScript, Element Plus"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="./profile/tech-stack/data-dark.svg"><img src="./profile/tech-stack/data-light.svg" width="400" alt="DATA &amp; STORAGE: MySQL, Redis, Elasticsearch"></picture>

## 部分开源贡献

聚焦正确性、参数校验和资源生命周期的小而精的改进。

| 项目 | 贡献 | 主要改动 |
| :--- | :--- | :--- |
| **Apache Kafka** | [#22722](https://github.com/apache/kafka/pull/22722) | 修复 CreateTopics 分区数校验中的整数溢出，并补充回归测试 |
| **Netty** | [#17093](https://github.com/netty/netty/pull/17093) | 为内存分配器的 `maxOrder` 增加下限校验，拒绝负数，并补充回归测试 |
| **Netty** | [#12254](https://github.com/netty/netty/pull/12254) | 去除不必要的内层循环迭代 |
| **Apache RocketMQ** | [#6564](https://github.com/apache/rocketmq/pull/6564) | 移除 Producer 启动时冗余的 Topic 发布信息初始化 |
| **Apache RocketMQ** | [#4314](https://github.com/apache/rocketmq/pull/4314) | 移除首轮迭代就返回、实际无效的循环 |
| **AgentScope** | [#4015](https://github.com/agentscope-ai/agentscope/pull/4015) | 忽略已过期的挂起回复中断 |
| **AgentScope** | [#4039](https://github.com/agentscope-ai/agentscope/pull/4039) | 多模态 Embedding 某个批次失败后，等待并回收同时发出的其他批次 |

[查看全部已合并的 PR →](https://github.com/pulls?q=is%3Apr+is%3Amerged+author%3Acoderbruis+-user%3Acoderbruis)

## GitHub 统计

![GitHub 统计](./profile/stats.svg)

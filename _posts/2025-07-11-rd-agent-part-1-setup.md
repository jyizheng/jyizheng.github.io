---
title: "RD-Agent 学习 (一): 项目概览与环境设置"
date: "2025-07-11 09:00:00 +0800"
author: jyizheng
category: rd-agent-study
---

这是 `RD-Agent` 学习系列的第一篇。在这篇文章中，我们将首先对项目进行一个宏观的了解，然后按照官方文档的指引，完成本地开发环境的搭建和基础的健康检查。

## 项目目标

`RD-Agent` 的核心目标是自动化高价值、可重复的工业研发流程。它不仅仅是一个代码执行的 Copilot，更是一个能够主动提出想法、并通过与真实世界数据交互来验证和优化这些想法的自主代理 (Agent)。

## 环境搭建步骤

1.  **克隆仓库**
    ```bash
    git clone [https://github.com/microsoft/RD-Agent.git](https://github.com/microsoft/RD-Agent.git)
    cd RD-Agent
    ```

2.  **安装依赖**
    *(此处可以记录您在安装过程中遇到的具体步骤和可能的问题...)*

3.  **运行健康检查**
    根据文档，项目提供了一个健康检查脚本来验证 Docker 和端口占用情况。
    ```bash
    rdagent health_check
    ```

在下一篇文章中，我们将深入其核心架构。

---
[**返回系列目录**]({% post_url 2025-07-10-rd-agent-series-toc %}) | [**下一篇：核心架构：双循环的 R&D 框架**]({% post_url 2025-07-12-rd-agent-part-2-architecture %})


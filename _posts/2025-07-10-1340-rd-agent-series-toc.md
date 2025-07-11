---
title: "学习系列: 微软 RD-Agent 源码深度解析"
date: "2025-07-10 13:40:00 +0800"
author: jyizheng
category: rd-agent-study
---

微软的 `RD-Agent` 是一个旨在通过大语言模型（LLM）自动化工业研发（R&D）流程的开源框架。它通过“研究 (Research)”和“开发 (Development)”两个核心组件，实现了想法的提出、验证和迭代优化，尤其在数据驱动的场景下，如量化交易和医疗预测中展现了巨大潜力。

我计划用一个系列的文章来深入学习和分析这个项目的源码，理解其设计哲学和实现细节。

### 系列文章目录

* **第一部分:** [项目概览与环境设置]({% raw %}{% post_url 2025-07-10-1420-rd-agent-part-1-setup %}{% endraw %})
* **第二部分:** [核心架构：双循环的 R&D 框架]({% raw %}{% post_url 2025-07-10-1430-rd-agent-part-2-architecture %}{% endraw %})
* **第三部分:** [代码实现：Agent 如何自主学习与演进]({% raw %}{% post_url 2025-07-10-1450-rd-agent-part-3-core-logic %}{% endraw %})
* **第四部分:** [配置管理设计五大原则]({% raw %}{% post_url 2025-07-10-1544-rd-agent-part-4-config-principles %}{% endraw %})
* *(未来更多文章将在此处更新...)*


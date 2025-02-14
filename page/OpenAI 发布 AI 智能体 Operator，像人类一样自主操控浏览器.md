# OpenAI 发布 AI 智能体 Operator，像人类一样自主操控浏览器

OpenAI 近日推出了备受期待的 AI 智能体 Operator（操作员），它能够代理用户执行基于网页的操作，像人类一样点击、滚动和输入文字，完成诸如购买杂货、预订餐厅以及提交费用报告等任务。

![Operator 演示](https://bbtdd.com/img/4307770794.webp)

此前，微软、Salesforce 和 Workday 等商业软件公司也推出了各自的智能体。与此同时，谷歌和人工智能初创公司 Anthropic 近期也推出了类似的工具，但与 OpenAI 的 Operator 相比，Operator 通过其独特的 **CUA 系统** 进行复杂的思维链反思和步骤规划，大幅提高了任务的精度和复杂性。

## Operator 的核心优势

- **泛化能力**：Operator 无需针对具体任务进行精调，即可完成多种复杂任务。
- **复杂任务处理**：在用户测试中，它甚至能在 Arxiv 上进行论文分类搜索，阅读多篇论文并完成综述整理。
- **网页控制能力**：CUA 在网页控制和系统控制方面达到了 **SOTA**（当前最优水平），整体行动流畅。

## 当前使用范围

目前，Operator 以“研究预览”的形式向美国的 **ChatGPT Pro** 用户开放，订阅费用为每月 **200 美元**。OpenAI 计划逐步将其功能推广到 **ChatGPT Plus**、**Team** 和 **Enterprise** 用户。此外，Operator 很快将在其他国家推出，但在欧洲地区可能需要更长时间。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)

## CUA 模型的驱动

Operator 的核心是 OpenAI 的新模型 **CUA**（Computer-Using Agent，计算机使用智能体）。它融合了 **GPT-4o** 的视觉能力与通过强化学习实现的高级推理能力，能够像人类一样与图形用户界面（GUI）交互，包括按钮、菜单和文本框。

### CUA 的工作原理

1. **感知**：CUA 通过处理屏幕截图理解计算机的当前状态。
2. **推理**：通过思维链推导下一步操作，动态调整任务执行策略。
3. **行动**：执行点击、滚动或输入等操作，直至任务完成或需要用户干预。

## CUA 的基准测试表现

CUA 在多个基准测试中取得了显著成果：
- **OSWorld**：完整计算机使用任务成功率为 **38.1%**。
- **WebArena**：网页任务成功率为 **58.1%**。
- **WebVoyager**：网页任务成功率为 **87%**。

## 局限性与风险

尽管 Operator 潜力巨大，但其易用性仍面临挑战。例如，苹果的 **Apple Intelligence** 仍未广泛应用于日常事务。大多数企业 AI 智能体也仅处于测试阶段，以避免暴露公司机密数据或引发网络安全风险。

### 风险应对措施

- **接管模式**：要求用户手动输入支付详情或登录信息。
- **高风险任务确认**：在执行发送邮件等任务前征求用户批准。
- **数据隔离**：Operator 不会使用用户与 ChatGPT 共享的数据。

OpenAI 强调，Operator 已具备有限发布的条件，但在隐私、安全和控制方面仍需进一步优化。
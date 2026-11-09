# 黄胜泽 · Shengze Huang

让智能体学会把事做成，也把它怎样学会的讲清楚。

**[阅读我的研究与实践 →](https://huangshengzebluesky.github.io/)** · [论文研究](https://huangshengzebluesky.github.io/research.html) · [项目实践](https://huangshengzebluesky.github.io/projects.html) · [技术笔记](https://huangshengzebluesky.github.io/writing.html)

我关注智能体的训练、运行机制与评测，也做一些帮助学习、研究和专注工作的产品。这里从具体问题进入方法，记录做过什么、结果说明什么，以及过程中形成的思考。

## 论文背后的问题

- **[AutoHarness](https://huangshengzebluesky.github.io/research/harness.html)**：模型不换，怎样通过提示、状态、工具控制和插件协同，让它更会做事？AAAI 2027 Workshop 在投；延伸研究准备 ICML 2027。
- **[RewardWeaver](https://huangshengzebluesky.github.io/research/reward.html)**：一次交互失败后，模型最该练什么？从当前瓶颈选择过程奖励。研究参与，[公开预印本](https://arxiv.org/abs/2610.10120)。
- **[BehaviorWeaver](https://huangshengzebluesky.github.io/research/behavior.html)**：同一个动作在不同情境里应该怎样评价？研究状态与行为维度的反馈构造。共同作者，ICML 2027 写稿与投稿准备中。
- **[RoboWM-Bench](https://huangshengzebluesky.github.io/research/robo.html)**：视频里做成了，机器人就真的能做成吗？通过动作恢复与执行检验世界模型。共同作者，CVPR 2026 WMAS Workshop 最佳论文。

## 从想法走到能运行的工作

- **[商业模拟世界与训练数据](https://huangshengzebluesky.github.io/projects/world.html)**：把业务需求转成可以交互、重置和评价的环境，再把失败反馈接到 [AutoSFT](https://huangshengzebluesky.github.io/projects/sft.html)。
- **[多智能体评测](https://huangshengzebluesky.github.io/projects/multiagent.html)**：为 MPE 与 Google Football 建立自然语言接口，比较模型在通信、协作与战术决策中的表现。
- **[MLP AutoResearch](https://huangshengzebluesky.github.io/projects/mlp.html)**：2026 年 3 月早期跟进 AutoResearch，在一个熟悉的小模型上实践修改、训练、评价和版本选择。
- **[教育飞轮](https://huangshengzebluesky.github.io/projects/edu.html)**：从高质量知识凝练命题与审校技能，让作答和反馈同时改进题库与方法。
- **[回声](https://huangshengzebluesky.github.io/projects/echo.html)**：以本人原始输入为复盘入口，围绕当前主题关联项目和会话。
- **[飞跃会](https://huangshengzebluesky.github.io/projects/fly.html)**：把文档讨论组织成有阶段、有产物、可审阅的研究流程。

## 研究过程也值得读

[为什么换题后效果变差？](https://huangshengzebluesky.github.io/writing/earth-agent-generalization.html) · [失败一定属于模型吗？](https://huangshengzebluesky.github.io/writing/benchmark-audit.html) · [MCP、Tool、Skill、CLI 怎样分工？](https://huangshengzebluesky.github.io/writing/agent-tools-explained.html)

代码和论文是文章的延伸。希望读者先看到问题、方法与判断，再决定往哪一层深入。

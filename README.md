# LingBot-VLA 2.0 入门与复现笔记

面向会写 Python、能读懂 PyTorch 训练循环、第一次接触 VLA 的读者。目标是跟通一条机器人示范轨迹，理解动作模型如何训练与评测，再完成一项可以交给队友复核的工作。

| 顺序 | 阅读入口 | 动手产物 |
| --- | --- | --- |
| 1 | [VLA 基础讲义](FUNDAMENTALS.md) | 标出一条轨迹的观察、状态和动作 |
| 2 | [CPU 小实验](CPU_LAB.md) | 对比正确对齐与错位一帧的动作标签 |
| 3 | [训练诊断实验](EXPERIMENTS.md) | 比较不同轨迹和偏移量下的留出误差 |
| 4 | [比赛工作流](COMPETITION_WORKFLOW.md) | 交付一份数据抽查或失败回放记录 |
| 5 | [单卡训练复盘](CASE_STUDY.md) | 为下一次保存与恢复拟一份检查清单 |

从[在线实验](https://lillyli-netizen.github.io/Me-designed-page/training-labs/#alignment)切换两类轨迹，再回到 [CPU 小实验](CPU_LAB.md)读代码。准备使用真实数据时，先在一条允许使用的 episode 中核对时间、左右臂与夹爪通道。

[LingBot-VLA 2.0 上游](https://github.com/Robbyant/lingbot-vla-v2) · [技术报告](https://arxiv.org/abs/2607.06403) · [RoboTwin 2.0](https://robotwin-platform.github.io/) · [天池赛题](https://tianchi.aliyun.com/competition/entrance/532514/introduction)

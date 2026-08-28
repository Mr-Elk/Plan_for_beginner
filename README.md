# AI 应用开发学习计划

这是一套面向编程新手的全日制训练方案。学习者 22 岁，遥感专业毕业，能借助翻译阅读英文资料；当前按“看过代码，但基本不能独立写”处理。目标是转向后端优先的 AI 应用开发，并最终获得就业与独立交付能力。

计划以 48 周为参考、能力证据为晋级依据。每周投入 40 个有效小时，每两周交付一个能运行的项目增量。时间不够时缩小范围，不降低验收标准。

当前基线：v0.14。项目尚未开训，下一步见 [STATUS.md](STATUS.md)。

## 从哪里开始

- 学习者：先看[阶段学习地图](stages/README.md)，目前只读 [P0 阶段指南](stages/P0/README.md)。
- 负责人：先看[项目状态](STATUS.md)，再依据当前阶段的 `stage-control.md` 审阅阶段合同并生成课程包。
- 课程设计 AI：遵守 [AGENTS.md](AGENTS.md)，不要提前生成全年周任务。

## 文件各管什么

| 文件 | 只回答的问题 |
|---|---|
| [项目章程](docs/00-project-charter.md) | 为什么做、受什么限制、怎样算成功？ |
| [路线图](docs/01-roadmap.md) | 八个阶段分别解决什么问题？ |
| [能力矩阵](docs/02-capability-matrix.md) | 达到什么水平才能晋级？ |
| [执行节奏](docs/03-loop-protocol.md) | 每天、每周、每两周怎样推进？ |
| [AI 使用规则](docs/04-ai-use-policy.md) | 什么情况下可以让 AI 帮到哪一步？ |
| [治理与变更](docs/05-governance.md) | 谁能改什么，什么时候需要改总体规划？ |
| [学习架构](docs/06-learning-architecture.md) | 知识、项目和能力怎样相互支撑？ |
| [质量与证据](docs/07-quality-and-evidence.md) | 什么产出才算有效证据？ |
| [风险与恢复](docs/08-risk-and-recovery.md) | 计划偏离后怎样恢复？ |
| [课程范围](docs/10-curriculum-scope.md) | 哪些必学、学到多深、哪些暂不学？ |
| [并行执行](docs/11-parallel-execution.md) | 哪些内容可以同时做，WIP 如何限制？ |
| [规划原则](docs/12-planning-style.md) | 课程包按什么原则设计？ |
| [单次学习流程](docs/13-efficient-learning-process.md) | 一个知识点或任务具体怎样学？ |
| [项目控制](docs/14-program-control.md) | 当前处于什么状态，证据怎样追溯？ |
| [中文写作规范](docs/15-chinese-technical-writing.md) | 文档怎样写得详细、简练、准确？ |

历史治理记录在 [docs/09-governance-loop-log.md](docs/09-governance-loop-log.md)，只追加，不作为执行入口。

## 固定边界

- 主环境：Windows + WSL2；云端 Linux 用于部署。
- 主语言：Python；React 只学到能完成产品界面。
- 第一轮不以遥感为主线。
- 不系统学习大模型训练、竞赛算法、Kubernetes 和多套同类框架。
- 每日保留 Git 记录；每周安排独立检查；每两周演示一个纵向切片。
- AI 可以讲解、追问、审查和提供分级提示，不能替学习者完成独立证据。

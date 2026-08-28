# AI 应用开发学习计划

这是一个面向编程零基础学习者的全日制训练项目。目标是在约 48 周内，以一个持续交付现场螺旋建立 Python 后端、计算机基础、数据与机器学习、LLM 应用工程以及独立交付能力，并从第 36 周开始用真实求职反馈校准训练方向。

本仓库首先治理“学什么、如何验收、如何调整”，再按两周滚动生成课程包。日历只提供节奏，能力证据决定是否晋级。

## 当前状态

- 生命周期：总体规划治理
- 规划版本：v0.11
- 当前阶段：尚未开始训练
- 下一里程碑：审阅 v0.11 阶段任务基线，依据P0任务清单创建阶段合同与第 1–2 周诊断课程包并通过S0开训门
- 状态详情：[STATUS.md](STATUS.md)
- 版本变更：[CHANGELOG.md](CHANGELOG.md)
- Agent工作规则：[AGENTS.md](AGENTS.md)

## 单一事实源

发生冲突时，按以下优先级解释：

1. [项目章程](docs/00-project-charter.md)：目标、范围、约束和成功定义
2. [规划风格与学习原则](docs/12-planning-style.md)：实践、理论、记录和迭代的总纲
3. [治理与变更控制](docs/05-governance.md)：角色、决策权、版本和变更流程
4. [项目控制与证据追溯](docs/14-program-control.md)：运行状态、开训门、指标口径和证据索引
5. [学习架构](docs/06-learning-architecture.md)：知识依赖、迁移和项目层级
6. [高效学习步骤](docs/13-efficient-learning-process.md)：预试、精准输入、独立重建、迁移和复测
7. [课程范围地图](docs/10-curriculum-scope.md)：独立于时间的必修、增强和排除边界
8. [能力矩阵](docs/02-capability-matrix.md)：晋级要求和证据
9. [质量与证据标准](docs/07-quality-and-evidence.md)：开始、完成、考核和证据有效性
10. [48 周路线图](docs/01-roadmap.md)：建议节奏和阶段产出
11. [LOOP 执行协议](docs/03-loop-protocol.md)：日、周、周期执行方法
12. [AI 使用与考核规则](docs/04-ai-use-policy.md)：AI 辅助边界
13. [风险与恢复机制](docs/08-risk-and-recovery.md)：偏离后的最小恢复方案
14. [受控并行执行模型](docs/11-parallel-execution.md)：1＋2并行、依赖、WIP和角色流水线
15. 课程包与临时任务：服务于上述文件，不得反向修改项目目标

## 工作方式

```text
总体规划
  → P0–P7 阶段任务积压
  → 当前阶段合同
  → 每两周一个纵向切片课程包
  → P0 开训前通过 S0 正式开训门
  → 日/周 LOOP 执行
  → 自动测试 + 无 AI 考核 + 累计面试提取
  → 证据索引 + 周期复盘
  → 调整下一课程包
```

全年阶段任务见 [阶段任务目录](stages/README.md)，进入当前阶段时使用 [阶段合同模板](templates/stage-contract.md)筛选和批准任务，两周执行使用 [课程包模板](templates/course-package.md)。复杂主题使用 [单次学习块模板](templates/learning-session.md)，每日使用 [每日日志模板](templates/daily-log.md)，理论缺口进入 [理论回顾账本](templates/theory-review-ledger.md)，重要证据进入 [能力证据索引](templates/evidence-index.md)，每周使用 [周复盘模板](templates/weekly-review.md)。对总体规划的修改使用 [变更申请模板](templates/change-request.md)。

本轮总体治理过程和停止依据见 [治理LOOP记录](docs/09-governance-loop-log.md)。

## 核心约束

- 计划强度：每周 40 个有效小时，六天半节奏
- 主环境：Windows + WSL2；云端 Linux 用于部署
- 主方向：后端优先的 AI 应用工程
- 主语言：Python；JavaScript/React 只学到足以交付产品
- 不以遥感作为第一年主线
- 不以训练基础大模型、竞赛算法、Kubernetes 或多框架堆叠为目标
- 每日 Git 记录、每周无 AI 考核、每两周纵向切片演示
- 第 36 周开始试投递，第 48 周完成第一轮训练

## 官方资料入口

- [Python 教程](https://docs.python.org/3/tutorial/)
- [uv 项目管理](https://docs.astral.sh/uv/concepts/projects/init/)
- [FastAPI 教程](https://fastapi.tiangolo.com/tutorial/)
- [PostgreSQL 教程](https://www.postgresql.org/docs/current/tutorial.html)
- [React 学习文档](https://react.dev/learn)
- [Docker 入门](https://docs.docker.com/get-started/)
- [PyTorch 基础](https://docs.pytorch.org/tutorials/beginner/basics/intro)
- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)

# China Agentic Observatory

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22791309.svg)](https://doi.org/10.5281/zenodo.22791309)

### 中国人工智能与智能体前沿观察站

> **One repository · One day · One integrated research report**  
> **一仓 · 一日 · 一份完整研究报告**

A bilingual, source-grounded observatory for China's artificial-intelligence and agentic-system landscape across history, policy, standards, research, open source, infrastructure, industry, applications, evaluation, and governance.

本仓库是研究观察站，不是产品测试平台、能力认证机构、政策合规认证机构或全国部署状态数据库。

## Stable Research Entry Points / 长期研究入口

- [Methodology / 方法论](./METHODOLOGY.md) — 中国语境下的信源等级、状态分类、时间纪律与证据独立性。
- [Scope / 范围](./SCOPE.md) — 研究覆盖与排除项。
- [Taxonomy / 分类体系](./TAXONOMY.md) — policy / standards / infrastructure / industry / agentic systems 的长期比较词汇。
- [Source Registry / 权威信源注册表](./SOURCE_REGISTRY.md) — 规范来源身份与受证据边界约束的状态注记。
- [Active Watchlist / 活跃观察清单](./watchlist/ACTIVE.md) — 当前研究压力、待确认状态与优先问题。
- [Workstreams / 研究分工](./workstreams/README.md) — C1–C8 分析工作流。
- [Origin / 起源](./ORIGIN.md) — 仓库起源与研究意图。
- [Ten-repository context / 十仓上下文](./TEN_REPOSITORY_CONTEXT.md) — 与更大公开研究系统的关系。

时间序列研究产物继续保留在各自 canonical surfaces：

- [Daily reports / 日报](./reports/daily/)
- [Weekly research / 周报](./reports/weekly/)
- [Monthly research / 月报](./reports/monthly/)

## Web Presentation / 展示层

本仓的只读、Pages-ready research console 位于 [`docs/`](./docs/)。它从 current `main` 投影最新 Daily、canonical Weekly/Monthly 状态、C1–C8 handoff、Watchlist、Source Registry 与有边界的 Twin Observatory lens。

展示层**不拥有研究状态**，也不创建第二套 evidence database。canonical source 缺失时显示 unavailable，不反推 lifecycle 或 maturity。详见 [`docs/README.md`](./docs/README.md)。

首页不再硬编码“当前月份”“当前周”或最新结论。当前研究状态由 report indexes、Source Registry 与 Watchlist 自己拥有，从而让 README 保持长期稳定。

## Evidence Model / 证据模型

每项实质性陈述应能够归入：

- `OFFICIAL_FACT` — 官方政策、标准、注册信息或正式发布文件；
- `PROJECT_FACT` — 可核验的项目、仓库、版本、文档或论文状态；
- `EXTERNAL_CLAIM` — 企业、机构、作者或项目自身声明；
- `OBSERVATORY_ANALYSIS` — 本观察站的综合与推断；
- `UNCERTAIN` — 证据不足、过期、模糊或冲突。

来源等级高不等于可以跳过日期、状态、范围与成熟度校准。

```text
政策目标 != 已完成能力
标准计划 != 已发布标准
批准展示 != 已知批准时间
发布 != 实施
案例实施 != 全国普遍采用
项目存在 != 能力有效
benchmark claim != benchmark reproduced
观察日 != 状态变化日
```

## China-specific Status Discipline / 中国状态纪律

政策、标准和项目生命周期必须按真实证据区分，而不是按叙事方便合并。

Standards/policy examples:

`PLANNED · PUBLIC_NOTICE · DRAFTING · CONSULTATION · REVIEW · APPROVED · PUBLISHED · IN_FORCE · SUPERSEDED · WITHDRAWN`

Project examples:

`ANNOUNCED · PREVIEW · OPEN_SOURCED · RELEASED · MAINTAINED · RESTRUCTURED · DEPRECATED · ARCHIVED · UNCLEAR`

一个 2026 年的 current-state recheck 只能证明检查当时可观察到的状态；除非存在直接时间证据，否则不能反推出精确 transition timestamp。

## Publication and Citation / 出版与引用

上方 DOI 标识本观察站的一个已归档 software publication，并提供稳定引用入口。

**本仓库自己的 DOI 不是 C0–C6 外部信源，也不是关于中国政策、标准、企业、项目或产业状态的独立证据。**

```text
repository publication identity != China-world evidence
repository DOI != independent corroboration
self-citation != new external evidence
archived publication != later current main
```

引用具体政策、标准、企业项目或状态判断时，应继续引用支持该判断的外部来源与对应 observation/date boundary，而不是用仓库 DOI 替代。

## Research Production and Repository Governance

Daily / Weekly / Monthly SOP 定义时间序列研究产物的生产方式；它们与这里描述的长期 Methodology、Scope、Taxonomy 和 repository identity 分离。

贡献、维护与外部审查材料属于仓库治理/基础设施表面，仅因存放在同一仓库中不会自动进入研究证据链。

## Twin Observatory / 双仓联动

[Agentic Frontier Observatory](https://github.com/lostlight530/agentic-frontier-observatory) tracks the wider global agentic frontier.

双仓的结构可用于对比，但：

```text
structural comparability != formal interoperability
similar terminology != equivalent institutional status
same technology family != inherited maturity
```

## Origin / 起源

**Founded on 7 August 2026 / 成立于 2026 年 8 月 7 日**

> **前八仓构建自己的世界，第九、十仓每天重新观察外部世界**

## License

MIT License

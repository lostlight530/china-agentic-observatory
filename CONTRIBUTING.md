# Contributing / 贡献指南

China Agentic Observatory welcomes contributions that improve factual accuracy, source quality, temporal/status calibration, taxonomy, methodology, durable research assets, repository documentation, or public metadata.

## 中文

### 贡献对象

优先修改真正拥有该问题的长期表面：

- `METHODOLOGY.md` — 中国语境下的信源、状态、时间与证据纪律；
- `SCOPE.md` — 研究范围与排除项；
- `TAXONOMY.md` — policy / standards / infrastructure / industry / agentic systems 的比较词汇；
- `SOURCE_REGISTRY.md` — 规范信源身份；
- `watchlist/`、`workstreams/` — 当前研究压力与 C1–C8 分析结构；
- 根 README、引用/发布元数据、`.github/`、安全与贡献文档 — 仓库公共基础设施；
- 时间序列 research outputs — 仅在明确纠错任务确实拥有对应记录时修改。

### 来源、状态与时间

贡献应当：

- 优先使用政府、标准组织、官方项目/企业资料与原始研究；
- 区分 `event_date`、`publication_date`、`effective_date`、`observed_at` 与已知 `state_transition_date`；
- 区分 `OFFICIAL_FACT`、`PROJECT_FACT`、`EXTERNAL_CLAIM`、`OBSERVATORY_ANALYSIS`、`UNCERTAIN`；
- 明确标准/政策状态和项目状态，不用相似措辞替代正式生命周期；
- 不把政策目标、标准计划、起草、审查、批准展示、企业宣传、单一案例自动提升为已实施能力或全国成熟度；
- 不把同一上游文件的重复转载计为独立证据。

本仓自己的 DOI、README、历史报告或软件归档不能替代中国外部世界的 C0–C6 信源。

```text
repository DOI != official/project evidence
self-citation != independent corroboration
observation date != transition date
approval display != exact approval time
case implementation != nationwide adoption
```

### 历史与纠错

历史 Daily / Weekly / Monthly 和其他 point-in-time 记录保留原始观察边界。后续发现错误时更新当前解释并明确 correction，不把后来获得的来源或精确日期倒写进更早记录。

周期 SOP 定义研究生产方式；普通贡献不需要围绕调度器、维护 Agent 或外部审计控制逻辑组织。

### Pull Request

使用仓库 PR 模板，并说明具体问题、有限改动、受影响长期表面、来源与日期/版本/状态依据、实际完成的核验、仍不确定事项、历史影响、安全/隐私影响与回滚方式。

## English

### Choose the owning surface

Prefer the durable surface that actually owns the issue:

- `METHODOLOGY.md` for China-specific source/status/date discipline;
- `SCOPE.md` for coverage and exclusions;
- `TAXONOMY.md` for policy/standards/infrastructure/industry/agentic comparison vocabulary;
- `SOURCE_REGISTRY.md` for canonical source identities;
- `watchlist/` and `workstreams/` for active research pressure and C1–C8 analytical organization;
- root documentation, citation/release metadata, `.github/`, security, and contribution files for repository infrastructure;
- time-ordered research outputs only when a specific correction genuinely owns that record.

### Source, status, and date discipline

Contributions should prefer official/primary/original sources, preserve formal lifecycle status, separate event/publication/effective/observation/transition dates, and keep official/project facts distinct from external claims, observatory analysis, and uncertainty.

Do not promote policy targets, standards plans, drafting/review/approval displays, marketing claims, or isolated cases into implemented capability or nationwide maturity without evidence.

The repository's own DOI, README, prior reports, or archive are not C0–C6 external evidence.

### Historical correction

Preserve point-in-time research boundaries. Correct current interpretation forward and never make a later source or transition timestamp appear available to an earlier observation.

Cadence SOPs define research production; ordinary contributions do not need to reproduce scheduler, maintenance-agent, or external-audit control logic.

### Pull requests

Use the repository pull-request template and include the bounded change, affected durable surfaces, source/date/status evidence, verification actually performed, unresolved items, historical impact, security/privacy impact, and rollback.

## Security, privacy, license, and attribution

Do not submit credentials, private information, full paywalled text, or non-public evidence. Follow `SECURITY.md` for sensitive reports.

Contributions to repository-owned work are submitted under the current license. External sources retain their original authorship and licensing, and Git/PR history remains the source of contribution attribution.

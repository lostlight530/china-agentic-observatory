# Methodology / 方法论

## 0. Observatory pipeline / 观察站方法链

```text
公开世界
↓
权威信源检索
↓
事实存在性验证
↓
C1–C8 独立 Workstreams
↓
证据分级 / 状态与时间校准
↓
一日一份 Integrated Report
↓
同一 canonical weekly 持续累积
↓
假设 strengthened / open / refuted / durable
↓
月度长期结算
↓
Source Registry + Watchlist
```

Core rule:

> **不验证技术是否真的有效，但必须验证信息是否真的存在。**

This repository is a research observatory, not a benchmark, deployment platform, product test bed, or execution Agent.

## 1. Source hierarchy / 信源等级

| Level | Source | Use |
|---|---|---|
| C0 | State Council, CAC, NDRC, MIIT, SAMR, MOST and formal laws or policies | Canonical policy and legal status |
| C1 | National standards bodies, TC260, TC609, CESI, CAICT | Standards, security guidance, methods, formal work status |
| C2 | Official industry alliances and standards organizations | Technical specifications and ecosystem coordination |
| C3 | Official company repositories, documentation, releases, and papers | Product, project, and architecture claims |
| C4 | Universities, laboratories, peer-reviewed or original research | Scientific evidence and methods |
| C5 | Named technical leaders and official engineering blogs | Declared direction and implementation context |
| C6 | Media, communities, conferences, and social platforms | Discovery leads only |

A higher source grade does not remove the need to calibrate dates, status, scope or claim meaning.

## 2. Statement classes / 陈述分类

- `OFFICIAL_FACT` — official policy, standard, registry, or published document
- `PROJECT_FACT` — verifiable repository, release, documentation, or paper state
- `EXTERNAL_CLAIM` — a company, institution, or author claim
- `OBSERVATORY_ANALYSIS` — this repository's synthesis
- `UNCERTAIN` — evidence insufficient or conflicting

Every material conclusion should be traceable to one or more of these classes.

## 3. Existence verification / 存在性验证

Before analysis, verify:

```text
source exists
→ issuer exists
→ exact document / project exists
→ date is calibrated
→ current status is calibrated
→ quoted meaning is represented accurately
→ claim scope is bounded
```

Existence verification is not performance validation.

```text
document exists ≠ requirement implemented
project exists ≠ capability works
case exists ≠ nationwide implementation
benchmark claim exists ≠ benchmark reproduced
```

## 4. Status discipline / 状态纪律

For standards and policy, distinguish:

`PLANNED`, `PUBLIC_NOTICE`, `DRAFTING`, `CONSULTATION`, `REVIEW`, `APPROVED`, `PUBLISHED`, `IN_FORCE`, `SUPERSEDED`, `WITHDRAWN`

For projects, distinguish:

`ANNOUNCED`, `PREVIEW`, `OPEN_SOURCED`, `RELEASED`, `MAINTAINED`, `RESTRUCTURED`, `DEPRECATED`, `ARCHIVED`, `UNCLEAR`

China-specific mandatory boundaries:

```text
政策目标 ≠ 已完成能力
课题征集 ≠ 研究成果
标准计划 ≠ 已发布标准
起草 ≠ 审查 ≠ 批准 ≠ 发布
技术文件 ≠ GB/T 国家标准
相近标准 ≠ 正式 crosswalk
案例实施 ≠ 全国互操作体系
数据飞轮 ≠ 自动闭环
评测结果 ≠ 自动修改数据集
新版本 ≠ 自动进入训练
```

## 5. Date discipline / 日期纪律

Always distinguish:

- `event_date`
- `publication_date`
- `effective_date` when applicable
- `observed_at`
- `state_transition_date` when actually known

A current-state recheck must never be rewritten as a same-day state transition.

> **Observation date ≠ state-transition date / 观察日 ≠ 状态变化日**

## 6. Evidence independence / 证据独立性

Repeated pages, mirrored announcements, derivative news, and multiple statements ultimately sourced from the same original document do not count as independent strengthening.

Evidence is strengthened by genuinely independent sources, layers, implementations or status transitions—not by citation count.

## 7. Daily → Weekly → Monthly memory / 日周月记忆链

Daily reports record atomic observation and delta.

Weekly reports maintain falsifiable hypotheses across one ISO week and settle them only after the final real observation day.

Monthly reports compress already-existing daily/weekly history into longer-lived judgment and carry-forward.

```text
Daily = atomic evidence + delta
Weekly = hypothesis memory + correction
Monthly = long-horizon settlement + carry-forward
```

> **周日不是清空，周一不是重启。**

Durable conclusions become baseline doctrine. Open gaps continue; they are not rediscovered as new merely because a new week or month begins.

## 8. Correction and historical-record discipline / 修正与历史纪律

- factual or status errors must be corrected explicitly
- old wording is not silently erased from the research narrative
- purely stylistic modernization is not a reason to rewrite atomic historical reports
- legacy non-canonical snapshots may remain for audit, but must point to the canonical record that supersedes them
- later evidence must not be backdated into an earlier observation day

## 9. Non-validation boundary / 非验证边界

The repository checks whether a public source exists, what it says, who issued it, and what status it carries.

It does **not** independently run models, reproduce benchmarks, deploy projects, certify compliance, or validate advertised capability.

Search, reading, cross-checking, status calibration and structured synthesis are in scope.

## 10. Comparison discipline / 比较纪律

China-global comparison must specify the exact layer being compared: policy, governance, identity, discovery, messaging, tool access, runtime, evaluation, security, data lifecycle, industry adoption or standards maturity.

Similar vocabulary does not prove equivalent architecture.

> **Structural comparability ≠ formal interoperability.**

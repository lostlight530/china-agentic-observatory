> [!NOTE]
> **Current architecture interpretation — 2026-09-18**
> - **Subject class:** `METHOD`
> - **Role:** Durable China-observatory method for source hierarchy, lifecycle/status/date calibration, evidence independence, correction and same-layer comparison
> - **Authority:** Current methodology authority for China-specific non-periodic research semantics
> - **Current meaning:** Use this file to determine how official/project evidence becomes a bounded statement while preserving issuer authority, formal lifecycle, geography, implementation maturity and uncertainty
> - **Evidence boundary:** Higher official source grade does not prove implementation completeness or national maturity; current-state observation is not transition date; policy target is not capability; technical document is not automatically GB/T; aggregation is not independent corroboration
> - **Cross-document relation:** Taxonomy supplies local vocabulary; Source Registry supplies admitted identities/current-state notes; workstreams apply the method; periodic SOPs govern cadence without redefining evidence semantics
> - **Update trigger:** Update when evidence hierarchy, lifecycle/date/status method, correction discipline or comparison method materially changes
> - **Preservation rule:** The existing subject remains the owning repository document. Historical policy/standard/project observations retain their original date and status boundary; later evidence changes current interpretation without backdating transitions

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
时间序列综合研究产物
↓
假设修正 / 结算
↓
长期综合
↓
Source Registry + Watchlist
```

Core rule:

> **不验证技术是否真的有效，但必须验证信息是否真的存在。**

This repository is a research observatory, not a benchmark, deployment platform, product test bed, compliance-certification service, or execution Agent.

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

A higher source grade does not remove the need to calibrate dates, status, scope, or claim meaning.

Source grade is claim-specific. A government or company page may be authoritative for what that issuer announced while remaining insufficient evidence for implementation completeness, independent performance, nationwide adoption, or cross-ecosystem maturity.

## 2. Statement classes / 陈述分类

- `OFFICIAL_FACT` — official policy, standard, registry, or published document;
- `PROJECT_FACT` — verifiable repository, release, documentation, or paper state;
- `EXTERNAL_CLAIM` — a company, institution, or author claim;
- `OBSERVATORY_ANALYSIS` — this repository's synthesis;
- `UNCERTAIN` — evidence insufficient, stale, ambiguous, or conflicting.

Every material conclusion should be traceable to one or more of these classes.

Attributed statements do not become repository facts merely because they are repeated by multiple derivative sources.

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

Existence verification is not performance or implementation validation.

```text
document exists != requirement implemented
project exists != capability works
case exists != nationwide implementation
benchmark claim exists != benchmark reproduced
```

## 4. Status discipline / 状态纪律

For standards and policy, distinguish:

`PLANNED`, `PUBLIC_NOTICE`, `DRAFTING`, `CONSULTATION`, `REVIEW`, `APPROVED`, `PUBLISHED`, `IN_FORCE`, `SUPERSEDED`, `WITHDRAWN`

For projects, distinguish:

`ANNOUNCED`, `PREVIEW`, `OPEN_SOURCED`, `RELEASED`, `MAINTAINED`, `RESTRUCTURED`, `DEPRECATED`, `ARCHIVED`, `UNCLEAR`

China-specific mandatory boundaries:

```text
政策目标 != 已完成能力
课题征集 != 研究成果
标准计划 != 已发布标准
起草 != 审查 != 批准 != 发布 != 实施
技术文件 != GB/T 国家标准
相近标准 != 正式 crosswalk
案例实施 != 全国互操作体系
数据飞轮 != 自动闭环
评测结果 != 自动修改数据集
新版本 != 自动进入训练
批准展示 != 已知批准时间
```

## 5. Date discipline / 日期纪律

Always distinguish:

- `event_date`;
- `publication_date`;
- `effective_date` when applicable;
- `observed_at`;
- `state_transition_date` when actually known.

A current-state recheck must never be rewritten as a same-day state transition.

> **Observation date != state-transition date / 观察日 ≠ 状态变化日**

If a document is observed in an `APPROVED` or `PUBLISHED` state but the exact transition timestamp is not directly evidenced, preserve the state while keeping the transition time unknown.

## 6. Evidence independence / 证据独立性

Repeated pages, mirrored announcements, derivative news, model summaries, search snippets, and multiple statements ultimately sourced from the same original document do not count as independent strengthening.

Evidence is strengthened by genuinely independent sources, institutional layers, implementations, research, or real status transitions—not by citation count.

## 7. Repository publication is not China-world evidence / 仓库出版物不是中国外部事实证据

The observatory has a Zenodo software publication. That DOI identifies this repository as a citable software/research object; it is not a C0–C6 source about Chinese policy, standards, projects, companies, infrastructure, or industry state.

```text
repository DOI != official fact
repository DOI != project fact about an external project
repository DOI != independent corroboration
repository archive != current-main research state
```

A repository-level citation may identify the observatory software or archived research object. A statement about an external policy, standard, project, company, or ecosystem still requires the external evidence chain that supports that statement.

Internal reports may be cited for the observatory's own earlier analysis or observation history, but self-citation does not create source independence.

## 8. Research-memory chain / 研究记忆链

```text
Daily = atomic evidence + delta
Weekly = hypothesis memory + correction
Monthly = long-horizon settlement + carry-forward
```

> **周日不是清空，周一不是重启。**

Durable conclusions become baseline only after surviving the applicable evidence and correction process. Open gaps continue across week/month boundaries rather than being rediscovered as new.

Aggregation does not create independent external evidence by itself.

## 9. Correction and historical-record discipline / 修正与历史纪律

- factual or status errors must be corrected explicitly;
- old wording is not silently erased from the research narrative;
- purely stylistic modernization is not a reason to rewrite atomic historical reports;
- later evidence must not be backdated into an earlier observation day;
- contradictions remain visible until resolved;
- later confirmation must not manufacture an exact earlier transition timestamp.

## 10. Non-validation boundary / 非验证边界

The repository checks whether a public source exists, what it says, who issued it, and what status it carries.

It does **not** independently run models, reproduce benchmarks, deploy projects, certify compliance, or validate advertised capability.

Search, reading, cross-checking, status calibration, and structured synthesis are in scope.

## 11. Comparison discipline / 比较纪律

China-global comparison must specify the exact layer being compared: policy, governance, identity, discovery, messaging, tool access, runtime, evaluation, security, data lifecycle, industry adoption, or standards maturity.

Similar vocabulary does not prove equivalent architecture, legal status, maturity, or adoption.

> **Structural comparability != formal interoperability.**

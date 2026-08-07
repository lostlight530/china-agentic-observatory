# Methodology / 方法论

## 1. Source hierarchy / 信源等级

| Level | Source | Use |
|---|---|---|
| C0 | State Council, CAC, NDRC, MIIT, SAMR, MOST and formal laws or policies | Canonical policy and legal status |
| C1 | National standards bodies, TC260, CESI, CAICT | Standards, security guidance, methods, industry research |
| C2 | Official industry alliances and standards organizations | Technical specifications and ecosystem coordination |
| C3 | Official company repositories, documentation, releases, and papers | Product, project, and architecture claims |
| C4 | Universities, laboratories, peer-reviewed or original research | Scientific evidence and methods |
| C5 | Named technical leaders and official engineering blogs | Declared direction and implementation context |
| C6 | Media, communities, conferences, and social platforms | Discovery leads only |

## 2. Statement classes / 陈述分类

- `OFFICIAL_FACT` — official policy, standard, registry, or published document
- `PROJECT_FACT` — verifiable repository, release, documentation, or paper state
- `EXTERNAL_CLAIM` — a company, institution, or author claim
- `OBSERVATORY_ANALYSIS` — this repository's synthesis
- `UNCERTAIN` — evidence insufficient or conflicting

## 3. Status discipline / 状态纪律

For standards and policy, distinguish:

`PLANNED`, `PUBLIC_NOTICE`, `DRAFTING`, `CONSULTATION`, `REVIEW`, `APPROVED`, `PUBLISHED`, `IN_FORCE`, `SUPERSEDED`, `WITHDRAWN`

For projects, distinguish:

`ANNOUNCED`, `PREVIEW`, `OPEN_SOURCED`, `RELEASED`, `MAINTAINED`, `RESTRUCTURED`, `DEPRECATED`, `ARCHIVED`, `UNCLEAR`

## 4. Date discipline / 日期纪律

Always record event date, publication date, effective date when applicable, and repository observation date.

## 5. Non-validation boundary / 非验证边界

The repository checks whether a public source exists, what it says, who issued it, and what status it carries. It does not independently run models, verify benchmark claims, deploy projects, or certify compliance.

## 6. Comparison discipline / 比较纪律

China-global comparison must specify the layer being compared: policy, governance, identity, discovery, messaging, tool access, runtime, evaluation, security, or industry adoption. Similar vocabulary does not prove equivalent architecture.

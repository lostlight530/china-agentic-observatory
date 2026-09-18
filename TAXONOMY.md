> [!NOTE]
> **Current architecture interpretation — 2026-09-18**
> - **Subject class:** `DEFINITION / TAXONOMY`
> - **Role:** Durable normalization vocabulary for historical stages, institutional levels, object classes, evidence classes, lifecycle, maturity, dates, scale, and China-global relations
> - **Authority:** Current China Observatory classification authority
> - **Current meaning:** Taxonomy organizes evidence while preserving institutional level, formal lifecycle, project maturity, geography, and same-layer comparison
> - **Evidence boundary:** official status is proposition-specific; family membership does not propagate maturity; similar terminology does not create direct equivalence
> - **Cross-document relation:** Scope defines coverage; Taxonomy normalizes institutional/lifecycle terms; Methodology defines evidence discipline; Source Registry owns source identities; C1–C7 own bounded domains; C8 synthesizes without manufacturing stronger evidence
> - **Update trigger:** Update only when a recurring China-specific distinction cannot be represented without ambiguity
> - **Preservation rule:** Earlier observation/report history remains time-scoped. This subject file changes only for durable framework correction or explicit current interpretive clarity

# Taxonomy / 分类体系

This taxonomy is the China Observatory's durable normalization layer for historical stage, institutional level, object type, formal lifecycle, project maturity, evidence class, date, and China–global comparison.

A taxonomy label organizes evidence. It does not make the underlying proposition true.

## Historical stages / 历史阶段

1. `FOUNDATIONS_PRE_1978` — computation, automation, control, pattern recognition, early machine intelligence
2. `RESEARCH_SYSTEM_1978_2009` — institutional rebuilding, national programs, universities, laboratories, industrial automation
3. `DEEP_LEARNING_INDUSTRIALIZATION_2010_2016` — internet platforms, vision, speech, data, accelerators
4. `NATIONAL_STRATEGY_2017_2022` — New Generation AI Development Plan, platformization, industrial policy
5. `GENERATIVE_AI_GOVERNANCE_2023_2024` — public generative services, model registration, content governance
6. `AI_PLUS_2025` — broad integration into economic and social systems
7. `AGENTIC_STANDARDS_2026` — agent policy, interconnection standards, identity, security, industry deployment

These are analytical navigation periods, not claims that all institutions or technologies transitioned on one date.

## Current domains / 当前领域

- `POLICY_STRATEGY`
- `LAW_GOVERNANCE`
- `STANDARDS_PROTOCOLS`
- `MODELS_ALGORITHMS`
- `AGENTS_PLATFORMS`
- `OPEN_SOURCE`
- `CHIPS_COMPUTE`
- `DATA_CLOUD_EDGE`
- `ROBOTICS_EMBODIED`
- `SCIENTIFIC_AI`
- `INDUSTRY_APPLICATIONS`
- `SAFETY_SECURITY`
- `ECONOMY_LABOR`
- `EDUCATION_CULTURE`
- `GLOBAL_RELATIONS`

Multi-domain classification is allowed; evidence from one domain does not automatically establish maturity in another.

## Institutional level / 机构层级

When authority or scale matters, distinguish:

- `NATIONAL_LEGISLATIVE_OR_STATE`
- `STATE_COUNCIL`
- `MINISTRY_OR_NATIONAL_REGULATOR`
- `NATIONAL_STANDARDIZATION_BODY`
- `PROVINCIAL_OR_LOCAL_GOVERNMENT`
- `INDUSTRY_OR_ASSOCIATION_BODY`
- `UNIVERSITY_OR_RESEARCH_INSTITUTE`
- `COMPANY_OR_PROJECT`
- `OPEN_SOURCE_COMMUNITY`
- `OTHER_PUBLIC_INSTITUTION`

Institutional level is not a quality ranking. It identifies what scope the source/object can authoritatively describe.

## Object classes / 对象类型

- `POLICY_OR_STRATEGY`
- `LAW_RULE_OR_MEASURE`
- `STANDARD_OR_TECHNICAL_DOCUMENT`
- `RESEARCH_PAPER_OR_PROJECT`
- `MODEL_OR_MODEL_FAMILY`
- `AGENT_FRAMEWORK_OR_RUNTIME`
- `PROTOCOL_OR_INTERCONNECTION_MECHANISM`
- `OPEN_SOURCE_PROJECT`
- `HARDWARE_OR_INFRASTRUCTURE`
- `PLATFORM_PRODUCT_OR_SERVICE`
- `PILOT_OR_DEPLOYMENT`
- `EVALUATION_OR_BENCHMARK`
- `INCIDENT_OR_SECURITY_GUIDANCE`

Similar names across classes must not be assumed to identify the same object.

## Evidence classification / 证据分类

Material statements remain distinguishable as:

- `OFFICIAL_FACT` — directly supported by a competent official/public-authority source within its scope;
- `PROJECT_FACT` — directly supported by the owning project/repository/company/research institution for its own object/state;
- `EXTERNAL_CLAIM` — attributed claim whose underlying proposition is not independently established by the cited surface;
- `OBSERVATORY_ANALYSIS` — repository interpretation based on cited evidence;
- `UNCERTAIN` — evidence is insufficient, conflicting, ambiguous, or the relevant transition/status cannot be established.

Official status is proposition-specific. An official policy source is not automatically evidence for a separate technical-performance proposition.

## Formal policy/standard lifecycle / 正式生命周期

Use these states only when supported by the relevant object and source:

`PLANNED`, `PROJECT_INITIATED`, `DRAFTING`, `CONSULTATION`, `REVIEW`, `APPROVED`, `PUBLISHED`, `IN_FORCE`, `SUPERSEDED`, `WITHDRAWN`, `UNCLEAR`

Not every object follows every state. Approval and publication may be distinct; publication and effectiveness may be distinct.

## Project/implementation maturity / 项目与实现成熟度

For software/model/platform/project objects:

`ANNOUNCED`, `PREVIEW`, `OPEN_SOURCED`, `RELEASED`, `MAINTAINED`, `DEPLOYED`, `RESTRUCTURED`, `DEPRECATED`, `ARCHIVED`, `UNCLEAR`

These states are object-scoped and can coexist across related layers. A standard can be `PUBLISHED` while an implementation remains `PREVIEW` or `UNCLEAR`.

## Date vocabulary / 日期词汇

Keep distinct:

- `EVENT_DATE`
- `ANNOUNCEMENT_DATE`
- `PUBLICATION_OR_UPDATE_DATE`
- `APPROVAL_DATE`
- `EFFECTIVE_DATE`
- `RELEASE_DATE`
- `OBSERVATION_DATE`
- `KNOWN_TRANSITION_DATE`

If a current page shows `APPROVED` but no approval date is recovered, record current observed state and leave exact transition time unknown.

## Scale and geography / 规模与地理范围

Use the narrowest supported scope:

- named organization/project;
- named city/province/region;
- named sector/industry;
- multi-region/multi-sector sample;
- national state only when national-scale evidence supports it.

```text
one project != national system
one locality != nationwide deployment
one firm != industry consensus
```

## China–global relationship vocabulary

Useful relationship states include:

- `SAME_LAYER_ANALOGUE`
- `COMPLEMENTARY`
- `PARTIALLY_COMPATIBLE`
- `DOCUMENTED_COMPATIBILITY`
- `TESTED_INTEROPERABILITY`
- `COMPETING_APPROACH`
- `DIFFERENT_LAYER`
- `NO_DIRECT_EQUIVALENT`
- `RELATION_UNCLEAR`

Do not claim direct equivalence merely because two systems share words such as agent, identity, protocol, platform, trust, or interconnection.

## Non-inheritance rules / 不继承规则

```text
policy published != implementation mature
standard published != adoption
approval display != exact transition time
open source != production deployment
case study != national maturity
quality result != rights/access/governance state
same family != inherited maturity
```

## Taxonomy governance

Add vocabulary only for recurring distinctions that existing categories cannot represent cleanly. New labels do not retroactively rewrite historical reports; earlier observations retain their original time boundary and may be mapped forward through explicit current interpretation.

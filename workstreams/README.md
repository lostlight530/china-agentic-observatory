# Preserved Workstreams / 保留分任务

The workstreams are the China Observatory's **durable research-responsibility map**. They separate policy, standards, research, engineering, infrastructure, applications, China–global comparison, and synthesis before those findings enter time-scoped reports.

They are not a scheduler and do not duplicate Daily/Weekly/Monthly SOPs.

## Workstream map

| ID | Workstream | Durable responsibility |
|---|---|---|
| C1 | [History, National Strategy, and Policy](./01-history-policy.md) | historical/institutional context, national strategy, ministry/regulatory policy, public governance lifecycle |
| C2 | [Standards, Protocols, Identity, and Interconnection](./02-standards-protocols.md) | national/industry/group standards, protocols, identity, discovery, interaction, trusted interconnection |
| C3 | [Research, Models, Algorithms, and Evaluation](./03-research-models.md) | universities/labs, papers, models, algorithms, multimodality, robotics/scientific AI and evaluation |
| C4 | [Agents, Platforms, Open Source, and Engineering](./04-agents-open-source.md) | agent frameworks/platforms, open source, engineering architectures, tools/memory/workflows/protocol adoption |
| C5 | [Chips, Compute, Data, Terminals, and Industrial Infrastructure](./05-infrastructure-industry.md) | domestic compute/chip/data/cloud/edge/terminal/robotics/industrial infrastructure and constraints |
| C6 | [Applications, Security Governance, and Social Impact](./06-applications-governance.md) | sector applications, security/governance, labor, education, culture and public impact |
| C7 | [China–Global Relationship](./07-china-global.md) | same-layer comparison between China-specific trajectories and global systems/standards |
| C8 | [Cross-Workstream Synthesis and Judgment Revision](./08-synthesis.md) | status reconciliation, deduplication, convergence/divergence, calibrated synthesis and judgment revision |

## Shared evidence contract

Every workstream keeps separate:

```text
source identity
source institutional level
claim type
relevant jurisdiction/geography
formal lifecycle state
project/implementation maturity
relevant dates
independent corroboration
observatory analysis
uncertainty
```

A policy target, standard, company announcement, pilot, approval display, open-source release, and nationwide deployment are different evidence objects.

## China-specific source discipline

Prefer the source closest to the proposition:

- laws/regulations and official rule texts for legal/regulatory claims;
- State Council / ministry / regulator material for national policy status;
- standards publishers/official standards systems for standard identity/status;
- universities/labs/original papers for research claims;
- source repositories and project documentation for open-source/project state;
- companies for their own product/release claims;
- independent research/data for broader performance, adoption, or impact claims.

An official source can be authoritative for policy existence while remaining insufficient for a separate technical-performance claim.

## Date and lifecycle discipline

Keep event, publication/update, effective, repository-observation, and known-transition dates distinct.

```text
current approved display != exact approval timestamp
policy publication != implementation completion
standard publication != ecosystem adoption
company case != national maturity
```

## Handoff to C8

C1–C7 hand off bounded findings with:

- entity/object and jurisdiction;
- exact proposition;
- source and source level;
- formal state/maturity;
- relevant dates;
- independent/counter evidence;
- explicit non-claims;
- cross-workstream significance.

C8 may synthesize or downgrade but must not manufacture missing state transitions or national-scale conclusions.

See [`../METHODOLOGY.md`](../METHODOLOGY.md), [`../SCOPE.md`](../SCOPE.md), and [`../TAXONOMY.md`](../TAXONOMY.md) for the shared research contract.

## Shared C1–C8 evidence handoff object

Use `(canonical_object, issuer, jurisdiction, institutional_level, formal_document_type, version_or_standard_number, formal_status, publication/effective/observation_dates, implemented_system_and_revision, deployment_population, exact_claim, source_identity, counterevidence, unresolved_fields)` for significant findings. Drop irrelevant fields explicitly as `NOT_APPLICABLE`, not as guessed values.

**Independent workstreams are not independent evidence by default:** C1 may cite a ministry announcement, C2 the same announcement's standard, and C4 a company citing that standard. Without distinct source surfaces or an implemented two-party test this is not three confirmations of interoperability. C8 owns deduplication, source lineage and current judgment; it cannot upgrade formal lifecycle, software maturity, national deployment or technical correctness by adding citations.

## C2 专项研究核验案例

- [C2 标准与协议的分层核验案例](./evidence-cases/C2_STANDARD_PROTOCOL_CROSSWALK.md) — 区分正式标准身份、技术条款、实现版本与双端互通，包含具体反例和核验字段，不新增 C 类别，不把规范声明写成实际部署


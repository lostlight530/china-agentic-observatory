> [!NOTE]
> **Current architecture interpretation — 2026-09-18**
> - **Subject class:** `WORKSTREAM DEFINITION`
> - **Role:** Durable responsibility contract for **Agents, platforms, open source and engineering**
> - **Authority:** Current workstream-scope authority for repository/project identity, release/maintenance state, implemented agent mechanics, protocol adapters and actual interoperability
> - **Current meaning:** This file defines how C4 contributes bounded evidence to the China Observatory. It is a stable research contract, not a periodic result and not an independent source merely by existing
> - **Evidence boundary:** repository exists != maintained; adapter present != interoperability verified; open source != production deployment. Evidence remains issuer-, proposition-, lifecycle-, geography-, population-, version- and date-bounded
> - **Cross-document relation:** `SCOPE.md` owns overall coverage; `TAXONOMY.md` owns China-specific institutional/lifecycle vocabulary; `METHODOLOGY.md` owns evidence/date/status discipline; `SOURCE_REGISTRY.md` owns admitted recurring source identities; C8 synthesis cannot strengthen C1–C7 evidence by aggregation
> - **Update trigger:** Update only when the durable workstream responsibility, handoff contract, comparison discipline, or evidence boundary changes materially
> - **Preservation rule:** Periodic observations and lifecycle transitions belong to time-scoped reports. This non-periodic workstream definition must not be rewritten merely because a new Daily/Weekly/Monthly result appears

# C4｜Agents, Platforms, Open Source, and Engineering / 智能体、平台、开源与工程

C4 tracks China's public agent-engineering surface: agent frameworks, runtimes/harnesses, platforms, workflows, memory, tools, computer use, source repositories, MCP/A2A-related implementation, orchestration, and architecture-level project change.

## Core questions

- What exactly exists: concept/demo, repository, SDK, framework, runtime, hosted platform, product feature, or production deployment?
- Which version/commit/release is being described, and is the project actively maintained?
- Which properties are implemented versus planned: tools, memory, task state, identity, permissions, computer use, sandboxing, recovery, observability, multi-agent coordination?
- Is MCP/A2A or another protocol merely mentioned, supported in one adapter, or demonstrably interoperable at a named version/profile?
- Does a repository restructuring or release materially change architecture, ownership, maintenance, or user-facing capability?

## Preferred evidence

Prefer source repositories, releases/tags, maintainers' documentation, issue/PR history when needed for project state, official platform documentation, and inspectable interoperability examples. Company announcements can establish company-reported availability but not independent reliability or adoption.

## Project maturity boundaries

```text
repository exists != maintained project
open sourced != production deployed
demo != stable capability
README claim != implemented behavior
adapter present != interoperability verified
protocol mentioned != protocol conformance
issue closed != underlying class of problem solved
```

Keep project identity, repository identity, release/version, organization ownership, licensing, and current maintenance state separate where material.

## Agent engineering boundaries

```text
tool access != authority
memory feature != durable trustworthy memory
workflow success != long-horizon reliability
computer use != safe autonomous operation
multi-agent support != consensus correctness
```

## Handoff to C8

C4 contributes the exact project/platform/version, implementation surface, maturity/maintenance state, protocol/tool/memory semantics, observed engineering evidence, deployment evidence if any, and unresolved limitations.

C4 does not infer national adoption, policy endorsement, or scientific superiority from open-source activity alone.

## Source-to-runtime verification ladder

Classify an agent project along `public repository -> located code path -> executable fixture -> bounded observed behavior -> external-effect verification -> cross-process recovery -> independent interoperability -> deployed usage`. Each property needs its own artifact and evidence; an SDK import, README compatibility claim or passing syntax check cannot satisfy all steps.

A valid long-running Agent claim names persistence locator, tool authorization owner, approval/version binding, operation receipt, retry/idempotency policy, and completion predicate. Tool exposure through MCP, A2A or a vendor framework is not the same as the caller being permitted to perform a specific effect. Names of protocols or a client/server adapter do not establish conformance to a target version.

**Counterexample:** a demo shows an agent recovering chat history after restarting the UI, while the task scheduler and external effect receipts are lost. That demonstrates some visible chat persistence, not durable task resumption or once-only side effects. Record missing identity and execution evidence explicitly instead of assigning a generic "enterprise ready" status.

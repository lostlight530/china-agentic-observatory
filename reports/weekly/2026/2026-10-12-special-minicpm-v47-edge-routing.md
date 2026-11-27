# 2026-10-12 Special — MiniCPM-V 4.7：端侧多模态推理与路由

- Repository: lostlight530/china-agentic-observatory
- Special ID: CHINA-S-20261012-minicpm-v47-edge-routing
- Record type: POST_HOC_SPECIAL_EVENT_RECONCILIATION / NON_CANONICAL_RESEARCH
- Event attribution: 2026-10-12 (publisher/local date; separate related dates below)
- Actual source recheck: 2026-11-27 Asia/Shanghai
- Original Native Daily credit: 0; no reopening of historical closure
- Canonical week: [2026-W42](./2026-W42.md); month: [2026-10](../../monthly/2026/2026-10.md)

## Evidence and chronology / 事实与日期

项目日志标记10月12日版本，模型包括35B-A3B与1B；文档讨论LES预取和端侧运行，发行方报告具体设备上的速度与内存。

- OpenBMB: https://github.com/OpenBMB/MiniCPM-V/blob/main/docs/minicpm_v4dot7_zh.md
- OpenBMB: https://github.com/OpenBMB/MiniCPM-V/blob/main/docs/changelog_zh.md

## Bounded technical analysis / 系统机制

模型权重、视觉编码、MoE专家路由、预取及设备内存带宽分别影响吞吐；预取不等于改变模型真实路由。端侧运行也不保证离线权限隔离。

## Counterevidence and verification plan / 证据边界

main文档可变，未锁定模型文件或复现速度；需要提交SHA、量化、设备、输入形状及首token延迟。

## Repository relations / 长期观察

[Daily date owner](../../daily/2026/10/2026-10-12.md) serves as chronology only, not proof of original source access. This is a distinct research object or explicitly scoped deeper mechanism analysis, not a new original observation. Preserve source lineage, date identity, original judgment and existing Special aggregates; later evidence is not silently propagated backwards.

## Disposition

SOURCE_BOUNDED / NON_CANONICAL. Independent benchmark, deployment, runtime, and conformance NOT_EXECUTED. No new Native, independent original workstream, or historical hypothesis credit.

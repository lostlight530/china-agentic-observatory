# 2026-09-14 Special — Jetson-PI：具身智能的端侧异步控制与计算系统

- Repository: lostlight530/china-agentic-observatory
- Record type: POST_HOC_SPECIAL_EVENT_RECONCILIATION / NON_CANONICAL_RESEARCH
- Special ID: CHINA-S-20260914-airs-jetson-pi-embodied-runtime
- Event attribution: 2026-09-14 (publisher/local date, where exact time absent no conversion inferred)
- Actual source recheck: 2026-11-27 Asia/Shanghai
- Scope: C3/C5/C6; source-bounded retrospective research; Native Daily credit: 0
- Canonical week: [2026-W38](./2026-W38.md); month: [2026-09](../../monthly/2026/2026-09.md)
- Original observation, historical closure and hypothesis credit unchanged

## Research question

推理时延下降如何成为安全实时控制？

## Primary evidence / 来源与事实

9月14日 AIRS 介绍与北大等合作的 CoRL 2026 录用工作 Jetson-PI：未来表征校正、置信度调度和板载推理优化。研究方报告 Jetson Orin 控制频率对朴素 PyTorch/vla.cpp 提升8.66/5.41倍；LIBERO 平均成功率提升14.8%，未独立复算

- AIRS: https://airs.cuhk.edu.cn/article/1447 — public page inspected 2026-11-27

## Technical analysis / 技术机制

VLA 推理与物理控制的时钟不同。预测未来表征可减少感知执行错位，但传感器新状态、已经提交的动作、调度和安全联锁仍需一致。论文录用与未来集成 AIRSEAI 不是产品部署。

## Counterevidence and independent validation boundary

原论文、代码实验、机器人传感日志及独立复现未检验。要求冻结硬件、控制周期、延迟分布与真实环境安全测试，不能直接迁移 benchmark 比例。

## Cross-system relations and long-term observation

已有 W37 注册接口对象不等于该论文/端侧 runtime 研究。 The event belongs to its own source and date identity. Rechecking a publisher is not a second independent scientific proof. Relate to the existing [Daily](../../daily/2026/09/2026-09-14.md) only as chronology; no claim that its original producer inspected this Special.

## Disposition

ADMITTED / SOURCE_BOUNDED. No new historical Native run, no canonical weekly reopening, no new original month closure, independent benchmark/conformance/runtime NOT_EXECUTED. The next verification must target the specific missing artifact above.

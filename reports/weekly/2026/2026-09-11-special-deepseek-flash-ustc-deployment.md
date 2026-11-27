# 2026-09-11 Special — DeepSeek V4.1 Flash 与中国科大部署：模型发布到可用服务

- Repository: lostlight530/china-agentic-observatory
- Record type: POST_HOC_SPECIAL_EVENT_RECONCILIATION / NON_CANONICAL_RESEARCH
- Special ID: CHINA-S-20260911-deepseek-flash-ustc-deployment
- Event attribution: 2026-09-11 (publisher/local date, where exact time absent no conversion inferred)
- Actual source recheck: 2026-11-27 Asia/Shanghai
- Scope: C3/C5/C6; source-bounded retrospective research; Native Daily credit: 0
- Canonical week: [2026-W37](./2026-W37.md); month: [2026-09](../../monthly/2026/2026-09.md)
- Original observation, historical closure and hypothesis credit unchanged

## Research question

模型 release 如何经异构算力、网关、认证变成真实用户服务？

## Primary evidence / 来源与事实

DeepSeek 9月10日公布552B MoE、输入8B/输出16B激活的非对称架构及KV存储压缩；中国科大9月12日公告9月11日接入其校内模型服务平台。发行时 V4 Pro 迁移计划与后续 API changelog 保留服务的描述不同

- DeepSeek；中国科大: https://deepseek.com/news/deepseek-v4-1-flash/ — public page inspected 2026-11-27
- DeepSeek；中国科大: https://news.ustc.edu.cn/zqzjg/info/1005/1402.htm — public page inspected 2026-11-27
- DeepSeek；中国科大: https://api-docs.deepseek.com/updates/ — public page inspected 2026-11-27

## Technical analysis / 技术机制

供应商给模型和 API 声明；高校提供另一个部署责任方的证据，但不是独立 benchmark。分开权重版本、模型 alias、网关路由、硬件和用户服务。校方所报12000用户和日均300亿词元是全平台口径，不能归给单模型。

## Counterevidence and independent validation boundary

无逐模型运行日志、成功率、单任务成本及模型路由 trace。核对两个 Pro 叙述的时间和调用实际版本；要求平台分模型统计和模型报告复现。

## Cross-system relations and long-term observation

既有 W37 Special 聚焦标准和 ITU，本篇增加实际机构部署及模型经济性。 The event belongs to its own source and date identity. Rechecking a publisher is not a second independent scientific proof. Relate to the existing [Daily](../../daily/2026/09/2026-09-11.md) only as chronology; no claim that its original producer inspected this Special.

## Disposition

ADMITTED / SOURCE_BOUNDED. No new historical Native run, no canonical weekly reopening, no new original month closure, independent benchmark/conformance/runtime NOT_EXECUTED. The next verification must target the specific missing artifact above.

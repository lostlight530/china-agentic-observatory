# C4｜Agent、平台与开放工程 / Native 2026-11-11

- logical_date: 2026-11-11 Asia/Shanghai
- actual_execution_at: 2026-11-11 16:32:50 Asia/Shanghai
- actual_execution_utc: 2026-11-11T08:32:50Z
- observation_cutoff: 2026-11-11 16:35:14 Asia/Shanghai
- observation_cutoff_utc: 2026-11-11T08:35:14.422Z
- repository_preflight_main: 3e84c9ad0b644a41b7fe5f98ea71526f622bf824
- observation_window: 当次有界官方来源、GitHub 与当前仓库研究，不代表全天新闻或系统运行覆盖
- date_semantics: source_event_date / publication_date / effective_date / observed_at / state_transition_date / delivery_or_merge_date 相互独立
- execution_boundary: external runtime、实验复现、CI、checker、TCK、conformance 均 NOT_EXECUTED

## 1｜Research question / 可证伪问题
本次有界复核能证明哪些 Agent、平台与开放工程 的确切对象及状态，哪些要求独立运行或正式规范来源

## 2｜Primary observations / 原始观察
Poppy 第一方版本清单在本轮显示 0.4 标注 published=2026-11-10，发布源码提交实际于 2026-11-11 02:36:55 UTC 进入 Git，发行方称为 1.0 Release Candidate；这不证明中国平台执行该协议或自动满足本地行业标准

## 3｜Judgment / 判断
- FIRST_PARTY_PROTOCOL_VERSION_PUBLICATION_CONFIRMED / CROSS_SYSTEM_DEPLOYMENT_UNKNOWN，publisher_date 与 commit_date 分离
- observed_at: 2026-11-11 16:35:14 Asia/Shanghai
- exact state transition time: UNVERIFIED unless the issuer explicitly provided it
- issuer statements、portal metadata、repository evidence 和 independent runtime evidence 分开处理

## 4｜Falsifier and next check / 反证及后续
需本地平台真实版本化实现和正式引用条款，不能把同名身份或批准接口当作规范等价

## 5｜Primary sources / 一手来源
- poppy_manifest: https://github.com/personal-agent-protocol/personal-agent-protocol/blob/ed474089d0fdeafae9584a95cfcc485209d8b124/content/versions/versions.json
- poppy_commit: https://github.com/personal-agent-protocol/personal-agent-protocol/commit/48039002795c9ebb390f1966fb70f82e4790efb6
- yd: https://std.samr.gov.cn/hb/search/stdHBDetailed?id=5A166B0E8BF82BDAE06397BE0A0A0423

## 6｜Limit / 边界
本轮未运行外部系统、审批流程、checker、CI、TCK、conformance，任何存在性或网页显示都不是对应执行 PASS

# C7｜中国与全球互联关系 / Native 2026-11-09

- logical_date: 2026-11-09 Asia/Shanghai
- actual_execution_at: 2026-11-09 18:16:22 Asia/Shanghai
- actual_execution_utc: 2026-11-09T10:16:22Z
- observation_cutoff: 2026-11-09 18:33:23 Asia/Shanghai
- observation_cutoff_utc: 2026-11-09T10:33:23.161Z
- repository_preflight_at: 2026-11-09 18:30:42 Asia/Shanghai
- base_main_sha: 312e6b468f834587bb6d35d39184d13d59f2c6cd
- observation_window: 2026-11-09 单次有界来源核验与仓库状态读取，不代表对外部全日事件的完整扫描
- provenance: event_date、publication_date、effective_date、observed_at 与 state_transition_date 分开记录，晚发现旧来源不回写为旧日已知
- execution_boundary: 外部软件、部署、checker、CI、TCK、conformance、runner 均 NOT_EXECUTED

## 1｜可证伪问题
中国新研究与全球 Agent / 科学 AI 进展是否构成同一技术层的可互操作实现，还是仅在相邻层面出现主题相似

## 2｜Primary observations
AutoDNA 与 OpenAI × Ligo BioBasicsBench 形成一组值得比较但不能混为一谈的科学 Agent 证据

- AutoDNA 重点在实验设计、Agent 任务分解、仪器接口、硬件执行与实验结果反馈，属于物理实验执行层
- BioBasicsBench 评估 Agent 对凝胶图像、显微镜数据、仪器读数、实验记录和控制条件的解释能力，属于实验数据理解与判断层
- 两者分别覆盖科学工作流的执行侧与分析侧，不能相互证明对方能力，也没有共同的端到端评测协议

Agent Substrate 1.0 在 Global F3/F4 提供 sandboxed actor runtime、snapshot 与 suspend/resume 证据，但没有证据表明它与 AutoDNA 的仪器控制栈集成

- source_1: https://openai.com/index/measuring-how-ai-agents-handle-wet-lab-science
  - support: 100 个实验数据解释任务与发行方评测方法
  - source_class: FIRST_PARTY_RESEARCH_BENCHMARK_ANNOUNCEMENT
  - publication_date: 2026-11-06
- source_2: https://www.nature.com/articles/s41586-026-11228-6
  - support: AutoDNA 物理实验执行研究
  - source_class: PEER_REVIEWED_ORIGINAL_RESEARCH
  - publication_date: 2026-11-04
- source_3: https://github.com/agent-substrate/substrate/releases/tag/v1.0.0
  - support: 通用 Agent sandbox runtime 发布工件
  - source_class: OFFICIAL_PROJECT_RELEASE
  - publication_date: 2026-11-05

## 3｜Judgment / 有界结论
- material_result: COMPLEMENTARY_LAYER_EVIDENCE / NO_CROSS_SYSTEM_INTEROPERABILITY_PROVEN
- physical_execution != scientific_data_interpretation
- sandbox_runtime != instrument_control_contract
- shared_agent_label != shared_authority_or_recovery_semantics

## 4｜Falsifier and next check / 反证与后续
需要跨系统实际连接、版本化 instrument API、Agent 身份和委托权限映射、动作级审计、异常恢复以及独立重复实验

## 5｜Evidence limits / 失败模式
OpenAI benchmark 与 AutoDNA 来自不同研究主体，但任务层、数据、评价指标和实验环境不同；两者并列不构成同一 benchmark 的独立复现
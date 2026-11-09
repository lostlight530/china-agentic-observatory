# C3｜模型、方法与评价 / Native 2026-11-09

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
新论文、模型或方法是否提供了可定位的研究对象与实际实验结果，还是只有发行方产品能力声明

## 2｜Primary observations
**AutoDNA｜Nature Article**

- publication_date: 2026-11-04
- observed_at: 2026-11-09 18:33:23 Asia/Shanghai
- Nature 论文提出面向生物分子工程的 AI-native autonomous laboratory
- 摘要报告系统跨越 20 余类仪器执行 11,000 余步，人工干预限于硬件维护任务，例如试剂和实验耗材补充
- 四项代表性应用包括匹配专家优化的酶促 DNA 合成产量、并发实验流程执行速度提升 3.2 倍、端到端 DNA 数据存储并精确恢复原始数字内容，以及识别并验证临床检测到的 KRAS G13D 突变
- 论文说明代码公开于 GitHub，相关测序数据与 Agent 输出存放于 Zenodo

**AutoDNA｜机构与项目页面**

- 上海交通大学张江高等研究院页面 publication_date: 2026-11-06，报告 DNA 存储读写周期执行 11,382 次硬件操作
- IPADS 项目主页当前显示 25+ instruments 与 11,386 autonomous hardware steps
- NCSTI 于 2026-11-09 09:11:32Z 转载中国科学报报道，显示 11,382 次操作，属于同一研究团队成果的再传播，不是独立复现

**Hi-WBC｜北京人形机器人创新中心发行方声明**

- issuer_event_date: 2026-11-02
- publication_date: 2026-11-07
- 新闻稿将 Hi-WBC 描述为全身控制模型，声明采用 MoE 专家策略、策略蒸馏、Contact-aware Learning 与 Perceptive Control，并介绍两项机器人演示
- 本轮未定位到可公开下载的模型权重、技术论文、完整系统卡或独立评测

- source_1: https://www.nature.com/articles/s41586-026-11228-6
  - support: 论文摘要、四项应用、代码与数据可用性
  - source_class: PEER_REVIEWED_ORIGINAL_RESEARCH
  - publication_date: 2026-11-04
- source_2: https://zias.sjtu.edu.cn/info/1017/22778.htm
  - support: 研究团队、装置、11,382 次操作与实验场景
  - source_class: UNIVERSITY_FIRST_PARTY_RESEARCH_ANNOUNCEMENT
  - publication_date: 2026-11-06
- source_3: https://ipads.sjtu.edu.cn/autodna/
  - support: 项目主页显示的 25+ instruments 与 11,386 steps
  - source_class: PROJECT_FIRST_PARTY_PAGE
  - observed_at: 2026-11-09 18:33:23 Asia/Shanghai
- source_4: https://www.ncsti.gov.cn/kjdt/kjrd/rgzn_kjrd/202611/t20261109_262150.html
  - support: 2026-11-09 中国科学报转载
  - source_class: OFFICIAL_PLATFORM_REPRINT
  - publication_date: 2026-11-09T09:11:32Z
- source_5: https://www.prnasia.com/story/555228-1.shtml
  - support: Hi-WBC 发行方新闻稿及演示声明
  - source_class: ISSUER_PRESS_RELEASE
  - publication_date: 2026-11-07

## 3｜Judgment / 有界结论
- material_result: MATERIAL_RESEARCH_SOURCE_DISCOVERY
- AutoDNA: PEER_REVIEWED_PAPER_AND_PUBLIC_CODE_DATA_POINTERS
- Hi-WBC: ISSUER_CLAIM_WITH_DEMO_DESCRIPTION
- independent_replication: NOT_OBSERVED
- exact_count: UNRESOLVED

## 4｜Falsifier and next check / 反证与后续
获取 AutoDNA 的复现实验记录、完整补充材料、跨实验室重复结果与 Hi-WBC 的版本化权重、系统卡和匹配基准后再升级结论

## 5｜Evidence limits / 失败模式
Nature 摘要写 20 余类仪器与 11,000 余步，SJTU 与 NCSTI 写 11,382 次，IPADS 项目主页写 11,386 次，统计口径差异未解释；不得选取单一数字覆盖其他来源；论文结果仍不等于独立实验室复现
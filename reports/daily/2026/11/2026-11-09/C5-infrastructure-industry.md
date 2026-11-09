# C5｜基础设施与产业 / Native 2026-11-09

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
本日是否出现真实物理基础设施运行或产业部署证据，能够区分研究装置、演示系统与规模化生产服务

## 2｜Primary observations
AutoDNA 的论文报告跨 20 余类仪器执行超过 11,000 步，覆盖核酸合成、转录、扩增与测序；作者报告 DNA 存储端到端写入、保存、读取与解码后精确恢复原始数字内容，并报告并发实验流程执行速度提升 3.2 倍

不同一手页面的硬件操作计数为：Nature 摘要超过 11,000，SJTU 与 NCSTI 报道 11,382，IPADS 项目主页 11,386，计数定义未见解释

Hi-WBC 新闻稿描述人形机器人全身控制演示及多机器人任务协同，但未给出部署规模、连续运行时长、故障率、现场验收或第三方性能测量

- source_1: https://www.nature.com/articles/s41586-026-11228-6
  - support: 研究装置和四项实验结果
  - source_class: PEER_REVIEWED_ORIGINAL_RESEARCH
- source_2: https://ipads.sjtu.edu.cn/autodna/
  - support: 项目主页显示的仪器数量与硬件步骤计数
  - source_class: PROJECT_FIRST_PARTY_PAGE
- source_3: https://www.prnasia.com/story/555228-1.shtml
  - support: Hi-WBC 发布方演示描述
  - source_class: ISSUER_PRESS_RELEASE
- observed_at: 2026-11-09 18:33:23 Asia/Shanghai

## 3｜Judgment / 有界结论
- material_result: PHYSICAL_EXECUTION_RESEARCH_EVIDENCE / NO_SCALE_DEPLOYMENT_VERIFIED
- throughput_claim: PAPER_REPORTED_3_2X / INDEPENDENTLY_NOT_MEASURED
- deployment_scope: RESEARCH_LAB_AND_ISSUER_DEMO
- industrial_adoption_rate: UNKNOWN

## 4｜Falsifier and next check / 反证与后续
后续需要长期运行日志、设备可用性、错误率、人工接管次数、维护成本、跨仪器兼容矩阵和独立用户部署证据

## 5｜Evidence limits / 失败模式
单一研究装置的操作计数不是全国部署统计；3.2 倍是论文报告结果，不是本仓独立量测；演示不等于生产部署
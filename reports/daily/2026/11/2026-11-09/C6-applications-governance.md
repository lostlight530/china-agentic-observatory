# C6｜应用、风险与社会治理 / Native 2026-11-09

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
新应用是否有明确场景与可追溯结果，是否同时公开了足以判断安全责任、人工监督和监管边界的证据

## 2｜Primary observations
AutoDNA 论文报告核酸检测、酶促 DNA 合成、DNA 数据存储和 KRAS G13D 突变识别验证等代表性应用，其中 DNA 存储循环准确恢复写入的数字内容，KRAS G13D 结果是研究团队报告的临床检测突变验证案例

Nature 摘要说明人工干预限于硬件维护任务，例如补充试剂和实验耗材，这比“完全无人参与”的宣传式表达更精确，但仍未给出覆盖所有实验类型的安全认证、事故统计、临床监管批准或跨实验室风险评估

Hi-WBC 发布稿涉及真实机器人演示，但本轮未发现独立安全评测、事故与故障数据、场景边界或正式准入文件

- source_1: https://www.nature.com/articles/s41586-026-11228-6
  - support: 应用结果与人工维护边界
  - source_class: PEER_REVIEWED_ORIGINAL_RESEARCH
- source_2: https://www.prnasia.com/story/555228-1.shtml
  - support: 人形机器人演示声明
  - source_class: ISSUER_PRESS_RELEASE
- source_3: https://www.cac.gov.cn/2026-05/08/c_1779979789523320.htm
  - support: 既有智能体治理政策基线
  - source_class: OFFICIAL_POLICY
- observed_at: 2026-11-09 18:33:23 Asia/Shanghai

## 3｜Judgment / 有界结论
- material_result: RESEARCH_APPLICATIONS_REPORTED / SAFETY_AND_REGULATORY_MATURITY_UNKNOWN
- clinical_deployment: NOT_ESTABLISHED
- human_oversight: MAINTENANCE_INTERVENTION_REPORTED
- robot_safety_certification: NOT_OBSERVED

## 4｜Falsifier and next check / 反证与后续
需要临床或行业准入文件、风险分析、人工接管与紧急停止记录、设备失效模式、事故披露及独立复现实验

## 5｜Evidence limits / 失败模式
识别并验证临床检测到的突变不等于临床诊断产品获批；研究实验准确恢复不等于生产级长期可靠性；发布稿不构成安全认证
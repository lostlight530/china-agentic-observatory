# C4｜Agent 工程、开放系统 / Native 2026-11-09

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
新研究是否公开了可复核的 Agent 任务分解、工具接口、身份授权、运行状态和故障恢复机制

## 2｜Primary observations
AutoDNA 项目主页描述六个专业 LLM agents 协作，覆盖实验方案、假设、控制代码与实验流程；上海交通大学研究说明进一步描述文献检索、试剂选择、方案设计、代码生成、硬件执行、结果分析与迭代优化的分工

项目把仪器能力抽象成自然语言描述与统一代码接口的 atomic services，结合高精度硬件、程序检查、仪器状态跟踪和资源调度，将 Agent 生成的实验设计转化为实际设备操作

- GitHub 代码仓库：https://github.com/IPADS-X/AutoDNA
- Nature 数据与代码记录：https://doi.org/10.5281/zenodo.20624108
- 项目主页：https://ipads.sjtu.edu.cn/autodna/
- 机构说明：https://zias.sjtu.edu.cn/info/1017/22778.htm

仓库 Quick Start 中出现 Gemini API key 配置要求，这是代码安装说明中的依赖信息，不足以证明论文实验使用的具体模型版本、线上部署拓扑或每次设备调用的模型身份

Hi-WBC 本轮只有发行方新闻稿与 Demo 叙述，未发现公开代码、权重或可执行 API 契约

## 3｜Judgment / 有界结论
- material_result: NEW_MULTI_AGENT_PHYSICAL_TOOL_ORCHESTRATION_CASE
- instrument_atomic_service: PROJECT_LOCAL_ABSTRACTION
- formal_protocol_mapping: NOT_VERIFIED
- portable_identity_authority: NOT_OBSERVED
- per_action_audit_and_recovery_contract: NOT_OBSERVED

## 4｜Falsifier and next check / 反证与后续
需要每个 Agent、操作者、仪器与资源的可定位身份，明确授权范围、批准与撤销，版本化工具 schema、动作级审计、失败幂等与补偿、状态恢复 trace，以及跨实验室可复现结果

## 5｜Evidence limits / 失败模式
论文与项目主页可以证明系统设计与作者报告的实验，不等于本仓执行代码；atomic services 不自动等于 MCP tools、A2A task 或正式行业接口；外部项目未运行，conformance 与 TCK NOT_EXECUTED
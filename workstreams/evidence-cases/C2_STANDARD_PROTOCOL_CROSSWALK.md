# C2 — 标准、技术协议与互联互通的分层核验证据

**Subject class：** C2 领域方法实例，不新增 C1–C8 分类，不是本月标准发布清单  
**Owner：** [C2 标准、协议、身份与互联](../02-standards-protocols.md)  
**校准日期：** 2026-11-15，仅依据当前仓库原生分类与研究契约，未对任一特定标准进行本次实时状态核查

## 总论：规范性权威与工程事实不能混为一谈

对涉及中国标准和 Agent 协议的命题，至少独立记录四个对象

1. **正式文献对象：** 主管或发布机构、文种、标准号、版本、公布与实施日期、正式生命周期状态、规范性/资料性条款
2. **技术语义对象：** 发现、主体身份、认证、授权、委托、撤销、消息交换、任务状态、错误与恢复、外部效果这些性质中究竟定义了哪些
3. **实现对象：** 代码仓库和具体版本、相应 SDK/服务端/客户端的实现范围、配置、安全剖面和本地扩展
4. **互操作证据：** 两端实际测试的方向、版本、传输、凭据、请求、响应、异常结果、效果端回执和可复核记录

没有第 3/4 层证据时，第 1/2 层可以支持「文件提出了某要求」，不能支持「产业已实现互操作」

## 正式身份校验字段

`(issuer, publication_system, exact_number, standard_type, revision, document_title, normative_status, lifecycle_state, announcement_date, publication_date, effective_date, clause_reference, primary_URL, observation_date)`

`GB`、`GB/T`、`GB/Z`、行业标准、地方标准、团体标准与企业技术协议不能互相重命名，它们的法规范畴、组织身份和使用关系必须由对应的一手体系核验

某条信息是**拟立项、立项、征求意见、送审、报批、发布、实施、修订、废止**中的哪一种，应以对应对象的官方状态为准，原始记录缺少确切转换日期时状态可确认、日期仍可未知

不能因为第三方媒体称某技术为「国标」，就自动分配一个 GB/T 身份，不能因为正式标准已发布，就推断某厂商完成了测试认证

## 最小可证伪案例

| 案例 | 容易发生的错误推断 | 所需反证或核验证据 | 允许的最强结论 |
| --- | --- | --- | --- |
| C2-1 | 标准项目获批立项，等同正式实施 | 官方标准项目号、状态和公布/实施日期 | 对应状态存在，不继承后续阶段 |
| C2-2 | 两份文件都定义 agent ID，故身份体系兼容 | 身份对象、命名空间、密钥绑定、认证与撤销条款 | 仅存在同类术语，互操作未知 |
| C2-3 | 协议文档规定授权，故工具操作安全 | 具体执行方、权限判定点、资源解析、作用域和实际决策记录 | 规范给出条件，不等于实现保证 |
| C2-4 | SDK 声称支持协议，故跨厂商系统已经互通 | 两端精确版本、配置、方向、测试消息、失败轨迹和实际结果 | 至多支持单方实现声明 |
| C2-5 | 测试握手成功，故长期任务可恢复 | 断线/进程重启后任务存储身份、未决效果、权限有效期 | 握手成功，Durable Execution 未证实 |
| C2-6 | 中国正式文件与外国产品使用相同术语，因此产业先进性可直接排序 | 先将法律/标准/代码/部署层级配平，再比较相同指标 | 层级不同则拒绝给出单一胜负判断 |
| C2-7 | 同一新闻被多家媒体转述，构成独立验证 | 原始发布源、转述链、实际测试来源 | 多次转述仍只有一个原始证据血缘 |

所有案例都是供 C2 科研使用的**反例构造与审核问题**，不是现阶段已经观察到具体公司、机构存在该问题的事实

## 互操作试验最小数据格式

```text
test_object:
  formal_standard_ref: <official number/version/status or NOT_APPLICABLE>
  side_A: <implementation and exact revision>
  side_B: <implementation and exact revision>
  profile_and_transport: <negotiated profile and security settings>
  principal_and_authority: <actor, proof, scope and validity>
  task_and_effect: <task identity, acknowledgement and effect-sink receipt>
  replay: <exact fixture, command, trace, observed result and failure>
  evidence_independence: <primary origin and any independent implementation>
  date_and_limit: <observation date, unresolved dimensions>
```

以上是研究记录结构，不是声称已生成或执行的测试文件

## C2 → C7/C8 交接

C2 交付版本绑定的正式状态与技术条款，C4 交付本地 Agent 实现和效果证据，C7 按相同层级比较中外对象，C8 去重、标记冲突、保留不确定性

任何跨层结论需要明确提升依据，不能靠标准编号、厂商认证话术、案例宣传或引用数量自行升级

**本次证据边界：** 外部标准实时状态 `NOT_REVALIDATED`，新测试 `NOT_EXECUTED`，原本的历史状态不在此修改或重分类

# Daily SOP / 每日研究标准作业程序

## Mission / 唯一职责

每天使用公开权威来源完成一次中国人工智能全景研究，并交付一份完整每日研究记录。

> **允许无变化，不允许无报告。**

Daily 的目标不是堆新闻，而是回答：

```text
今天出现了什么新证据
↓
它改变了昨天哪个判断
↓
没有改变什么
↓
证据等级是什么
↓
边界在哪里
↓
下一步应该追什么
```

## Before research / 开始前

1. 读取最新远端 `main`
2. 确认昨日 PR 是否已合并；未合并不得假装进入历史
3. 读取昨日 integrated daily、当前 canonical weekly、Source Registry、watchlist 和必要历史基线
4. 确认 Asia/Shanghai 日期与 observation cut-off

## Required workstreams / 保留分任务

- C1 历史、国家战略与政策
- C2 标准、协议、身份与互联
- C3 模型、算法、科研与评测
- C4 智能体、平台、开源与工程架构
- C5 芯片、算力、数据、终端与产业基础设施
- C6 应用场景、安全治理与社会影响
- C7 中国与全球路线关系
- C8 跨任务综合与判断修正

所有 C1–C8 都必须被检查；没有 material change 可以明确记录 unchanged。

## Source and evidence discipline / 信源与证据纪律

1. 优先 C0–C4 权威来源，C5–C6 只作补充或发现线索
2. 先验证信息存在，再解释意义
3. 区分 event / publication / effective / observation / known transition date
4. 区分 `OFFICIAL_FACT` / `PROJECT_FACT` / `EXTERNAL_CLAIM` / `OBSERVATORY_ANALYSIS` / `UNCERTAIN`
5. 同源重复不算独立增强
6. current-state confirmation 不得写成 same-day transition
7. 无强新证据时使用 `NO MATERIAL CHANGE / UNCHANGED`
8. 不为了日报制造新 H 或趋势

## Required daily pack / 每日交付

China daily pack固定为：

```text
reports/daily/YYYY/MM/YYYY-MM-DD.md
reports/daily/YYYY/MM/YYYY-MM-DD/
├─ README.md          # task index
├─ C1-history-policy.md
├─ C2-standards-protocols.md
├─ C3-research-models.md
├─ C4-agents-open-source.md
├─ C5-infrastructure-industry.md
├─ C6-applications-governance.md
├─ C7-china-global.md
└─ C8-synthesis.md
```

创始期历史文件若形成于该 pack 规则之前，不为排版统一伪造缺失分任务；真实缺口必须如实保留。

## Integrated report structure / 主报告结构

```markdown
# <Daily theme> / <中文主题>
## China AI Daily Research Report / 中国人工智能每日研究报告
### YYYY-MM-DD

## 0｜Executive Judgment / 核心判断
## 1｜Research Scope / 今日研究范围
## 2｜Historical Continuity / 历史连续性
## 3｜Policy and Standards / 政策与标准
## 4｜Research, Models, and Infrastructure / 科研、模型与基础设施
## 5｜Agents, Open Source, and Industry / 智能体、开源与产业
## 6｜Applications, Security, and Society / 应用、安全与社会
## 7｜China–Global Relationship / 国内外路线关系
## 8｜Changed and Stable Judgments / 判断修正与稳定判断
## 9｜Uncertainties and Watchlist / 不确定与观察点
## 10｜Primary Sources / 一手来源
```

## Weekly handoff / 向周报交接

日报完成后，仅当证据改变本周 hypothesis 状态时，原地更新同一 `reports/weekly/YYYY/YYYY-Www.md`。

日报不是周报缩写；周报也不是日报拼接。

## Durable assets / 长期资产

- `SOURCE_REGISTRY.md`：仅新增耐久新源或明确状态修正
- `watchlist/ACTIVE.md`：仅新增 / 关闭 / 升级长期问题
- 不因为每日重复检查而复制已有条目

## Correction discipline / 更正纪律

发现昨日或历史错误时：

```text
old repository statement
→ new evidence / audit finding
→ explicit correction
→ preserved temporal explanation
```

later evidence 不得倒灌成 earlier-day fact。

## Forbidden / 禁止事项

- 不运行、部署或测试外部项目
- 不把政策目标写成能力已实现
- 不把计划、起草、审查写成已发布实施
- 不把企业宣传或个案写成全国性事实
- 不用媒体替代可获得的一手源
- 不为了日报制造趋势
- 不静默删除历史错误
- 不创建自动化任务
- 不改 CI / GitHub Actions
- 不自动 merge
- 不直接写 main

## GitHub delivery boundary / GitHub 交付边界

```text
latest merged main
→ new daily branch
→ daily pack
→ canonical weekly update in place
→ README / durable assets only when needed
→ compare main...branch
→ behind_by = 0
→ Draft PR
→ verify mergeable
→ STOP
```

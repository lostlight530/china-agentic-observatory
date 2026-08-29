# Weekly SOP / 每周研究标准作业程序

## Mission / 唯一职责

把同一 Asia/Shanghai 自然周已经形成的日报、权威来源和判断变化压缩为一份**有记忆的假设系统**。

> **周日不是清空，周一不是重启。**

## Canonical file / 唯一周报

```text
reports/weekly/YYYY/YYYY-Www.md
```

一周只维护这一份 canonical weekly，周中原地推进，不建立按日期拆分的新周报。

仓库成立前不存在的日期不得补写。创始周或缺口必须显式声明真实 coverage。

## Weekly state machine / 周度状态机

```text
Monday opening hypotheses
↓
Tue–Sat evidence accumulation / correction
↓
Sunday settlement
↓
Durable / Strengthened But Open / Open / Refuted
↓
carry unresolved state forward
```

周报不是 7 篇日报拼接。

## Monday opening / 周一开启

1. 当日 integrated daily 已形成
2. 读取上一周 final、watchlist、Source Registry 与当前日报
3. 建立真实 Coverage Window
4. 提出有限、可证伪 hypotheses
5. 每个 H 写明 strengthening evidence 与 falsifier
6. durable doctrine 作为 baseline，不重新包装成新发现

## Midweek updates / 周中推进

使用：

- `NEW`
- `STRENGTHENED`
- `UNCHANGED`
- `WEAKENED`
- `OPEN`
- `REFUTED`

同源重复不算独立 strengthening。

无 material change 时允许 weekly 保持不变；不要为了“每天都改周报”而制造状态变化。

## Sunday settlement / 周日收口

只有本周最后一个真实 observation-day daily 已形成后才能 final closure。

必须完成：

1. 核对 coverage 与日报数量
2. 汇总真正 changed judgments
3. 逐一结算全部 H
4. 分开 `DURABLE`、`STRENGTHENED BUT OPEN`、`OPEN`、`REFUTED`
5. 提炼最窄 durable doctrine
6. 记录 correction / counterevidence
7. 列出 open gaps
8. 形成 next-week carry-forward
9. 不制造 Sunday novelty

## Canonical structure / 推荐结构

```markdown
# <Theme> / <主题>
## China AI Weekly Research — YYYY-Www Final

## 0｜Coverage and Closure State / 覆盖与收口状态
## 1｜Executive Weekly Judgment / 周度核心判断
## 2｜Evidence Added This Week / 本周新增证据
## 3｜Hypothesis Settlement / 假设结算
## 4｜Durable and Changed Judgments / 稳定与变化判断
## 5｜Corrections and Counterevidence / 更正与反证
## 6｜China–Global Relationship / 国内外路线关系
## 7｜Open Gaps / 未解决缺口
## 8｜Next-Week Carry-Forward / 下周延续
## 9｜Primary Sources and Daily Records / 一手来源与日报索引
```

## Legacy weekly snapshots / 历史周中快照

仓库早期若因工具限制留下 `YYYY-Www-YYYY-MM-DD-progress.md`：

- 保留历史，不删除
- 必须标记 `LEGACY_NON_CANONICAL`
- 必须指向最终 canonical `YYYY-Www.md`
- 不再更新
- 新 Agent 不得把它当第二份周报

## Boundaries / 边界

```text
政策任务 ≠ 已完成能力
标准计划 ≠ 已发布标准
相近标准 ≠ formal crosswalk
case implementation ≠ nationwide interoperability
same-source repetition ≠ independent evidence
```

不运行/部署/测试外部项目；不建自动化；不改前端/运行时代码/Actions；不自动 merge；不直接写 main。

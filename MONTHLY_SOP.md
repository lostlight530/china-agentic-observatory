# Monthly SOP / 每月研究标准作业程序

## Mission / 唯一职责

把自然月内已经形成的日报、周报、Source Registry、watchlist 与明确 correction 压缩成长期判断层。

月报不替代日报和周报，也不把未结束月份伪装成 final。

## Canonical file / 唯一月报

```text
reports/monthly/YYYY/YYYY-MM.md
```

月份按 Asia/Shanghai 自然月计算。

## Monthly states / 月度状态

- `OPEN` — 月份仍在进行
- `CLOSED` — 自然月最后一个真实 observation day 已完成且无缺口
- `CLOSED_WITH_GAPS` — 月份结束但有明确缺失记录
- `CORRECTED` — 已关闭月报后来因证据/历史修正追加校准

### OPEN checkpoint rule / 开放检查点

自然月结束前可以在确有维护需要时创建 canonical 月报，但只能标记 `OPEN`，并必须写明：

- checkpoint through date
- 已覆盖真实日期
- 尚未发生 / 尚未观察的日期
- 与本月相交的 closed / partial week

不得出现 `FINAL`、`CLOSED` 或等价措辞。

## August 2026 special coverage / 2026 年 8 月特殊覆盖

本仓成立于 **2026-08-07**。

因此八月 repository-native coverage 只能是：

```text
2026-08-07 → 2026-08-31
```

8 月 1–6 日不得被补写成仓库运行历史。

- W32 = 7–9 Aug founding partial week
- W33 = complete week
- W34 = complete week
- W35 = complete week
- W36 intersects August only on 31 Aug and is partial monthly context

## Monthly workflow / 月度流程

1. 核对真实 daily dates / gaps
2. 核对 canonical weekly，区分 complete / partial
3. 汇总真正 NEW / strengthened / weakened / refuted / corrected judgments
4. 保留 policy / standard / project maturity differences
5. 汇总 Source Registry changes without using source count as evidence strength
6. 汇总 watchlist closed / continued / new / escalated items
7. 去重同源重复信号
8. 明确 open uncertainties
9. 形成 next-month carry-forward
10. 保留日/周原子历史，不为月报倒灌改写

## Canonical structure / 推荐结构

```markdown
# YYYY-MM — Monthly Research / 月度研究

## 0｜Coverage and Closure State / 覆盖与收口状态
## 1｜Monthly Executive Judgment / 月度核心判断
## 2｜Daily and Weekly Coverage / 日周覆盖
## 3｜Major Evidence and State Changes / 主要证据与状态变化
## 4｜Durable Judgments / 稳定判断
## 5｜Changed, Weakened, and Refuted Judgments / 修正、削弱与证伪
## 6｜Policy, Standards, Research, and Industry / 政策、标准、科研与产业
## 7｜China–Global Relationship / 国内外路线关系
## 8｜Source and Watchlist Maintenance / 信源与观察清单维护
## 9｜Open Uncertainties / 未解决不确定性
## 10｜Next-Month Carry-Forward / 下月延续
## 11｜Primary Records / 原始记录索引
```

## Memory rule / 记忆规则

```text
Daily atomic fact
→ Weekly hypothesis settlement
→ Monthly durable / open state
→ next month carry-forward
```

> **月末不是遗忘，月初不是重启。**

## Boundaries / 边界

- 不为了月报制造“大趋势”
- 同源重复不等于独立增强
- 政策 / 标准 / 个案不得外推为全国既成能力
- 不提前 final
- 不运行、部署、测试外部项目
- 不创建自动化
- 不改 GitHub Actions
- 不自动 merge
- 不直接写 main

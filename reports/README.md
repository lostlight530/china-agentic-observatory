# Reports / 研究报告

This directory is the observatory's time-structured memory.

```text
Daily = atomic observation
Weekly = hypothesis memory and settlement
Monthly = long-horizon compression and carry-forward
```

## Daily / 每日

`daily/` contains the atomic research record.

Current operating rule:

> **允许无变化，不允许无报告。**

For the mature China workflow, one observation day contains:

```text
Integrated Daily
+ C1–C8
+ task index
```

Daily maintenance follows [`DAILY_SOP.md`](../DAILY_SOP.md).

Historical daily records created before the current pack/layout convention remain valid atomic history. They are not retroactively rewritten solely for style. Factual/state corrections must remain explicit and may be added when necessary.

## Weekly / 每周

One ISO week has exactly one canonical file:

```text
weekly/YYYY/YYYY-Www.md
```

Current canonical chain:

- [`2026-W32`](./weekly/2026/2026-W32.md) — **CLOSED**, founding partial week, 7–9 Aug
- [`2026-W33`](./weekly/2026/2026-W33.md) — **CLOSED**, 10–16 Aug
- [`2026-W34`](./weekly/2026/2026-W34.md) — **CLOSED**, 17–23 Aug
- [`2026-W35`](./weekly/2026/2026-W35.md) — **CLOSED**, 24–30 Aug

Historical date-named `*-progress.md` files are **legacy non-canonical snapshots** retained for audit only. They are superseded by the matching `YYYY-Www.md` and must not be updated or counted as parallel weeklies.

Weekly maintenance follows [`WEEKLY_SOP.md`](../WEEKLY_SOP.md).

> **周日不是清空，周一不是重启。**

## Monthly / 每月

Canonical path:

```text
monthly/YYYY/YYYY-MM.md
```

- [`2026-08`](./monthly/2026/2026-08.md) — **OPEN checkpoint through 30 Aug**

The repository was founded on 7 August 2026. August 1–6 are not observatory-native run history.

The August monthly record cannot become `CLOSED` until the real 31 August observation exists. W36 will intersect August only on 31 August and must be treated as partial monthly context.

Monthly maintenance follows [`MONTHLY_SOP.md`](../MONTHLY_SOP.md).

## Canonicality / 规范记录优先级

When records appear to overlap, interpret them in this order:

```text
exact-day integrated daily = atomic record for that observation day
canonical YYYY-Www.md     = weekly settlement
canonical YYYY-MM.md      = monthly settlement / checkpoint
legacy progress snapshot  = historical supplement only
```

Later synthesis does not rewrite what was known on an earlier day; explicit corrections explain changes instead.

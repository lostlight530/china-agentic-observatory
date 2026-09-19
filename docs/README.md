# Presentation Layer / 展示层

本目录是 `china-agentic-observatory` 的**只读 Web 投影层**。

它不创建第二套研究数据库，也不拥有 Daily、Weekly、Monthly、Source Registry、Watchlist、C1–C8、precise-object lifecycle、证据类别或 correction 状态。

## Projection contract

本仓 authority 保持：

```text
current merged main + current observatory contract
> source registry / precise-object schema / maturity rules
> watchlist + canonical Weekly
> latest Daily + relevant history
> current official Chinese primary sources
> reliable supplement
> historical reports
> this presentation layer
```

前端可以投影最新 repository-native observation date、owning Weekly/Monthly 当前状态、最新 Daily pack 的 C1–C8 bounded handoff、开放 Watchlist、Source Registry 已收录对象与 Twin Observatory 同层比较入口，并把每个投影表面链接回仓库源文件。

前端不得从 current-state page 反推未记录 transition time，不得把 drafting/review/approved/published/in-force 合并成一个状态，不得从对象标题推断条款级语义、implementation、conformance 或 adoption，不得对 China/Global 排名，不得写回研究表面，也不得把渲染或抓取成功当成 scientific validity / formal mapping。

任何 canonical source 无法读取时，界面显示 `UNAVAILABLE`，不补造状态。

## Implementation

站点使用无依赖静态 HTML/CSS/JavaScript。页面加载时读取公开 `main` 的 canonical Markdown，仅生成 bounded projection。

本展示层不要求新增仓库自定义 GitHub Actions workflow。若使用 GitHub Pages，预期 publishing source 为 `main` + `/docs`；Pages Settings 属于发布配置，与研究 truth 分离。

## Accessibility

使用原生 HTML landmarks / table semantics、可见键盘 focus、系统 light/dark preference 与 `prefers-reduced-motion`。证据和 lifecycle 状态同时保留文本标签，不依赖颜色单独传达含义。

## Visual identity

视觉语言不继承旧 Welcome Portal 的 Google 配色，也不模仿 AI 厂商产品页。界面语法来自本项目自身：precise object、institutional level、lifecycle state、observation date、source lineage、uncertainty 与 reconciliation。

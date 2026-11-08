# Hi，我是 YIbaikaishui 👋

主要做 **Agent 系统** 和 **网络安全工具**

---

## 🛡️ 安全 · exposur

**面向 AI Agent 的 Web 供给面发现引擎**（Go 1.23+，MIT）

📦 **[github.com/YIbaikaishui/exposur](https://github.com/YIbaikaishui/exposur)**

不是又一个比词表、比速度的目录扫描器——那条赛道社区已经卷了很多年。exposur 换了个角度：

- 一次 `discover` 返回目标的**完整暴露画像**，而不是一堆路径列表
- 内置约 130 条**高价值模式**（VCS 泄露 / 配置 / API 规范 / 调试台 / 备份），每条都带命中判据，宁缺毋滥
- 每条发现输出 `severity / confidence / evidence / next_steps`——**Agent 拿到就能直接决策下一步**
- 面向机器的输出：JSON Lines 打到 stdout，管道即用（`| jq`、直接喂给 agent）

<sub>Go · 并发扫描 · JSON Lines 输出契约 · Linux / macOS / Windows</sub>

> 仅限**你拥有合法授权**的目标使用（授权渗透、自有资产盘点）。未授权目标一律禁止。

---

## 🎡 游乐场

工作之外写着玩的东西，不揣着当作品集。

- **[潮汐场 TIDAL ARENA](https://yibaikaishui.github.io/tidal-arena/)** — 8 万人专业足球场三维演示，纯前端 WebGL。
  能第一人称漫游、做疏散演练、收集徽章。默认轻量模式，核显也打得开。

---

<p align="center"><sub>📫 聊 Agent 设计或安全工具，欢迎开 issue</sub></p>

# Hi，我是 YIbaikaishui 👋

做前端与三维可视化，也写 Python / Rust 的工程工具。习惯把「看起来只是张效果图」的东西做成**能真的点开、真的能玩**的作品。

---

## 🏟️ 潮汐场 TIDAL ARENA

**8 万人专业足球场 · 纯前端 WebGL 三维演示**

[![潮汐场 TIDAL ARENA 黄昏视角](https://yibaikaishui.github.io/tidal-arena/docs/images/cover.jpg)](https://yibaikaishui.github.io/tidal-arena/)

▶️ **[在线直接玩 →](https://yibaikaishui.github.io/tidal-arena/)** ｜ 📦 **[源码](https://github.com/YIbaikaishui/tidal-arena)**

- **8 万座席**逐排逐区程序化生成，容量统计、疏散演练、HUD 全部读同一份数据源，不会各说各话
- **鞍面悬浮屋盖 + 四潮八柱**，昼夜三种光照预设平滑过渡
- 一套真能玩的任务系统：第一人称漫游 → 疏散演练 → 收集徽章 → 建筑洞察图鉴
- **零后端、零外部资源**：three.js 与字体全部本地化，纹理全部 Canvas 程序化生成
- **默认轻量模式**，核显也能流畅打开；加 `?full=1` 看完整泛光效果

| 按键 | 作用 |
|---|---|
| `F` | 第一人称漫游（跟着青色光柱走，走近自动完成目标） |
| `P` / `H` / `C` | 导览机位 / 操作说明 / 照片模式 |
| `Shift` + `P` | 性能诊断面板（GPU、像素比、帧率、绘制量） |

<sub>three.js · 原生 ES Module + importmap · esbuild · GitHub Pages</sub>

---

## 🧩 FastAPI 工程工具链

一套「CLI + 多种布局模板」的脚手架组合，`pip install fastgen-cli` 即可用。

| 项目 | 说明 |
|---|---|
| [**fastgen-cli**](https://github.com/YIbaikaishui/fastgen-cli) | 用 Rust 写的 FastAPI 模块管理器，nest-cli 风格的 `make module` |
| [fastgen-layout-basic](https://github.com/YIbaikaishui/fastgen-layout-basic) | 最小 src 布局起步模板 |
| [fastgen-layout-advanced](https://github.com/YIbaikaishui/fastgen-layout-advanced) | 垂直切片 + 自动维护 registry + 异步 SQLAlchemy 2.0 + Alembic |
| [fastgen-layout-auth](https://github.com/YIbaikaishui/fastgen-layout-auth) | 带 JWT 登录注册、bcrypt 加密的起步模板 |

<sub>Rust（CLI）· Python · FastAPI · SQLAlchemy 2.0 · Alembic · pytest</sub>

---

<p align="center"><sub>📫 想聊三维可视化、WebGL 性能优化或脚手架设计，欢迎开 issue</sub></p>

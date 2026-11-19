### 你好，我是 Ethan 👋

**专注打造「本地优先 · 零冗余依赖 · 边界可控」的 AI Agent 基础设施与效率工具。**  
*Building local-first, zero-bloat AI agent infrastructure & verifiable developer tools.*

拒绝臃肿黑盒与破坏性魔改，习惯用平台原生能力（`Node 24+ / SQLite / SwiftUI`）打磨轻量、可控、开箱即跑的工程工具。

---

### 🔥 开源代表项目 / Featured Projects

| 项目 | 定位 | 解决什么真实痛点 | 核心技术 |
| :--- | :--- | :--- | :--- |
| **[🏰 BastionCC（棱堡）](https://github.com/liangsiweiethan-wq/bastion-cc)** | AI Agent 远程工作台 · `v0.1.0` | 用反代 API 接第三方客户端容易打穿 Prompt Cache、几轮烧完 Claude Pro 额度；纯 SSH 又缺现代 UI。BastionCC 让服务端原生直呼 `claude --resume` 稳保高缓存命中率，外层配齐 Electron 桌面端、零依赖 Web 控制台（自动 SSE 实时流）、6 位配对码与多账号隔离仓。 | `TypeScript` · `Node 24` · `SQLite` · `Electron` |
| **[🛠️ dsh-forge](https://github.com/liangsiweiethan-wq/dsh-forge)** | 跨宿主 Prompt 与补丁编译器 | 多套 AI 编程环境提示词与宿主补丁碎片化、更新易碎。以零运行时依赖的管道编译与版本门控声明式补丁统一管理 6 套主流 Agent 环境，自带三阶段验证与时间戳回滚机制。 | `JavaScript` · `Node.js` · `Zero-Deps` |
| **📚 LiteratureSearch** | 本地优先 PDF 文献工作台 *(整理发布中 / Preparing for release)* | 科研/长文档检索卡顿、摘录无法一键回跳原页。纯本地 macOS 原生应用，毫秒级全文检索并精准跳回 PDF 原始页码与高亮片段。 | `Swift` · `SwiftUI` · `PDFKit` · `SQLite FTS5` |

---

### ⚙️ 工程原则 / Engineering Principles

- **原生优先，拒绝脆性魔改** — 直接基于官方 CLI `--resume`、系统原生 SDK 与浏览器标准构建，不靠拆包或重拼报文破坏上游兼容性。
- **控制 / 正文 / 执行 三面隔离** — 状态事件日志与加密正文（`AES-256-GCM`）物理分离，远端执行器采用反向轮询、不暴露入站端口。
- **发布即门禁** — 公开仓库标配自动化单元测试 / Socket E2E、CI 类型检查以及防隐私与密钥误提交的静态/Git 历史扫描门禁。

---

### 🧰 核心技术栈 / Core Stack

`TypeScript` · `Node.js 24+` · `Python` · `Swift / SwiftUI` · `SQLite (FTS5 / WAL)` · `Electron` · `Docker` · `Linux / nftables`

---

### 📣 欢迎体验与交流 / Connect

- 欢迎到各仓库试跑本地体验模式（自带 `Mock` 适配器，无需账号 60 秒可跑通），觉得思路有启发欢迎点个 **Star ⭐** 或在 **Issues** 交流自建经验与改进建议！
- *Star if these tools help your workflow — feedback, bug reports, and PRs are always welcome in Issues.*

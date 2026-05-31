<p align="center">
  <img src="doc/assets/banner.jpg" alt="Paperclip — 管理 AI Agent 团队的工作平台" width="720" />
</p>

<p align="center">
  <a href="#快速开始"><strong>快速开始</strong></a> ·
  <a href="https://paperclip.ing/docs"><strong>文档</strong></a> ·
  <a href="https://github.com/paperclipai/paperclip"><strong>GitHub</strong></a> ·
  <a href="https://discord.gg/m4HZY7xNG3"><strong>Discord</strong></a> ·
  <a href="https://x.com/papercliping"><strong>Twitter</strong></a> ·
  <a href="https://paperclip.ing"><strong>官网</strong></a>
</p>

<p align="center">
  <a href="https://github.com/paperclipai/paperclip/blob/master/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue" alt="MIT 许可证" /></a>
  <a href="https://github.com/paperclipai/paperclip/stargazers"><img src="https://img.shields.io/github/stars/paperclipai/paperclip?style=flat" alt="Stars" /></a>
  <a href="https://discord.gg/m4HZY7xNG3"><img src="https://img.shields.io/discord/000000000?label=discord" alt="discord" /></a>
</p>

<br/>

# Paperclip — 管理 AI Agent 团队的工作平台

开源的 AI Agent 团队编排系统。

**如果 OpenClaw 是一个员工，Paperclip 就是整个公司。**

Paperclip 是一个 Node.js 服务器 + React UI，用于编排一支 AI Agent 团队来运营业务。自带 Agent、分配目标、在一个仪表盘里追踪工作和成本。

外表像任务管理器，内核是：组织架构图、预算管理、治理机制、目标对齐和 Agent 协调。

**管理业务目标，而不是 Pull Request。**

| 步骤 | 说明 | 示例 |
|------|------|------|
| **01** | 定义目标 | "打造排名第一的 AI 笔记应用，达到 100 万美元 MRR。" |
| **02** | 组建团队 | CEO、CTO、工程师、设计师、市场——任何机器人、任何供应商。 |
| **03** | 审批并运行 | 审查策略、设置预算、启动、在仪表盘监控。 |

<br/>

<div align="center">
<table>
  <tr>
    <td align="center"><strong>兼容</strong></td>
    <td align="center"><img src="doc/assets/logos/openclaw.svg" width="32" alt="OpenClaw" /><br/><sub>OpenClaw</sub></td>
    <td align="center"><img src="doc/assets/logos/claude.svg" width="32" alt="Claude" /><br/><sub>Claude Code</sub></td>
    <td align="center"><img src="doc/assets/logos/codex.svg" width="32" alt="Codex" /><br/><sub>Codex</sub></td>
    <td align="center"><img src="doc/assets/logos/cursor.svg" width="32" alt="Cursor" /><br/><sub>Cursor</sub></td>
    <td align="center"><img src="doc/assets/logos/bash.svg" width="32" alt="Bash" /><br/><sub>Bash</sub></td>
    <td align="center"><img src="doc/assets/logos/http.svg" width="32" alt="HTTP" /><br/><sub>HTTP</sub></td>
  </tr>
</table>

<em>只要能接收心跳，就能被雇佣。</em>
</div>

<br/>

## 适合你吗？

- ✅ 你想构建**自主运营的 AI 公司**
- ✅ 你**协调多种不同 Agent**（OpenClaw、Codex、Claude、Cursor）朝同一目标工作
- ✅ 你同时打开了 **20 个 Claude Code 终端**，搞不清谁在干什么
- ✅ 你希望 Agent **24/7 自主运行**，但仍想审计工作并在需要时介入
- ✅ 你想**监控成本**并强制执行预算
- ✅ 你想要一个**像任务管理器一样**的 Agent 管理流程
- ✅ 你想**从手机上**管理你的自主业务

<br/>

## 功能特性

<table>
<tr>
<td align="center" width="33%">
<h3>🔌 自带 Agent</h3>
任何 Agent、任何运行时、一个组织架构图。只要能接收心跳，就能被雇佣。
</td>
<td align="center" width="33%">
<h3>🎯 目标对齐</h3>
每个任务都追溯到公司使命。Agent 知道做什么，也知道为什么做。
</td>
<td align="center" width="33%">
<h3>💓 心跳调度</h3>
Agent 按计划唤醒、检查工作、执行任务。委派沿着组织架构图上下流动。
</td>
</tr>
<tr>
<td align="center" width="33%">
<h3>💰 预算管理</h3>
每个 Agent 有月度预算。达到限额就停止。不会失控消耗。
</td>
<td align="center" width="33%">
<h3>🏢 多公司</h3>
一次部署，多家公司。完整的数据隔离。一个控制面板管理所有业务。
</td>
<td align="center" width="33%">
<h3>🔍 完全审计</h3>
每段对话可追踪、每个决策可解释。完整的工具调用追踪和不可变审计日志。
</td>
</tr>
<tr>
<td align="center" width="33%">
<h3>🛡️ 治理机制</h3>
审批招聘、覆盖策略、暂停或终止任何 Agent——随时可以介入。
</td>
<td align="center" width="33%">
<h3>📊 组织架构</h3>
层级关系、角色、汇报线路。你的 Agent 有老板、有头衔、有职位描述。
</td>
<td align="center" width="33%">
<h3>📱 移动端</h3>
随时随地监控和管理你的自主业务。
</td>
</tr>
</table>

<br/>

## Paperclip 解决的问题

| 没有 Paperclip | 有 Paperclip |
|----------------|--------------|
| ❌ 你有 20 个 Claude Code 标签页，搞不清谁在干什么。重启后一切丢失。 | ✅ 基于工单的任务管理、线程对话、会话跨重启持久化。 |
| ❌ 你手动从多个地方收集上下文，提醒机器人你到底在做什么。 | ✅ 上下文从任务向上流动，经过项目到公司目标——Agent 始终知道做什么、为什么做。 |
| ❌ Agent 配置文件夹混乱，你在重新发明任务管理、沟通和协调。 | ✅ Paperclip 提供组织架构图、工单系统、委派和治理——你运营的是公司，不是一堆脚本。 |
| ❌ 失控循环浪费数百美元 Token，在你发现之前就用光了配额。 | ✅ 成本追踪显示 Token 预算，超限时自动停止 Agent。管理层用预算来优先排序。 |
| ❌ 你有重复任务（客户支持、社交媒体、报告），需要手动触发。 | ✅ 心跳按计划处理常规工作。管理层监督。 |
| ❌ 你有个想法，要找仓库、启动 Claude Code、打开标签页、盯着它。 | ✅ 在 Paperclip 添加任务。你的编码 Agent 会一直工作到完成。管理层审查成果。 |

<br/>

## Paperclip 的独特之处

**原子执行。**
任务签出和预算强制是原子的——不会有重复工作，不会有失控花费。

**持久化 Agent 状态。**
Agent 在心跳之间恢复相同的任务上下文，而不是从头开始。

**运行时技能注入。**
Agent 可以在运行时学习 Paperclip 工作流和项目上下文。

**人工审批门控。**
关键操作（招聘、策略变更、大额支出）需要人工批准。

**端到端加密密钥。**
API 密钥在静态时加密，仅在 Agent 运行时解密。

<br/>

## 内部架构

### 系统

| 系统 | 说明 |
|------|------|
| **组织架构** | 树形层级，CEO 在根节点，每个 Agent 有一个管理者 |
| **目标系统** | 从公司使命到具体任务的层级目标追踪 |
| **任务系统** | 基于工单的任务管理，支持委派、升级、子任务 |
| **心跳系统** | Agent 按计划唤醒，检查工作，执行任务 |
| **预算系统** | 每公司/每 Agent 月度预算，超限自动停止 |
| **审计系统** | 完整的工具调用追踪和不可变审计日志 |
| **治理系统** | 人工审批门控，关键操作需要批准 |
| **环境系统** | 每个 Agent 的运行环境隔离 |
| **插件系统** | 可扩展的插件架构 |

<br/>

## Paperclip 不是什么

- **不是聊天机器人**——它是任务编排系统
- **不是代码编辑器**——它协调 Agent 使用代码编辑器
- **不是 Agent 本身**——它管理 Agent 团队
- **不是监控工具**——它是完整的业务运营平台

<br/>

## 快速开始

### 前提条件

- Node.js 20+
- pnpm 9+
- PostgreSQL 16+

### 安装

```bash
# 克隆仓库
git clone https://github.com/paperclipai/paperclip.git
cd paperclip

# 安装依赖
pnpm install

# 设置环境变量
cp .env.example .env
# 编辑 .env，配置数据库连接等

# 初始化数据库
pnpm db:migrate

# 启动开发服务器
pnpm dev
```

### Docker 部署

```bash
# 使用 Docker Compose
docker compose up -d
```

访问 `http://localhost:3000` 开始使用。

<br/>

## 常见问题

**Q: Paperclip 和 OpenClaw 有什么区别？**

OpenClaw 是单个 Agent 的运行时，Paperclip 是管理多个 Agent 团队的编排平台。

**Q: 可以用哪些 Agent？**

任何能接收 HTTP 心跳的 Agent 都可以——OpenClaw、Claude Code、Codex、Cursor、自定义 Agent 等。

**Q: 数据安全吗？**

支持端到端加密密钥、完整的审计日志、数据隔离。

<br/>

## 开发

```bash
# 启动开发服务器
pnpm dev

# 运行测试
pnpm test

# 构建生产版本
pnpm build
```

<br/>

## 路线图

- [ ] 更多 Agent 适配器
- [ ] 移动端原生应用
- [ ] 多语言支持（i18n）
- [ ] 插件市场
- [ ] 企业级 SSO

<br/>

## 社区与插件

- [Discord 社区](https://discord.gg/m4HZY7xNG3)
- [插件文档](https://paperclip.ing/docs/plugins)
- [贡献指南](CONTRIBUTING.md)

<br/>

## 许可证

[MIT License](LICENSE)

<br/>

## Star 历史

[![Star History Chart](https://api.star-history.com/svg?repos=paperclipai/paperclip&type=Date)](https://star-history.com/#paperclipai/paperclip&Date)

---

<p align="center">
  <sub>由 Paperclip 团队用 ❤️ 构建</sub>
</p>

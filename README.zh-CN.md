# 你好，我是 nanhudev 👋

**AI-native 开发者 · Agent 系统 · 本地 AI · 创意工具**

**[English](README.md) · [中文](README.zh-CN.md)**

我在做 AI-native 软件，背后其实只有一条反复出现的主线：

> **让模型负责推理，让工具负责执行，让整个系统保持可观察、可验证。**

工作覆盖 Agent 编排、本地 AI 运行时、创意工具、交互系统与可复现研究。

相比"给传统软件加一个 AI 功能"，我更在意的是：
**如果从架构设计的第一天起，就默认模型和 Agent 是系统的一部分，会发生什么。**

---

## 代表项目

### 🧠 Agent2LLM

**可组合的 Brain × Harness 协作框架。**

推理前端和执行环境通常被锁在同一个产品里。Agent2LLM 把它们拆开，让你可以自由配对——
ChatGPT 或 Claude 做 *大脑*，WorkBuddy / Codex / Cursor / Claude Code / DeepSeek Harness 做 *手*。

```text
Brain   →  推理 · 评审 · 意图
              ↓
          Agent2LLM
              ↓
Harness →  执行 · 工作区变更
```

原则只有一句：**大脑决定，手脚执行。**

CLI 优先、适配器优先、本地优先。 → [`nanhudev/agent2llm`](https://github.com/nanhudev/agent2llm)

---

### 🧊 Chat2Blend

**用网页 LLM 当 3D 大脑，让 Blender 执行。**

Chat2Blend 捕获 ChatGPT 等网页 LLM 流式生成的 Blender Python，
直接送进一个可见、已经打开的 Blender 实例。

```text
网页 LLM → 流式 Python → 浏览器扩展 → 本地桥接 → Blender 插件 → 3D 模型
```

不用手动复制粘贴。不需要 API Key。也不需要第二个 Agent 把同一段 `bpy` 代码重写一遍。
→ [`nanhudev/chat2blend`](https://github.com/nanhudev/chat2blend)

---

### 🐾 AgentPet

**让 Coding Agent 变 observable 的桌面伙伴。**

AgentPet 观察你本地的 Coding Agent 实际在做什么，把真实的开发事件翻译成可见的桌面行为——
会话、文件变更、git 提交、测试结果、任务状态。

它**刻意只做观察者，不做控制器**。
目的不是去驱动 Agent，而是让它的工作变得可读。

→ [`nanhudev/AgentPet`](https://github.com/nanhudev/AgentPet)

---

### 🎙 Local Voice Companion

**本地优先的语音 AI 运行时。**

语音识别、模型推理、语音合成都可以跑在你自己的机器上，通过 HTTP / WebSocket 暴露出去。

可以用作个人语音助手、游戏对话后端、AI 角色运行时，或者其他 Agent 的语音层。
→ [`nanhudev/local-voice-companion`](https://github.com/nanhudev/local-voice-companion)

---

### 🎬 HTML Video Workflow

**一句 prompt 进去，一个完整 MP4 出来。**

Agentic 视频运行时，把整条生产链路串起来：

```text
调研 → 脚本 → 分镜 → 渲染 → 配音 → 合成 → 质检 → MP4
```

支持 CLI、Python SDK、REST API、MCP 和本地 Studio 界面。
→ [`nanhudev/html-video-workflow`](https://github.com/nanhudev/html-video-workflow)

---

### 🧬 Cognitive OS

**让"长期理解一个人"变成基础设施。**

大多数 AI 产品里的"记忆"只是更长的聊天记录。Cognitive OS 把它分层拆开：

- 情景记忆
- 语义知识
- 行为模式
- 身份假设
- 反思
- 预测

它想回答的是：系统能否随时间建立对一个**稳定、有证据支撑**的个体模型——
每一条判断都带着支撑它的证据。
→ [`nanhudev/cognitive-os`](https://github.com/nanhudev/cognitive-os)

---

## 应用 AI 与研究

### 📚 AI Teacher Coach

**面向高中语文教师的 AI 备课与课堂训练工具。**

一个课题可以产出：教研分析、教案、课件、虚拟学生课堂模拟、教学评价。

设计上刻意把 **LLM 推理、教学硬约束、视觉模板** 三者分开——
而不是让一个模型同时干三件事、每件都做到 70 分。
**已上线：[bubbleapp.cn/aiteacher](https://bubbleapp.cn/aiteacher/)**

→ [`nanhudev/ai-teacher-coach`](https://github.com/nanhudev/ai-teacher-coach)

### 🎮 Novel2Game AI

**把叙事文本变成可持续的交互世界。**

从小说中抽取人物、地点、物品与关系，维护一份权威世界状态，
同时允许玩家用自然语言行动。

```text
小说 → 世界抽取 → 持久状态 → 玩家行动 → AI 裁决 → 状态更新
```

→ [`nanhudev/novel2game-ai`](https://github.com/nanhudev/novel2game-ai)

### 📈 TradeScope AI

**可解释的加密市场研究终端。**

围绕可溯源数据、确定性指标和显式的模型风险边界构建——
它会告诉你哪些是实测、哪些是推断、哪些是模型在猜。
→ [`nanhudev/tradescope-ai`](https://github.com/nanhudev/tradescope-ai)

### 🔬 Quant Research Lab

**可复现的量化研究沙盒。**

滚动前进模拟，含交易成本、杠杆、强平与样本外验证。
每个结果都是用来被重跑的，不是用来被欣赏的。
→ [`nanhudev/quant-research-lab`](https://github.com/nanhudev/quant-research-lab)

### 🧮 Negative Collatz Boundary

**大规模数值验证，并且可复现。**

对负 Collatz 轨迹做穷举式 OpenCL 实验，覆盖 10¹⁰ 以内全部起点——
已发现最长轨迹 **1,062 步**，起点 **−9,177,118,737**。
附带 LaTeX 论文与复核所需的全部数据。
→ [`nanhudev/negative-collatz-boundary-1e10`](https://github.com/nanhudev/negative-collatz-boundary-1e10)

---

## 我在探索什么

大部分工作最后都回到三个问题：

**1. 多个 AI 系统应该如何协作？**
不是一个巨型 Agent 包办一切，而是不同系统有明确的角色、能力和边界。

**2. 如何让 AI 系统保持可观察？**
真实的状态、真实的文件、真实的 diff、真实的执行、显式的不确定性。
这比一个看起来很聪明的 Demo 更重要。

**3. 当 AI 成为 runtime 的一部分，什么会变？**
从第一天就围绕模型和 Agent 设计的软件，
而不是先有传统软件、之后再挂一个聊天框。

当前重点：**Agent 基础设施** · **本地优先 AI** · **创意 AI** · **人机控制权边界**

---

## 技术栈

| 层 | 工具 |
|---|---|
| 语言 | Python · TypeScript · JavaScript |
| 应用 | FastAPI · React · Next.js · Node.js |
| AI | LLM API · RAG · MCP · Agent 工作流 · 本地模型 |
| 创意 | Blender · Godot · FFmpeg · ComfyUI |
| 基础设施 | PostgreSQL · pgvector · SQLite · Docker |

---

## 原则

- **先有证据，再有结论。**
- **重大决策的控制权留在人手里。**
- **系统必须说明什么是真实的、什么是推断的、什么是模拟的。**
- **可复现性优先于看起来厉害的 Demo。**
- **AI 应该与工具协作，而不是假装取代工具。**

---

## 关于

**余宣均 / Xuanjun Yu** — 澳门大学。
BubbleLab 创始人 · [bubbleapp.cn](https://bubbleapp.cn)

> 我构建那些"说法可以被验证"的 AI 系统。

---

<sub>中英文是同一页的两个平行版本，不是把其中一种附在另一种下面。</sub>

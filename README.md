# Hi, I'm nanhudev 👋

**AI-native Builder · Agent Systems · Local-first AI · Creative Tools**

**[English](README.md) · [中文](README.zh-CN.md)**

I build AI-native software around one recurring idea:

> **Let models reason, let tools execute, and keep the whole system observable and verifiable.**

My work spans agent orchestration, local AI runtimes, creative tooling,
interactive systems and reproducible research.

I care less about "adding AI to an app" and more about designing software
where models and agents are part of the architecture from day one.

---

## Featured Projects

### 🧠 Agent2LLM

**Composable Brain × Harness infrastructure for coding agents.**

Reasoning frontends and execution harnesses are usually locked inside one
product. Agent2LLM separates them and lets you pair them freely — ChatGPT or
Claude as the *brain*, WorkBuddy / Codex / Cursor / Claude Code / DeepSeek
Harness as the *hands*.

```text
Brain   →  reasoning · review · intent
              ↓
          Agent2LLM
              ↓
Harness →  execution · workspace mutation
```

The core principle is simple: **the Brain decides, the Harness acts.**

CLI-first, adapter-first, local-first. → [`nanhudev/agent2llm`](https://github.com/nanhudev/agent2llm)

---

### 🧊 Chat2Blend

**Use a web LLM as the 3D brain. Let Blender execute.**

Chat2Blend captures Blender Python streamed out of ChatGPT or any other web
LLM and pipes it straight into a visible, already-open Blender instance.

```text
Web LLM → Streaming Python → Browser Extension → Local Bridge → Blender Add-on → 3D Model
```

No manual copy/paste. No API key. No second coding agent rewriting the same
`bpy` code. → [`nanhudev/chat2blend`](https://github.com/nanhudev/chat2blend)

---

### 🐾 AgentPet

**A desktop companion that makes coding agents observable.**

AgentPet watches what your local coding agents are *actually* doing and
translates real development events into visible desktop behaviour — sessions,
file changes, git commits, test results, task state.

It deliberately stays an **observer, not a controller**.
The point is not to drive the agent, but to make its work legible.

→ [`nanhudev/AgentPet`](https://github.com/nanhudev/AgentPet)

---

### 🎙 Local Voice Companion

**A local-first voice runtime for AI applications.**

Speech recognition, model reasoning and text-to-speech can all run on your own
machine, exposed over HTTP / WebSocket.

Usable as a personal voice assistant, a game dialogue backend, an AI character
runtime, or the voice layer of another agent.
→ [`nanhudev/local-voice-companion`](https://github.com/nanhudev/local-voice-companion)

---

### 🎬 HTML Video Workflow

**One prompt in. A complete MP4 out.**

An agentic video runtime that chains the whole production path:

```text
Research → Script → Storyboard → Render → Voice → Composition → QC → MP4
```

Available through CLI, Python SDK, REST API, MCP and a local Studio UI.
→ [`nanhudev/html-video-workflow`](https://github.com/nanhudev/html-video-workflow)

---

### 🧬 Cognitive OS

**Long-term machine understanding of a person — as infrastructure.**

Most "memory" in AI products is just a longer chat history. Cognitive OS
separates the layers instead:

- episodic memory
- semantic knowledge
- behavioural patterns
- identity hypotheses
- reflection
- prediction

It asks whether a system can build a *stable, evidence-backed* model of an
individual over time — where every claim carries its supporting evidence.
→ [`nanhudev/cognitive-os`](https://github.com/nanhudev/cognitive-os)

---

## Applied AI & Research

### 📚 AI Teacher Coach

**AI lesson preparation and classroom simulation for Chinese-language teachers.**

One topic produces teaching analysis, lesson plans, presentation slides, a
virtual-student classroom simulation and a teaching evaluation.

The design deliberately splits LLM reasoning, hard teaching constraints and
visual templates — rather than asking one model to do all three and average
70% on each. **Live at [bubbleapp.cn/aiteacher](https://bubbleapp.cn/aiteacher/).**

→ [`nanhudev/ai-teacher-coach`](https://github.com/nanhudev/ai-teacher-coach)

### 🎮 Novel2Game AI

**Turn narrative text into a persistent interactive world.**

Extracts characters, locations, objects and relationships from fiction, then
maintains an authoritative world state while the player acts in natural language.

```text
Novel → World Extraction → Persistent State → Player Action → AI Adjudication → State Update
```

→ [`nanhudev/novel2game-ai`](https://github.com/nanhudev/novel2game-ai)

### 📈 TradeScope AI

**An explainable crypto research terminal.**

Built around traceable data, deterministic indicators and explicit model-risk
boundaries — it shows what is measured, what is inferred, and where the model
is guessing. → [`nanhudev/tradescope-ai`](https://github.com/nanhudev/tradescope-ai)

### 🔬 Quant Research Lab

**A reproducible quantitative research sandbox.**

Walk-forward simulation with transaction costs, leverage, liquidation and
out-of-sample validation. Every result is meant to be re-run, not admired.
→ [`nanhudev/quant-research-lab`](https://github.com/nanhudev/quant-research-lab)

### 🧮 Negative Collatz Boundary

**Large-scale numerical verification, done reproducibly.**

An exhaustive OpenCL experiment over negative Collatz trajectories for all
starts through 10¹⁰ — longest trajectory found: **1,062 steps**, at start
**−9,177,118,737**. Ships with the LaTeX paper and the data needed to check it.
→ [`nanhudev/negative-collatz-boundary-1e10`](https://github.com/nanhudev/negative-collatz-boundary-1e10)

---

## What I'm Exploring

Most of my work comes back to three questions:

**1. How should multiple AI systems cooperate?**
Not one giant agent doing everything — different systems with explicit roles,
capabilities and boundaries.

**2. How do we keep AI systems observable?**
Real state, real files, real diffs, real execution, explicit uncertainty.
That matters more to me than a convincing-looking demo.

**3. What changes when AI becomes part of the runtime?**
Software designed around models and agents from day one, rather than
traditional software with a chatbot bolted on later.

Current focus: **agent infrastructure** · **local-first AI** · **creative AI**
· **human–AI control boundaries**

---

## Stack

| Layer | Tools |
|---|---|
| Languages | Python · TypeScript · JavaScript |
| Application | FastAPI · React · Next.js · Node.js |
| AI | LLM APIs · RAG · MCP · Agent workflows · Local models |
| Creative | Blender · Godot · FFmpeg · ComfyUI |
| Infrastructure | PostgreSQL · pgvector · SQLite · Docker |

---

## Principles

- **Evidence before claims.**
- **Humans stay in control of consequential decisions.**
- **A system should say what is real, inferred, or simulated.**
- **Reproducibility beats an impressive demo.**
- **AI should cooperate with tools, not pretend to replace them.**

---

## About

**余宣均 / Xuanjun Yu** — University of Macau.
Founder of BubbleLab · [bubbleapp.cn](https://bubbleapp.cn)

> I build AI systems whose claims can be checked.

---

<sub>English and Chinese are parallel versions of the same page, not a translation appended below the other.</sub>

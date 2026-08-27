<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
    <img alt="Automation &amp; AI Agent Engineer" src="assets/header-dark.svg" width="100%">
  </picture>
</p>

<p align="center">
  <img alt="Location" src="https://img.shields.io/badge/Chicago,_IL-open_to_work-2ea043?style=for-the-badge&labelColor=0d1117">
  <img alt="Focus" src="https://img.shields.io/badge/focus-agent_systems-d4a574?style=for-the-badge&labelColor=0d1117">
  <img alt="Since" src="https://img.shields.io/badge/AI--assisted_dev-daily_since_2024-6E56CF?style=for-the-badge&labelColor=0d1117">
</p>

---

I spent three years on a production line watching skilled people do work a computer should be doing. So I built the computer's half. That instinct — **notice the repetitive thing, then remove it** — is the whole job, whether the fix is a hotkey macro or a fleet of agents.

Now I build agent systems and the evaluation harnesses that prove they actually work.

<br>

## What I've built

<table>
<tr>
<td width="50%" valign="top">

### 🛠️ Macro automation tool
**AutoHotkey · Windows · zero dependencies**

I was a data annotation operator on an autonomy pipeline. Spotted a high-volume repetitive sub-task, built the fix on personal time.

A representative task went **~30s → ~6s (3–5x)** at **99.9% accuracy**. Validated with the engineering team, staged for deployment, SOPs and onboarding docs written solo.

</td>
<td width="50%" valign="top">

### 🤖 Multi-agent system
**Python · Node.js · MCP**

Designed, built, and ran **always-on across a home GPU and a VPS, March–June 2026**. Local-first since.

Sub-agent orchestration, MCP tool integration, file-backed shared state, scheduled execution, auth-gated endpoints, and cost-aware model routing that kept marginal cost near zero.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 LLM eval harness
**Python · eval-driven development**

Scores model outputs against a **deterministic oracle** — a hand-written game engine used as a known-correct answer key — plus an LLM-as-judge pattern for outputs with no clean ground truth.

Produces defensible accuracy-vs-latency comparisons across models, prompts, and routing choices. "The AI works" should be a measurement, not a vibe.

</td>
<td width="50%" valign="top">

### ⚡ Real-time desktop overlay
**Rust · public APIs**

Native overlay that pulls live data from public APIs and renders it on-screen in real time.

Low-latency rendering, no interference with the host application. Built to learn a systems language under real constraints rather than on a tutorial.

</td>
</tr>
</table>

<br>

## Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![AutoHotkey](https://img.shields.io/badge/AutoHotkey-334455?style=flat-square)

**AI & agents**

![MCP](https://img.shields.io/badge/MCP-d4a574?style=flat-square&logoColor=black)
![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![LLM Eval](https://img.shields.io/badge/LLM_evaluation-6E56CF?style=flat-square)
![Agent Orchestration](https://img.shields.io/badge/agent_orchestration-6E56CF?style=flat-square)

**Infra & integration**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Zapier](https://img.shields.io/badge/Zapier-FF4F00?style=flat-square&logo=zapier&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=make&logoColor=white)

<br>

<details>
<summary><b>How I work</b></summary>

<br>

- **Notice first, build second.** The bottleneck nobody flagged is worth more than the feature everyone requested.
- **Measure it or don't claim it.** Every number on this page traces to a hand-timed baseline or a scored eval run. Ranges, not headline figures.
- **Ship the boring version.** Zero dependencies beats a clever framework when someone else has to run it at 3am.
- **Write the docs yourself.** A tool nobody can onboard onto is a tool that dies with you.
- **AI-assisted development daily since 2024** — Cursor, then Claude Code. Agent loops, sub-agent orchestration, and persistent state are how I build, not something I read about.

</details>

<details>
<summary><b>Background</b></summary>

<br>

Audio engineering → manufacturing → automation engineering. Not the standard path, and I'd argue that's the point.

Signal processing, latency budgets, and "it has to work live, right now, in front of people" turn out to be the same constraints as real-time systems work. Three years of high-volume production taught me to spot a bottleneck before anyone files a ticket about it.

Currently independent: agent systems, eval harnesses, API integrations, and a technical advisory role with an early-stage product team.

</details>

<br>

---

<p align="center">
  <sub>Most of my repos are private — client work and things still in progress.<br>Happy to walk through code on a call.</sub>
</p>

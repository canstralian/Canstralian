# Canstralian

**Systems builder / operator.**  
Agent infrastructure. Security engineering. Local AI. Edge hardware.

From silicon to cloud. From offense to defense.

## Build

I build systems where **AI agents, security controls, software infrastructure, and hardware meet**.

Current work is centred on:

- **Agent systems** — orchestration, tools, skills, subagents, MCP, evaluation, memory and handoffs
- **Governed autonomy** — policy engines, audit trails, replay, posture adaptation and fail-closed controls
- **Security engineering** — red teaming, OSINT, automated analysis and defensive feedback loops
- **Local AI** — GPU-constrained inference, quantized models and local-first development
- **Edge systems** — Raspberry Pi, ESP32, RF hardware and embedded experimentation
- **Developer infrastructure** — reusable standards, validation, CI/CD and agent-compatible repository architecture

The design goal is not autonomous software for its own sake.

It is **controlled systems that can observe, reason, act, verify and explain what happened.**

```text
signal
  ↓
observe
  ↓
reason
  ↓
policy
  ↓
act
  ↓
verify
  ↓
evidence
  └──────────────→ feedback
```

**Intent is not authority.**  
Automation should be observable.  
Security boundaries should fail closed.  
Agent behaviour should be testable and replayable.

---

## Current Projects

### [Mandare](https://github.com/canstralian/mandare)

Governance-first runtime for agentic systems.

Policy evaluation → posture adaptation → controlled execution → evidence → replay.

Built around the idea that increasingly capable agents need **stronger runtime boundaries**, not simply better prompts.

### [BugBountyOS](https://github.com/canstralian/BugBountyOS)

Modular security operating system for automated bug-bounty workflows.

Reconnaissance, evidence collection and security automation assembled into reproducible pipelines.

### [OSINT MCP Server](https://github.com/canstralian/OSINT-MCP-Server)

MCP tooling for structured OSINT workflows with explicit error handling and guardrails around publicly available information.

### [HydraESP AI Edition](https://github.com/canstralian/HydraESP-AI-Edition)

ESP32-based passive RF edge-agent experimentation bridging embedded hardware, radio telemetry and AI-assisted analysis.

---

## In Development

**Forge** — canonical engineering standards, agent skills, prompts, contracts and repository workflows across Canstralian projects.

**Red Team Forge** — reusable adversarial-review, offensive-security and agent red-team infrastructure.

The objective is to make the intelligence layer **portable**:

```text
             ┌── Claude Code
             ├── Codex
Forge ───────┼── Cursor
             ├── GitHub Copilot
             └── other agent runtimes
```

One canonical engineering model. Thin client adapters. Minimal policy duplication.

---

## Stack

```python
stack = {
    "agents": [
        "MCP",
        "tool calling",
        "skills",
        "subagents",
        "state machines",
        "planner/executor",
        "evaluation",
    ],

    "ai": [
        "local LLMs",
        "llama.cpp",
        "KoboldCpp",
        "PyTorch",
        "Transformers",
        "RAG",
    ],

    "backend": [
        "Python",
        "FastAPI",
        "PostgreSQL",
        "Supabase",
    ],

    "security": [
        "red teaming",
        "OSINT",
        "CodeQL",
        "Semgrep",
        "Bandit",
        "Zero Trust",
    ],

    "edge": [
        "Raspberry Pi",
        "ESP32",
        "RF",
        "embedded systems",
    ],

    "engineering": [
        "pytest",
        "mypy",
        "ruff",
        "GitHub Actions",
        "OpenTelemetry",
    ],

    "environment": [
        "Linux",
        "WSL2",
        "Windows",
        "Docker",
        "Git",
    ],

    "pattern": "governed, observable agent systems",
}
```

---

## Engineering Direction

I'm particularly interested in the boundary between **deterministic software and probabilistic reasoning**.

That means designing systems where LLMs can propose, classify, investigate and reason — while deterministic components retain control over:

**authority → execution → validation → evidence**

The interesting problem isn't:

> How autonomous can the agent become?

It's:

> How capable can the system become without losing control of the loop?

---

## Connect

[GitHub](https://github.com/canstralian) · 📧 rbf.311@gmail.com

---

**Build the loop. Instrument the loop. Attack the loop. Improve the loop.**

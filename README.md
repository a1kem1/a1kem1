<h1 align="center">Aleksandar Stefanović</h1>
<h3 align="center">Founder — ALKEM1 · Constitutional AI Systems</h3>

<p align="center">
  <em>Building verified, offline-first AI operating systems that prove what they did.</em>
</p>

---

### What I'm Building

**ALKEM1 AG1** — Constitutional Agent Runtime

An AI agent that doesn't just execute code — it *proves* it did it safely.

- **Bounded execution loop** with deterministic reviewer (no LLM in the judge)
- **Structured patch synthesis** — focused JSON contracts for surgical code edits
- **Cryptographic evidence chain** — hash-chained ledger, receipts, evidence packs
- **Policy-gated tools** — fail-closed permission system (read_only → workspace_write → shell_guarded)
- **Cognitive self-correction** — retry with LLM replanning when reviewer says RETRY
- **4-runner benchmark arena** — AG1 vs Aider vs OpenCode vs Claude Code, same model, same task

```
Task → Plan → Execute → Review → Ledger → Evidence → Proof
```

**ALKEM1 OS** — Kernel-First Operating Layer

A full-stack OS for AI workflows with 42 invariants, 288K LOC, and zero-trust architecture.

- **5-layer kernel** — crypto → trust → map → runtime → apps
- **NEXUS Dashboard** — 70+ pages, fullscreen launchpad, 3 themes
- **Multi-agent orchestration** — 4-lane dispatch with fencing tokens
- **Contract fabric** — content-addressed schemas, Merkle attestation
- **Blockchain anchor** — Polygon Amoy proof chain

---

### Tech

```
Python · TypeScript · React · FastAPI · Docker · Redis · NATS
Ollama · qwen2.5-coder · deepseek-r1 · tree-sitter
SHA-256 hash chains · Ed25519 attestation · Polygon smart contracts
```

---

### Architecture

```
┌─────────────────────────────────────────┐
│  NEXUS Dashboard (:3690)                │
│  70+ pages · launchpad · 3 themes       │
├─────────────────────────────────────────┤
│  AG1 Runtime                            │
│  plan → execute → review → evidence     │
├─────────────────────────────────────────┤
│  ALKEM1 OS Kernel                       │
│  trust · contracts · invariants · ledger│
├─────────────────────────────────────────┤
│  Multi-Agent Fleet                      │
│  4 lanes · dispatch · claims · fencing  │
└─────────────────────────────────────────┘
```

---

### Results

| Metric | AG1 | Aider | OpenCode | Claude |
|--------|-----|-------|----------|--------|
| Capability | 67% | 100% | 100% | 67% |
| Safety | 100% | 87% | 100% | 100% |
| Governance | 100% | 0% | 0% | 0% |
| **Overall** | **81** | 70 | 60 | 43 |

AG1 wins overall because it's the only system that proves what it did.

---

### Repos

| Project | What |
|---------|------|
| [alkem1-ag1](https://github.com/alkem1-lab/alkem1-ag1) | Constitutional agent runtime — 213 tests |
| [alkem1_os](https://github.com/alkem1-lab/alkem1_os) | Kernel-first OS — 288K LOC, 42 invariants |
| [alkem1-xck](https://github.com/alkem1-lab/alkem1-xck) | Security toolkit |
| [alkem1-trading](https://github.com/alkem1-lab/alkem1-trading) | Autonomous trading system |

---

<p align="center">
  <a href="mailto:alek@alkem1.com">alek@alkem1.com</a> · 
  <a href="https://www.instagram.com/alkem1ag1/">Instagram</a> · 
  <a href="https://www.behance.net/stefanovicaleksandar">Behance</a> ·
  Geneva, Switzerland
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=alkem1&color=orange&style=flat-square" alt="views"/>
</p>

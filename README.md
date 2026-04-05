<h1 align="center">Aleksandar Stefanović</h1>
<h3 align="center">Founder — ALKEM1 · Constitutional AI Systems</h3>

<p align="center">
  <em>Building verified, offline-first AI operating systems that prove what they did.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SYSTEM-ONLINE-22C55E?style=flat-square&labelColor=181A20" />
  <img src="https://img.shields.io/badge/KERNEL-v0.8.0-3B82F6?style=flat-square&labelColor=181A20" />
  <img src="https://img.shields.io/badge/AG1-213_TESTS-F97316?style=flat-square&labelColor=181A20" />
  <img src="https://img.shields.io/badge/NEXUS-70+_PAGES-A855F7?style=flat-square&labelColor=181A20" />
  <img src="https://img.shields.io/badge/NODE-GENEVA__CH-6B7280?style=flat-square&labelColor=181A20" />
</p>

---

### AG1 — Constitutional Agent Runtime

An AI agent that doesn't just execute code — it *proves* it did it safely.

- **Bounded execution loop** — deterministic reviewer, no LLM in the judge
- **Structured patch synthesis** — focused JSON contracts for surgical code edits
- **5-level heuristic matching** — exact → normalized → fuzzy → indent-flexible → block-anchor
- **Cryptographic evidence chain** — hash-chained ledger, receipts, evidence packs
- **Cognitive self-correction** — retry with LLM replanning when reviewer says RETRY
- **4-runner benchmark arena** — AG1 vs Aider vs OpenCode vs Claude Code

### ALKEM1 OS — Kernel-First Operating Layer

288K LOC, 42 invariants, zero-trust architecture.

- **5-layer kernel** — crypto → trust → map → runtime → apps
- **Multi-agent orchestration** — 4-lane dispatch with fencing tokens
- **NEXUS Dashboard** — 70+ pages, fullscreen launchpad, 3 themes
- **Blockchain anchor** — Polygon Amoy proof chain

---

### Architecture

```mermaid
graph TD
    U[User / Operator] --> N[NEXUS Dashboard :3690]
    N --> CC[Command Center]
    N --> LP[Launchpad]
    N --> BM[Benchmark Arena]
    
    CC --> AG1[AG1 Runtime]
    AG1 --> PL[Planner — LLM]
    AG1 --> EX[Executor — Policy Gate]
    AG1 --> RV[Reviewer — Deterministic]
    AG1 --> SY[Structured Synthesis]
    
    EX --> TL[Tool Layer]
    TL --> S[search — ripgrep]
    TL --> R[read_file — line numbers]
    TL --> PF[patch_file — 5-level heuristic]
    TL --> PL2[patch_lines — line-range]
    
    RV -->|ACCEPT| LD[Ledger — hash chain]
    RV -->|RETRY| AG1
    RV -->|FAIL| LD
    
    LD --> EP[Evidence Pack]
    EP --> RC[Receipt — SHA-256]
    
    AG1 --> K[ALKEM1 OS Kernel]
    K --> TR[Trust Layer]
    K --> CT[Contract Fabric]
    K --> IV[42 Invariants]
    
    K --> FL[Multi-Agent Fleet]
    FL --> C1[CTRL — dispatch]
    FL --> C2[CORE — execution]
    FL --> C3[UI — dashboard]
    FL --> C4[VERIFY — audit]

    style AG1 fill:#F97316,color:#fff,stroke:#F97316
    style K fill:#3B82F6,color:#fff,stroke:#3B82F6
    style N fill:#A855F7,color:#fff,stroke:#A855F7
    style RV fill:#22C55E,color:#fff,stroke:#22C55E
    style LD fill:#10B981,color:#fff,stroke:#10B981
```

---

### Stack

<p>
  <img src="https://img.shields.io/badge/Python-181A20?style=for-the-badge&logo=python&logoColor=3776AB" />
  <img src="https://img.shields.io/badge/TypeScript-181A20?style=for-the-badge&logo=typescript&logoColor=3178C6" />
  <img src="https://img.shields.io/badge/React-181A20?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/FastAPI-181A20?style=for-the-badge&logo=fastapi&logoColor=009688" />
  <img src="https://img.shields.io/badge/Docker-181A20?style=for-the-badge&logo=docker&logoColor=2496ED" />
  <img src="https://img.shields.io/badge/Redis-181A20?style=for-the-badge&logo=redis&logoColor=DC382D" />
  <img src="https://img.shields.io/badge/Ollama-181A20?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2Zz48L3N2Zz4=&logoColor=fff" />
  <img src="https://img.shields.io/badge/Polygon-181A20?style=for-the-badge&logo=polygon&logoColor=8247E5" />
</p>

---

### Benchmark — Operational Proof

> Same model (qwen2.5-coder:14b). Same tasks. Same workspace. Different runtimes.

| Metric | 🛡️ AG1 | Aider | OpenCode | Claude |
|--------|---------|-------|----------|--------|
| Capability | 67% | 100% | 100% | 67% |
| Safety | **100%** | 87% | 100% | 100% |
| Governance | **100%** | 0% | 0% | 0% |
| Containment | **100%** | 100% | 100% | 0% |
| **Overall** | **81** | 70 | 60 | 43 |

AG1 wins because it's the only system that **proves** what it did.

Every other system is faster. None of them can show you a receipt.

---

### Repos

| Project | Description | Status |
|---------|-------------|--------|
| [`alkem1-ag1`](https://github.com/alkem1-lab/alkem1-ag1) | Constitutional agent runtime | ![Tests](https://img.shields.io/badge/tests-213_pass-22C55E?style=flat-square&labelColor=181A20) |
| [`alkem1_os`](https://github.com/alkem1-lab/alkem1_os) | Kernel-first OS — 288K LOC | ![Invariants](https://img.shields.io/badge/invariants-42/42-3B82F6?style=flat-square&labelColor=181A20) |
| [`alkem1-xck`](https://github.com/alkem1-lab/alkem1-xck) | Security toolkit | ![Active](https://img.shields.io/badge/status-active-6B7280?style=flat-square&labelColor=181A20) |
| [`alkem1-trading`](https://github.com/alkem1-lab/alkem1-trading) | Autonomous trading system | ![Active](https://img.shields.io/badge/status-active-6B7280?style=flat-square&labelColor=181A20) |

---

<p align="center">
  <a href="mailto:alek@alkem1.com">alek@alkem1.com</a> · 
  <a href="https://www.instagram.com/alkem1ag1/">Instagram</a> · 
  <a href="https://www.behance.net/stefanovicaleksandar">Behance</a> ·
  Geneva, Switzerland
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=a1kem1&show_icons=true&theme=dark&bg_color=181A20&title_color=F97316&icon_color=22C55E&text_color=A1A1AA&border_color=2B2F36&hide_border=false&hide=stars&count_private=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=a1kem1&layout=compact&theme=dark&bg_color=181A20&title_color=F97316&text_color=A1A1AA&border_color=2B2F36&hide_border=false&langs_count=8" height="150" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=alkem1&color=F97316&style=flat-square&label=PROFILE+VIEWS" alt="views"/>
</p>

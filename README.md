<div align="center">
  <a href="https://github.com/TbK0ng">
    <img src="./assets/hero.svg" alt="Jing Cao - Building systems that can prove themselves" width="100%" />
  </a>
</div>

<p align="center">
  <a href="https://github.com/TbK0ng?tab=repositories"><img src="https://img.shields.io/badge/HIT-Computer%20Science-0f766e?style=flat-square" alt="HIT Computer Science" /></a>
  <img src="https://img.shields.io/badge/Harbin-China-334155?style=flat-square" alt="Harbin, China" />
  <img src="https://img.shields.io/badge/focus-auditable%20AI-b45309?style=flat-square" alt="Focus: auditable AI" />
  <a href="https://github.com/TbK0ng?tab=followers"><img src="https://img.shields.io/github/followers/TbK0ng?style=flat-square&color=0f766e&label=followers" alt="GitHub followers" /></a>
</p>

## I build AI systems that can prove themselves.

I am a Computer Science student at **Harbin Institute of Technology**. My work sits on the boundary between probabilistic models and deterministic systems: evidence before generation, state before action, replay before trust.

- **Evidence-first AI** — retrieval systems where every citation is traceable and verifiable.
- **Agent infrastructure** — harnesses that keep long-running tasks bounded, observable, and recoverable.
- **Deterministic execution** — rules nominate, models review, and code enforces.

---

## Selected work

<a href="https://github.com/TbK0ng/paknow">
  <picture>
    <source media="(max-width: 600px)" srcset="./assets/paknow-card-mobile.svg" />
    <img src="./assets/paknow-card.svg" alt="PAknow - an auditable price-action research agent" width="100%" />
  </picture>
</a>

**PAknow** is an auditable price-action research agent. Deterministic PA rules nominate candidates; PAknow retrieves and verifies evidence from six source books; an LLM is allowed to review only after support, risk, and confirmation evidence are complete; a paper replay then uses only the closed bars visible at signal time.

`Python` · `FastAPI` · `RAG` · `Qdrant` · `SQLite` · `Pydantic`

[Open the repository](https://github.com/TbK0ng/paknow) · [Read the architecture](https://github.com/TbK0ng/paknow#readme)

<a href="https://github.com/TbK0ng/myflow">
  <picture>
    <source media="(max-width: 600px)" srcset="./assets/myflow-card-mobile.svg" />
    <img src="./assets/myflow-card.svg" alt="myflow - a context state machine for coding agents" width="100%" />
  </picture>
</a>

**myflow** is a context state machine harness for Pi coding agents. Workflow state lives in files; lifecycle hooks project only the state needed into each turn; plan hashes bind approvals, write scopes constrain parallel agents, and verify gates block premature completion.

`TypeScript` · `Node.js` · `Python` · `Pi extension` · `JSONL RPC`

[Open the repository](https://github.com/TbK0ng/myflow) · [Read the architecture](https://github.com/TbK0ng/myflow#readme)

---

## How I think about systems

> If a system cannot explain its evidence, it should not make the call.

| Principle | In practice |
| --- | --- |
| **Evidence before generation** | A model output is only useful when its sources can be hydrated and checked. |
| **State before action** | Long-running agents need an explicit workflow state, not an ever-growing conversation. |
| **Replay before trust** | A decision should be reproducible from the inputs visible at that moment. |

<details>
<summary><b>Toolbox</b></summary>
<br />

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</details>

<p align="center">
  <sub>Harbin · HIT CS · building in public</sub>
</p>


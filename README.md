<div align="center">

# Paulo Henrique Vieira

### AI & Agent Engineer · ML/NLP · speech

I build infrastructure for LLM agents and speech systems, and I make architecture decisions by measurement rather than conviction.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-paulohenriquevn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paulohenriquevn)
[![npm](https://img.shields.io/badge/npm-@paulohenriquevn-CB3837?style=flat&logo=npm&logoColor=white)](https://www.npmjs.com/~paulohenriquevn)

</div>

---

## Building now

### [theokit](https://github.com/usetheokit/theokit) — the full-stack TypeScript framework for AI agents
An agent is a file: drop it in `agents/` and it gets an HTTP route, token streaming, human-in-the-loop approvals and a typed client. React pages with SSR, OAuth sessions, Postgres, WebSockets, cron and nine deploy targets. Apache-2.0, published on npm.

### [theokit-sdk](https://github.com/usetheokit/theokit-sdk) — an agent runtime you own end to end
`Agent.create` / `prompt` / `stream` / `resume`, 43 LLM providers on your own keys, MCP with OAuth PKCE, subagents, workflows, evals, memory, and a bubblewrap + seccomp kernel sandbox for tool execution.

---

## Speech & NLP

| Project | What it does |
|---|---|
| [**jvscribe**](https://github.com/paulohenriquevn/jvscribe) | Real-time Brazilian Portuguese transcription **on CPU**. Architecture chosen by measurement and recorded in ADRs: Zipformer-CTC (64M, int8) with an auxiliary phoneme head, 27.49% WER on the evaluation set. |
| [**talkex**](https://github.com/paulohenriquevn/talkex) | Conversation-intelligence engine for call centers: hybrid lexical + semantic search, supervised classification and a deterministic rule DSL. |
| [**autofeat**](https://github.com/paulohenriquevn/autofeat) | Automated feature engineering for ML pipelines, published on PyPI as `cafe-autofe`. |

## Developer tools

| Project | What it does |
|---|---|
| [**gitsafety**](https://github.com/paulohenriquevn/gitsafety) | Stops you from committing an API key — git repos, loose folders and Jupyter notebooks. On PyPI. |
| [**m2js**](https://github.com/paulohenriquevn/m2js) | CLI + VS Code extension that turns TypeScript/JavaScript into LLM-optimized Markdown. On npm. |
| [**loop-pentest-audit**](https://github.com/paulohenriquevn/loop-pentest-audit) | Autonomous 7-phase penetration-testing lab for Claude Code (OWASP Testing Guide), producing CVSS-scored findings. |

---

**Stack:** TypeScript · Python · PyTorch · Postgres · Claude / OpenAI / open-weight models · MCP · Docker

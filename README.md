<div align="center">

# Paulo Henrique Vieira

### Senior Software Engineer · LLM agents · Voice AI

Software engineer for more than 18 years. Today I build LLM agents, the runtimes and evaluation around them, and speech systems, as open-source and research projects, and I make architecture decisions by measurement.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-paulohenriquevn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paulohenriquevn)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-paulohenriquevn-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/paulohenriquevn)
[![npm](https://img.shields.io/badge/npm-@paulohenriquevn-CB3837?style=flat&logo=npm&logoColor=white)](https://www.npmjs.com/~paulohenriquevn)

</div>

## Agents and LLMs

| Project | What it does |
|---|---|
| [**loopzero**](https://github.com/getloopscale/loopzero) | Full-stack TypeScript framework for AI agents. An agent is a file: drop it in `agents/` and it gets an HTTP route, token streaming, human-in-the-loop approvals and a typed client. React pages with file routing and SSR, OAuth sessions, Postgres, WebSockets, cron and nine deploy targets. Apache-2.0. |
| [**loopzero-sdk**](https://github.com/getloopscale/loopzero-sdk) | TypeScript SDK and agent runtime you own end to end: `Agent.create`, `prompt`, `stream` and `resume`, 43 LLM providers on your own keys, MCP with OAuth PKCE, subagents, workflows, evals, memory, and a bubblewrap and seccomp kernel sandbox for tool execution. Apache-2.0. |
| [**aifactory**](https://github.com/getloopscale/aifactory) | Software factory that turns a GitHub issue into a verified pull request. Coding agents work in cloud sandboxes, and the pull request opens only with green checks and the approval of an independent reviewer. TypeScript. |
| [**gaia-agent**](https://github.com/paulohenriquevn/gaia-agent) | Agent that scores 55% on GAIA level 1, 11 of 20 questions, in the final assignment of the Hugging Face Agents Course. Tools for search, page reading, attachments and sandboxed Python, with a three-attempt answer chain. The README records the run that scored higher and was thrown away because the agent could reach the answer key. TypeScript. |

## Speech and NLP

| Project | What it does |
|---|---|
| [**jvscribe**](https://github.com/paulohenriquevn/jvscribe) | Brazilian Portuguese speech recognition that transcribes 40 seconds of audio per second on a laptop CPU. Zipformer-CTC with 64M parameters and 68 MB on disk: 15.99% WER and 7.30% CER on the first 100 test samples of FLEURS pt_br. Architecture chosen by measurement and recorded in ADRs. [Model on Hugging Face](https://huggingface.co/paulohenriquevn/jvscribe). |
| [**talkex**](https://github.com/paulohenriquevn/talkex) | Hybrid cascaded engine that classifies intents in Brazilian Portuguese customer-service conversations: lexical search, semantic embeddings, supervised classification and a deterministic rule DSL. Cheap filters run first. |
| [**autofeat**](https://github.com/paulohenriquevn/autofeat) | Automated feature engineering for ML pipelines, published on PyPI as `cafe-autofe`. |

## Infrastructure

| Project | What it does |
|---|---|
| [**aws-emulator**](https://github.com/paulohenriquevn/aws-emulator) | Fork of the AWS Emulator that runs a whole Terraform stack with no AWS account: RDS and ElastiCache start real servers in containers, each EKS cluster gets a control plane and nodes on kind, and a read-only web console lists what the emulator holds. Eight Terraform fixtures run on every pull request. Rust. |

## Developer tools

| Project | What it does |
|---|---|
| [**gitsafety**](https://github.com/paulohenriquevn/gitsafety) | Stops you from committing an API key, in git repos, loose folders and Jupyter notebooks. On PyPI. |
| [**m2js**](https://github.com/paulohenriquevn/m2js) | CLI and VS Code extension that turn TypeScript and JavaScript into Markdown summaries for LLMs. On npm. |

**Stack:** Python · TypeScript · PyTorch · MCP · Postgres · AWS · Kubernetes · Terraform · Java · C# · Rust

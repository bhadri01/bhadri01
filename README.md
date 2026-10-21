# Hi, I'm Bhadri 👋

**AI & Full-Stack Engineer · Senior Software Engineer · Salem, India**

I build AI applications and the full-stack systems behind them. I have nearly 4 years of full-time professional experience since December 2022, excluding internship, spanning web platforms, real-time services, cloud labs and AI workflows.

- 🔭 **Senior Software Engineer** at BloomSkillTech — building a multi-tenant EdTech platform and RAG/multi-agent workflows with LangChain, LangGraph and MCP
- 🏗️ Designed core infrastructure and helped scale a client's EdTech platform to support **10,000+ users**
- ⚡ Reduced RAG response latency by **40%** under concurrent workloads; improved API throughput by **50%** using Redis caching and asynchronous queues
- 🤝 Mentor **6+ engineers** and have trained **1,000+ students** across colleges
- 🦀 Writing Rust where correctness has to be structural: sandboxes, filesystems, WireGuard
- 📦 Author of [**fastapi-querybuilder**](https://github.com/bhadri01/fastapi-querybuilder) — [live PyPI download statistics](https://pepy.tech/projects/fastapi-querybuilder)
- 🌐 [bha3.in](https://bha3.in) · [LinkedIn](https://www.linkedin.com/in/bhadri01)

---

## 🛠️ Skills

| Area | Tools and experience |
| --- | --- |
| AI applications | RAG, LangChain, LangGraph, MCP, LLM APIs, pgvector, Qdrant |
| AI-assisted development | Claude, Codex, GitHub Copilot, Antigravity |
| Backend & data | Python, FastAPI, SQLAlchemy, Alembic, PostgreSQL, Redis/Valkey, TimescaleDB, Celery, MinIO/S3, Go, REST APIs, SSE, WebSockets |
| Frontend & MERN | React, Next.js, React Native, TypeScript, JavaScript, Tailwind CSS, MongoDB, Express, Node.js |
| Systems & delivery | Rust, Axum, Linux, Docker, Git, GitHub, GitLab, Jira, GitHub Actions, CI/CD, Pytest, Nginx, Traefik, WireGuard |
| Security | Burp Suite, Wireshark, Nmap, API security, Linux sandboxing, digital forensics, CTFs |
| Engineering practice | System design, automated testing, code review, technical training, mentorship |

## Experience

| Period | Role |
| --- | --- |
| Jan 2025 – Present | **Senior Software Engineer — BloomSkillTech:** helped scale a client EdTech platform to 10,000+ users; RAG/multi-agent pipelines, CI/CD and mentoring 6+ engineers |
| May 2023 – Dec 2024 | **Software Engineer — BloomSkillTech:** cloud labs, Docker workspaces, FastAPI services and Redis caching |
| Dec 2022 – May 2023 | **Associate Software Engineer — BloomSkillTech:** law enforcement CRM with React, Go, PostgreSQL and Docker |
| Aug 2021 – Dec 2022 | **Software Engineer Intern — Salem City Cyber Crime Police:** station website/database integration, maintenance and support |

**Education:** B.E. Electronics and Communication Engineering, Muthayammal Engineering College, 2019–2023. Final-year project: gesture-controlled electronics for controlling electronic components through gestures.

**Achievements:** Salem City Police Certificate of Appreciation (December 2021); TOM CTF first-place team; YUKTHI CTF third-place team. Rated chess player (FIDE 1612).

[View my latest résumé (PDF)](https://github.com/bhadri01/portfolio/blob/main/public/Bhadrinathan_A_Resume.pdf) · [Portfolio](https://bha3.in) · [LinkedIn](https://www.linkedin.com/in/bhadri01)

---

## 🚀 What I've built

**Systems & security**

- **[ZeroCode](https://github.com/bhadri01/ZeroCode)** — sandboxed code execution in Rust. Runs untrusted code across 20 languages behind 8 independent isolation layers (namespaces, `pivot_root`, cgroup v2, Landlock, seccomp BPF, full capability drop). 7-crate Axum workspace, Postgres `LISTEN/NOTIFY` as the job queue, live output over SSE. Hardened against 130+ adversarial tests — fork bombs, memory bombs, ptrace and mount escapes.
- **[ZeroVPN](https://github.com/bhadri01/ZeroVPN)** — self-hosted WireGuard management platform. Multi-crate Rust/Axum backend, React frontend, one `docker compose up`. Backend and frontend share a single wire schema by compiling a Rust crate to WASM and speaking MessagePack over WebSocket.
- **[NullVeil](https://github.com/bhadri01/NullVeil)** — read-only forensics tooling in Rust: filesystem parsers that physically cannot write to the disk they read.

**Open source**

- **[fastapi-querybuilder](https://github.com/bhadri01/fastapi-querybuilder)** — filtering, sorting and search for FastAPI + SQLAlchemy. JSON filters with 14 operators, nested relationship joins, global search, pagination and soft-delete — generated into SQLAlchemy, never string-built. MIT licensed. [Live download statistics](https://pepy.tech/projects/fastapi-querybuilder).
- **[fastapi_sse_events](https://github.com/bhadri01/fastapi_sse_events)** — server-sent events for FastAPI, backed by Redis pub/sub so streams survive more than one server.

**Platform & product**

- **AlgoTrade** *(private)* — automated trading for NSE/BSE on Zerodha Kite Connect. Rust risk-engine (position sizing, Black-Scholes Greeks, Sharpe/Sortino) called over stdin/stdout at µs latency; one broker WebSocket fanned out through Redis; 16-section React 19 dashboard; ticks in TimescaleDB.
- **Succeedex** *(private)* — multi-tenant edtech platform at [succeedex.in](https://succeedex.in). Role-based CRMs, an online test portal, and centralized OAuth across a Docker-based service suite.
- **Crime Records CRM** *(private)* — case management and timeline tracking, built single-handedly for the Cyber Crime Police Station, Salem. React + Go + PostgreSQL, deployed with Docker.

---

💬 Always up for a chat about building products from scratch — reach me on [LinkedIn](https://www.linkedin.com/in/bhadri01) or through [bha3.in](https://bha3.in).

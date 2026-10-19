# Hi, I’m Rahul Dev 👋

### Backend Developer | Rust · Infra · Solana

I’m a developer based in India with **2+ years of full-stack experience**. I’ve built backend services and AI applications using Python and TypeScript, a matching engine in Rust, and Solana programs with Anchor.

My work includes **Python and TypeScript backends, Rust matching engines, and Solana programs**. I enjoy understanding how systems work beneath the API from order matching and asynchronous execution to shared-memory communication.

**Open to backend, Rust, infrastructure, and Solana engineering opportunities.**

## Selected Projects

### [Centralized Exchange — Spot & Perpetuals](https://github.com/rahuldev7583/centralized-exchange)

Built an exchange with separate services for API requests, order matching, risk management, settlement, market data, and WebSocket updates.

- Implemented spot and perpetual trading workflows, including margin checks, funding, and liquidation.
- Used PostgreSQL for persistence and Redis for service messaging.
- Built the frontend with Next.js.
- Deployed on AWS using Docker, ECR, and a load balancer, with GitHub Actions CI/CD.

**Stack:** TypeScript · Node.js · Next.js · PostgreSQL · Redis · Docker · AWS

### [Rust Matching Engine](https://github.com/rahuldev7583/matching-engine-rust)

Built a Rust matching engine for spot and perpetual markets.

- Implemented price-time priority using `BTreeMap` and `VecDeque`.
- Supports limit and market orders, partial fills, cancellation, and order book depth.
- Includes self-trade prevention and forced liquidation support.
- Integrates with backend, risk, and settlement services through Redis messaging.

**Stack:** Rust · Order Books · Redis · Event-Driven Services

### [Solana & Anchor Programs](https://github.com/rahuldev7583/Q3_25_Builder_RahulDev)

Built Solana programs and client applications, including vault, escrow, AMM, and NFT staking projects.

- Worked with PDAs, account constraints, CPIs, and token transfers.
- Built client interactions with Anchor and Solana tooling.
- Completed the Turbin3 Q3 2025 Builder program.

**Stack:** Rust · Solana · Anchor · TypeScript

### [Agave Sidecar IPC — Prototype](https://github.com/rahuldev7583/agave-sidecar-ipc)

Exploring shared-memory communication as a foundation for decoupling RPC workloads from a Solana validator.

- Built a producer–consumer prototype using `mmap` and an SPSC queue.
- Experimented with shared-memory allocation and zero-copy message passing.
- Studying memory layout, synchronization, and safety boundaries in `unsafe` Rust.

**Status:** IPC prototype; real Agave integration is future work.

**Stack:** Rust · Shared Memory · mmap · Lock-Free Queues

### [Jira-Style Task Management CLI](https://github.com/rahuldev7583/jira-cli)

Built a Jira-style task management application in Rust, exploring developer tooling and application design.

**Stack:** Rust · CLI

## Experience

### Full Stack Developer — Remote
**Sakshem IT Solution Pvt Ltd | November 2024 – July 2026**

- Built a natural-language analytics backend that translated user questions into SQL across datasets containing **50+ tables**, enabling self-service analytics.
- Designed multi-stage AI pipelines for intent classification, entity extraction, SQL generation, and runtime orchestration.
- Developed backend services with **FastAPI, PostgreSQL, and Docker**, including asynchronous processing, reporting pipelines, and deployments across multiple environments.
- Architected a multilingual chatbot for an application serving **250K+ users**, using RAG, vector search, and multiple LLM integrations.
- Developed a KYC image-validation microservice using computer vision and explainable decision fusion.
- Built chatbot backends combining vector search, live web retrieval, LLM fallback, streaming responses, and safety guardrails.

### Freelance Full Stack Developer
**March 2024 – November 2024**

- Developed full-stack applications with React, Next.js, Node.js, and Express.
- Designed MongoDB and PostgreSQL databases and used Prisma for database access.
- Built responsive interfaces with Tailwind CSS and shadcn/ui.
- Deployed applications using Docker and AWS.

## Technologies

| Area | Technologies |
| --- | --- |
| Languages | Rust, TypeScript, JavaScript, Python |
| Backend | Tokio, FastAPI, Node.js, Express, REST APIs, WebSockets |
| Data | PostgreSQL, Redis, MongoDB, Prisma |
| Infrastructure | Linux, Docker, AWS, Nginx, GitHub Actions |
| Solana | Anchor, PDAs, CPIs, SPL Tokens, Solana Web3.js |
| AI Systems | RAG, Vector Search, LLM Integration, Agent Orchestration |
| Frontend | React, Next.js, Tailwind CSS |

## Currently Building & Exploring

- A [TUI coding agent in Rust](https://github.com/rahuldev7583/coding-agent), using Ratatui and Tokio.
- Async Rust, process execution, and Linux sandboxing.
- Agave validator internals and JSON-RPC request flow.
- Matching-engine correctness and performance measurement.

## Writing

I write about Rust and Solana infrastructure, including RPC request flow inside Agave.

[Read my articles on Medium](https://medium.com/@rahuldev7583)

## Contact

- **Email:** [rahuldev2714@gmail.com](mailto:rahuldev2714@gmail.com)
- **X / Twitter:** [@iamrahul_dev](https://twitter.com/iamrahul_dev)
- **GitHub:** [rahuldev7583](https://github.com/rahuldev7583)

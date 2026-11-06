# Hi, I'm Shubhi 👋

Senior Software Engineer at **EYKON** (formerly Landis+Gyr Metering Solutions). 4+ years building enterprise smart-metering products in **C#, .NET Core, Angular and MongoDB**, plus production GenAI workflows in **Python and LangChain** for firmware testing.

## What I work on

- **GenAI workflows for engineering teams.** I designed LLM-based workflows that my team uses day to day:
  - Test-failure log analysis
  - Test-impact prediction for GitLab merge requests
  - Test-script generation
- **Full-stack .NET.** .NET Core microservices, MongoDB and Angular dashboards for smart-grid telemetry (100k+ records, sub-second queries).
- **CI/CD.** I write YAML pipelines on Azure DevOps and GitLab CI that build Docker images of Python services and deploy them to UAT and production.
- **Mentoring.** I mentor two junior engineers who now maintain these GenAI workflows, and I review their merge requests.

## Projects

| Project | What it is | Stack |
|---|---|---|
| [**LLM Gateway**](https://github.com/shubhiofficial-17/llm_gateway) | Self-hosted, OpenAI-compatible gateway between apps and LLM providers: per-team keys, rate/token limits, monthly budgets, fallbacks with circuit breakers, exact and semantic caching, a usage and cost ledger. Under 4 ms p99 overhead at 300 req/s in k6 tests. | .NET 8, PostgreSQL, Redis, OpenTelemetry, Grafana, k6 |
| [**Repo Q&A**](https://github.com/shubhiofficial-17/repo-qa) | Ask questions about any GitHub repo and get answers cited to file and line. Code-aware chunking, hybrid vector + keyword search, and an evaluation harness that gates retrieval quality in CI. | Python, FastAPI, pgvector, Docker |
| [**meterstream**](https://github.com/shubhiofficial-17/meterstream) | Real-time smart-meter platform: streaming ingest, tamper and anomaly detection (F1 0.986 on labelled simulated data), time-series storage, live dashboard. | Python, Redis Streams, TimescaleDB, Terraform (Azure) |
| [**review-crew**](https://github.com/shubhiofficial-17/review-crew) | Multi-agent pull request reviewer: security, correctness, tests and performance agents with repo tools, plus a coordinator that validates line locations and merges duplicates. Ships as a GitHub Action. | Python, LLM tool use, GitHub API |
| [**Collab Board**](https://github.com/shubhiofficial-17/collab-board) *(in progress)* | Real-time collaborative whiteboard. Canvas with shapes, sticky notes, freehand drawing and undo/redo done; persistence and live sync next. | Angular 18, .NET 8, SignalR, MongoDB |

## Tech

`Python` · `C# / .NET 8` · `Angular` · `LLMs / GenAI` · `RAG` · `PostgreSQL` · `Redis` · `Docker` · `Azure` · `Terraform` · `Azure DevOps` · `GitLab CI` · `GitHub Actions` · `OpenTelemetry`

## Career

| Role | Since |
|---|---|
| Senior Software Engineer, EYKON | Apr 2026 |
| Software Engineer | Aug 2023 |
| Graduate Engineer Trainee | Aug 2022 |

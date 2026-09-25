# Swastik Agnihotri

**DevOps / SRE Engineer · Cloud Infrastructure · Kubernetes · AI Systems**

I build reliable infrastructure, Kubernetes self-healing control planes, and deterministic automation for distributed systems and AI workflows.

[LinkedIn](https://linkedin.com/in/swastik-agnihotri) · [Portfolio](https://github.com/Swastik023) · [Email](mailto:swastikwork007@gmail.com)

---

### Core Technologies

`Kubernetes` `Docker` `Terraform` `Python` `TypeScript` `Go` `FastAPI` `Next.js` `PostgreSQL` `Redis` `Prometheus` `OpenTelemetry`

---

## Engineering Focus

- **Kubernetes & Cloud Infrastructure:** Cluster deployment, container orchestration, GitOps workflows, and resource governance.
- **SRE & Incident Automation:** Bounded self-healing control planes, automated root-cause diagnosis, and policy-guarded remediation loops.
- **Observability & Distributed Tracing:** OpenTelemetry instrumentations, Prometheus metric schemas, alert-budget management, and Grafana dashboards.
- **AI Runtimes & Deterministic Workflows:** State-machine-backed agentic execution, structured LLM extraction, evaluation benchmarks, and DAG orchestration.
- **Platform Engineering & Multi-Tenancy:** Role-based access control, tenant isolation, transactional workflows, and schema validation.
- **Delivery & Reliability Quality:** Continuous integration, strict static analysis, and end-to-end regression test suites.

---

## Selected Systems

### [kubernetes-sre-incident-platform](https://github.com/Swastik023/kubernetes-sre-incident-platform)
**Autonomous Kubernetes incident-response platform that investigates cluster alerts, evaluates remediation policies, and executes guarded recovery actions.**
- **Problem:** Production Kubernetes alerts frequently lead to repetitive diagnostic workflows and manual remediation risks during critical incidents.
- **System:** A modular control plane combining asynchronous API collectors, LangGraph cyclical state graphs, and Open Policy Agent (OPA) validation gates.
- **Technical Capabilities:** Evaluates incident runbooks, verifies target cluster health via Prometheus metrics, enforces strict OPA security constraints before executing actions, and checkpoints recovery state across distributed worker nodes.
- **Stack:** `Kubernetes` `Python` `FastAPI` `LangGraph` `Open Policy Agent` `Temporal` `Prometheus` `OpenTelemetry`

---

### [online-assessment-engine](https://github.com/Swastik023/online-assessment-engine)
**Multi-tenant online examination engine designed for deterministic test delivery, rubric grading, and tamper-resistant student sessions.**
- **Problem:** Concurrent online assessments require strict session isolation, negative-marking accuracy, and zero state drift across volatile client connections.
- **System:** High-reliability Next.js App Router application backed by PostgreSQL, Redis-backed rate limiters, and a comprehensive automated test harness.
- **Technical Capabilities:** Multi-section timed test delivery, deterministic score calculation with penalty weights, role-based access control, and full offline/online attempt synchronization backed by **358 automated tests**.
- **Stack:** `Next.js 15` `TypeScript` `Prisma` `PostgreSQL` `Redis` `Docker` `Jest`

---

### [ai-web-scraping-platform](https://github.com/Swastik023/ai-web-scraping-platform)
**Visual node-based data extraction platform executing drag-and-drop web scraping workflows with schema inference.**
- **Problem:** Traditional web scrapers break on DOM updates, require brittle manual scripts, and lack visual observability into complex multi-step pipelines.
- **System:** React Flow interactive DAG workflow canvas coupled with a server-side headless browser cluster and automated structured data extraction.
- **Technical Capabilities:** Visual execution graphs, automated schema parsing, rate-limited browser automation via Puppeteer, and transactional run logging in PostgreSQL.
- **Stack:** `Next.js 14` `TypeScript` `React Flow` `Puppeteer` `Prisma` `PostgreSQL` `OpenTelemetry`

---

### [coaching-institute-erp](https://github.com/Swastik023/coaching-institute-erp)
**Production-oriented educational ERP managing institutional scheduling, attendance verification, and payroll accounting.**
- **Problem:** Coaching institutes face administrative drift reconciling teacher lecture logs, dynamic batch timetables, and monthly teacher compensation.
- **System:** Multi-portal administrative suite featuring distinct roles for administrators, teachers, students, and accountants.
- **Technical Capabilities:** Batch conflict detection, lecture attendance verification, automated payroll generation based on completed sessions, and secure document vaults.
- **Stack:** `Next.js 15` `TypeScript` `Node.js` `MongoDB` `Server Actions` `Playwright`

---

### [ai-adaptive-learning-platform](https://github.com/Swastik023/ai-adaptive-learning-platform)
**Multimodal educational knowledge pipeline converting unstructured audio into grounded concept graphs with hallucination benchmarks.**
- **Problem:** Educational content generated from audio recordings often suffers from unchecked factual drift and fragmented structure.
- **System:** Asynchronous processing pipeline linking speech transcription, vector embeddings, and visual graph extraction.
- **Technical Capabilities:** Chunked audio transcription, vector similarity retrieval in pgvector, entity-relationship graph compilation, and automated groundedness evaluation benchmarks.
- **Stack:** `Python` `FastAPI` `PostgreSQL` `pgvector` `Docker` `Pydantic`

---

## Technical Competencies

```text
┌────────────────────────────────────────────────────────────────────────────────────────┐
│ CLOUD & INFRASTRUCTURE:  Kubernetes, Docker, Helm, Linux (Systemd, POSIX), GitOps      │
│ RELIABILITY & SRE:       Prometheus, OpenTelemetry, Grafana, Alertmanager, OPA         │
│ BACKEND & PLATFORMS:     Python (FastAPI), TypeScript, Node.js, Go, REST, WebSockets    │
│ DATA STORES & CACHE:     PostgreSQL, MongoDB, Redis, pgvector                          │
│ AI SYSTEMS & AUTOMATION: LangGraph, Model Context Protocol (MCP), LiteLLM, RAG Pipeline│
│ CI/CD & TESTING:         GitHub Actions, Jest, Pytest, Playwright, Strict Mypy / TS    │
└────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## Engineering Principles

1. **Deterministic Guards on Autonomous Systems:** Never allow an automated agent or pipeline to mutate production state without strict, bounded policy constraints (e.g., OPA validation gates and human-in-the-loop triggers).
2. **Observability as an Architectural Requirement:** Metrics, structured logs, and distributed traces must be integrated directly into service boundaries—not bolted on after an outage.
3. **Automate Failure Scenarios:** Systems must be designed and tested assuming dependencies, networks, and nodes will fail. Verification requires chaos testing and automated regression suites.
4. **Evidence Over Assumptions:** Rely on measurable telemetry, test suites, and reproducible builds rather than optimistic code paths.

---

## Professional Background

- **~4 years of software engineering experience** working across DevOps, cloud infrastructure, SRE automation, and full-stack platform development.
- Background in architecting cloud-native control planes, automating deployment pipelines, and building mission-critical SaaS architectures.
- Experience implementing automated incident response systems, Kubernetes reliability engineering, and resilient distributed applications.

---

## Other Systems & Experiments

In addition to core DevOps/SRE systems, I maintain automation toolsets in growth engineering and desktop telemetry:

- **[autonomous-trading-agents-platform](https://github.com/Swastik023/autonomous-trading-agents-platform):** Autonomous multi-agent financial trading framework orchestrating specialized LLM agents over stateful LangGraph execution graphs.
- **[quantitative-trading-handbook](https://github.com/Swastik023/quantitative-trading-handbook):** Comprehensive architecture handbook and knowledge portal covering systematic trading libraries, market data APIs, and algorithmic execution.
- **[ai-marketing-operations-platform](https://github.com/Swastik023/ai-marketing-operations-platform):** Multi-channel growth engineering platform orchestrating programmatic SEO and Meta Marketing API campaign automation.
- **[realtime-streaming-telemetry](https://github.com/Swastik023/realtime-streaming-telemetry):** Low-latency WebSocket bridge streaming real-time desktop productivity telemetry to OBS Studio.
- **[marketing-api-automation-mcp](https://github.com/Swastik023/marketing-api-automation-mcp):** Model Context Protocol (MCP) server providing LLM agents with structured tooling for search and ads analytics.

---

## Currently

- Extending policy-driven self-healing routines and automated canary remediation in Kubernetes clusters.
- Refining deterministic evaluation harnesses for agentic workflows and LLM tool execution.
- Optimizing high-concurrency event loops in distributed platform backends.

---

<div align="center">

**Swastik Agnihotri**  
[swastikwork007@gmail.com](mailto:swastikwork007@gmail.com) · [GitHub Profile](https://github.com/Swastik023) · [LinkedIn](https://linkedin.com/in/swastik-agnihotri)

</div>

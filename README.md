<div align="center">

# Swastik Agnihotri

**DevOps & SRE Engineer · Cloud Infrastructure & Autonomous AI Platforms**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/swastik-agnihotri)
[![Portfolio](https://img.shields.io/badge/Live_Portfolio-2563EB?style=for-the-badge&logo=google-chrome&logoColor=white)](https://github.com/Swastik023/devops-ai-engineering-portfolio)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Swastik023)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:swastikwork007@gmail.com)

<p align="center">
  <i>Building resilient Kubernetes self-healing control planes, cloud infrastructure automation, and deterministic AI platforms.</i>
</p>

</div>

---

### ⚡ Quick Overview for Engineering Managers & Recruiters

```text
┌─────────────────────────┬────────────────────────────────────────────────────────┐
│ PRIMARY ROLE            │ DevOps / SRE Engineer · Cloud Infrastructure Architect │
│ EXPERIENCE              │ ~4 Years (SRE Automation, Cloud Architecture, Full-Stack)│
│ CORE SPECIALTY          │ Kubernetes, Self-Healing Control Planes, GitOps, OPA   │
│ SECONDARY FOCUS         │ Autonomous AI Agent Runtimes & Multi-Tenant SaaS       │
│ ENGINEERING DISCIPLINE  │ Strict Policy Guardrails, Chaos-Tested, Zero Untested  │
└─────────────────────────┴────────────────────────────────────────────────────────┘
```

---

## 🛠️ Technical Matrix

| Domain | Technologies & Tooling |
|---|---|
| **Cloud & Orchestration** | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |
| **Reliability & Observability** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-4279F5?style=flat-square&logo=opentelemetry&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![OPA](https://img.shields.io/badge/Open_Policy_Agent-7D7D7D?style=flat-square&logo=open-policy-agent&logoColor=white) |
| **Languages & Runtimes** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=node.js&logoColor=white) |
| **Frameworks & AI Systems** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=next.js&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-FF4B4B?style=flat-square&logo=python&logoColor=white) ![Temporal](https://img.shields.io/badge/Temporal-000000?style=flat-square&logoColor=white) |
| **Data & Storage** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white) |
| **CI/CD & Verification** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) |

---

## ⭐ Featured Flagship Systems

Instead of browsing dozens of repositories, here are the **top 3 platforms** that demonstrate my end-to-end systems architecture, reliability engineering, and code quality:

### 1. 🛡️ [Autonomous Kubernetes Incident Response & SRE Platform](https://github.com/Swastik023/kubernetes-sre-incident-platform)
> **Domain:** SRE & Cloud Infrastructure Automation · **Status:** Production-Ready Control Plane

```text
Live Prometheus Alerts ──► Diagnostic Agent (LangGraph) ──► OPA Policy Gate ──► Bounded Cluster Remediation
```

* **The Problem:** Production Kubernetes incidents (OOMKilled, CrashLoopBackOff) create alert fatigue and risky manual midnight runbook interventions.
* **The Architecture:** An event-driven SRE control plane that consumes Alertmanager webhooks, deploys an autonomous diagnostic state-machine to inspect logs and events, validates proposed actions against **Open Policy Agent (OPA)** security gates, and safely executes self-healing steps.
* **Key Highlight:** **100% Policy-Guarded** — automated remediation cannot mutate cluster state without cryptographically signed OPA rules.
* **Stack:** `Kubernetes` `Python (FastAPI)` `LangGraph` `Open Policy Agent` `Prometheus` `OpenTelemetry` `Docker`
* 🔗 **[Explore Repository →](https://github.com/Swastik023/kubernetes-sre-incident-platform)**

---

### 2. 🎯 [Multi-Tenant Online Assessment & Examination SaaS](https://github.com/Swastik023/online-assessment-engine)
> **Domain:** High-Reliability Enterprise SaaS · **Status:** Full SaaS Platform

* **The Problem:** High-stakes computer-based testing requires strict tenant isolation, complex negative-marking arithmetic, and zero state drift across fluctuating student internet connections.
* **The Architecture:** Multi-tenant Next.js 15 App Router engine with PostgreSQL transactional safety, Redis rate limiting, anti-cheat screen locks, and offline attempt recovery.
* **Key Highlight:** Backed by **358 automated unit, integration, and security test suites** with zero tolerance for calculation anomalies.
* **Stack:** `Next.js 15` `TypeScript` `Prisma` `PostgreSQL` `Redis` `Docker` `Jest`
* 🔗 **[Explore Repository →](https://github.com/Swastik023/online-assessment-engine)**

---

### 3. 📈 [Autonomous Multi-Agent Financial Trading Platform](https://github.com/Swastik023/autonomous-trading-agents-platform)
> **Domain:** Multi-Agent AI Systems & Quant Frameworks · **Status:** Autonomous Execution Framework

* **The Problem:** LLM-assisted market intelligence fails when single-prompt models produce biased, ungrounded financial predictions without risk boundaries.
* **The Architecture:** Multi-agent framework orchestrating specialized autonomous agents (Market Analysts, Bull/Bear Researchers, Sentiment Analysts, Risk Debaters, and Portfolio Managers) over a stateful **LangGraph** execution graph.
* **Key Highlight:** Features multi-agent debate protocols, multi-vendor live dataflows (Yahoo, FRED, SEC EDGAR, Reddit), and deterministic backtesting simulation.
* **Stack:** `LangGraph` `Python 3.11` `Pandas` `Typer / Rich CLI` `Alpha Vantage` `Docker`
* 🔗 **[Explore Repository →](https://github.com/Swastik023/autonomous-trading-agents-platform)**

---

## 📂 Complete Systems Directory

Expand the categories below to view all **25 production-ready, standardized repositories**:

<details>
<summary><b>🧠 1. AI Platforms & Intelligent Systems (5 Platforms)</b></summary>
<br>

| Repository | Focus & Architecture | Stack |
|---|---|---|
| [`autonomous-trading-agents-platform`](https://github.com/Swastik023/autonomous-trading-agents-platform) | Autonomous multi-agent quantitative trading & risk debate graph | Python, LangGraph, Pandas |
| [`ai-adaptive-learning-platform`](https://github.com/Swastik023/ai-adaptive-learning-platform) | Multimodal audio-to-knowledge graph pipeline with hallucination benchmarks | Python, FastAPI, pgvector |
| [`ai-web-scraping-platform`](https://github.com/Swastik023/ai-web-scraping-platform) | Drag-and-drop visual web scraping studio with automated schema extraction | Next.js, React Flow, Puppeteer |
| [`codebase-architecture-analyzer`](https://github.com/Swastik023/codebase-architecture-analyzer) | Static AST compiler visualizing codebase architecture and circular imports | TypeScript, AST, SVG Engine |
| [`ai-task-planning-engine`](https://github.com/Swastik023/ai-task-planning-engine) | Autonomous DAG-based daily execution planner with state-machine snapshots | Python, NetworkX, FastAPI |

</details>

<details>
<summary><b>⚙️ 2. DevOps, SRE & Cloud Systems (4 Platforms)</b></summary>
<br>

| Repository | Focus & Architecture | Stack |
|---|---|---|
| [`kubernetes-sre-incident-platform`](https://github.com/Swastik023/kubernetes-sre-incident-platform) | Autonomous Kubernetes self-healing control plane with OPA policy gates | Kubernetes, LangGraph, OPA |
| [`realtime-streaming-telemetry`](https://github.com/Swastik023/realtime-streaming-telemetry) | Low-latency WebSocket bridge streaming productivity metrics into OBS Studio | Node.js, WebSockets, OBS API |
| [`offline-productivity-desktop`](https://github.com/Swastik023/offline-productivity-desktop) | Offline-first desktop focus client with local SQLite sync and plugins | Electron, Angular, TypeScript |
| [`devops-ai-engineering-portfolio`](https://github.com/Swastik023/devops-ai-engineering-portfolio) | Interactive portfolio showcasing systems architecture and STAR case studies | Next.js 15, Tailwind, React 19 |

</details>

<details>
<summary><b>🏢 3. Enterprise SaaS & Platforms (3 Platforms)</b></summary>
<br>

| Repository | Focus & Architecture | Stack |
|---|---|---|
| [`online-assessment-engine`](https://github.com/Swastik023/online-assessment-engine) | Multi-tenant computer-based test platform backed by 358 test suites | Next.js 15, PostgreSQL, Redis |
| [`coaching-institute-erp`](https://github.com/Swastik023/coaching-institute-erp) | Educational ERP with 4 portals (Admin, Teacher, Student, Accountant) | Next.js 15, MongoDB, Node.js |
| [`quantitative-trading-handbook`](https://github.com/Swastik023/quantitative-trading-handbook) | Systematic trading architecture handbook and resource knowledge portal | MkDocs Material, Python |

</details>

<details>
<summary><b>📈 4. Digital Marketing & Growth Systems (13 Platforms)</b></summary>
<br>

| Repository | Focus & Architecture | Stack |
|---|---|---|
| [`ai-marketing-operations-platform`](https://github.com/Swastik023/ai-marketing-operations-platform) | Unified AI marketing OS coordinating SEO, ads, and lead funnels | Next.js, Node.js, PostgreSQL |
| [`marketing-api-automation-mcp`](https://github.com/Swastik023/marketing-api-automation-mcp) | Model Context Protocol (MCP) server for GA4, Google Ads, and Meta APIs | TypeScript, MCP SDK, REST |
| [`google-search-performance-dashboard`](https://github.com/Swastik023/google-search-performance-dashboard) | Search Console analytics dashboard with automated ranking decay alerts | React, TypeScript, GSC API |
| [`seo-traffic-monitoring-agent`](https://github.com/Swastik023/seo-traffic-monitoring-agent) | Autonomous agent scanning organic traffic dips and drafting content briefs | Python, FastAPI, OpenAI API |
| [`programmatic-seo-content-engine`](https://github.com/Swastik023/programmatic-seo-content-engine) | Programmatic landing page generator with SERP schema optimization | Next.js, TypeScript, Node.js |
| [`social-media-publishing-platform`](https://github.com/Swastik023/social-media-publishing-platform) | Self-hosted multi-channel social media scheduler and queue manager | Next.js, PostgreSQL, APIs |
| [`social-inbox-analytics-platform`](https://github.com/Swastik023/social-inbox-analytics-platform) | Unified customer inbox with sentiment classification and reply drafting | Next.js, TypeScript, PostgreSQL |
| [`meta-ads-campaign-automation`](https://github.com/Swastik023/meta-ads-campaign-automation) | Programmatic ad launching and budget optimization via Meta Graph API | TypeScript, Meta API, Redis |
| [`performance-marketing-analytics`](https://github.com/Swastik023/performance-marketing-analytics) | Multi-channel ROAS analytics dashboard with creative leaderboards | Next.js, TypeScript, PostgreSQL |
| [`privacy-first-web-analytics`](https://github.com/Swastik023/privacy-first-web-analytics) | Cookieless, GDPR-compliant web analytics and conversion funnel tracker | Next.js, PostgreSQL, Prisma |
| [`multi-touch-marketing-attribution`](https://github.com/Swastik023/multi-touch-marketing-attribution) | First/Last/Linear multi-touch attribution engine for revenue tracking | Python, Node.js, PostgreSQL |
| [`email-marketing-automation-platform`](https://github.com/Swastik023/email-marketing-automation-platform) | Multi-tenant email marketing suite with visual automation drip builder | Next.js, PostgreSQL, BullMQ |
| [`transactional-email-gateway`](https://github.com/Swastik023/transactional-email-gateway) | High-throughput email delivery gateway orchestrating AWS SES & SNS | Node.js, AWS SES, Docker |

</details>

---

## 🏛️ Engineering Principles

1. **Deterministic Guardrails on Autonomous Systems:** Autonomous agents and SRE scripts must never perform destructive actions without strict OPA policy validation and human checkpoints.
2. **Observability as an Architectural Invariant:** Distributed tracing, structured logging, and metric schemas belong inside service boundaries from Day 1, not retrofitted after an outage.
3. **Fail-Closed Security & Resilience:** Design assuming dependencies, networks, and worker nodes will degrade. Validate with chaos testing and automated regression suites.
4. **Evidence Over Assumptions:** Rely on measurable telemetry, mechanical test suites, and reproducible builds.

---

<div align="center">

**Swastik Agnihotri**  
[swastikwork007@gmail.com](mailto:swastikwork007@gmail.com) · [LinkedIn Profile](https://linkedin.com/in/swastik-agnihotri) · [GitHub Profile](https://github.com/Swastik023)

</div>

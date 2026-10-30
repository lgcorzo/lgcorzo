# Dr. Luis Galo Corzo (`@lgcorzo`)

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org/)
[![Rust](https://img.shields.io/badge/Rust-1.80%2B-black?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Go](https://img.shields.io/badge/Go-1.22%2B-00ADD8?style=flat-square&logo=go&logoColor=white)](https://golang.org/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-GitOps%20%7C%20FluxCD-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![MLOps](https://img.shields.io/badge/MLOps-DVC%20%7C%20MLflow%20%7C%20Hydra-0194E2?style=flat-square)](https://github.com/lgcorzo/mlops-python-package)
[![ISO Standards](https://img.shields.io/badge/Architecture-ISO%2042010%20%7C%2015289-2E7D32?style=flat-square)](https://github.com/lgcorzo/llmops-python-package)
[![SIMD Acceleration](https://img.shields.io/badge/Hardware%20SIMD-AVX--512%20%7C%20ARM64-FF6F00?style=flat-square)](https://github.com/lgcorzo/sha256-simd)

### **Industrial AI Architect | MLOps, LLMOps & Autonomous Agent Factories**
*Ph.D. in Engineering · AI Architect @ Lantek · 15+ Years in Mission-Critical Systems*

[Portfolio Website](https://lgcorzo.github.io/) • [LinkedIn](https://www.linkedin.com/in/lgcorzo/) • [Curriculum Knowledge Base](https://notebook.google.com/notebook/ea63f8a7-1f9d-4326-8222-9e4429f37f90) • [Architecture Deep Dives](https://lgcorzo.github.io/architecture.html)

</div>

---

## 🏗️ Ecosystem Architecture: The Autonomous Factory Pattern

This GitHub ecosystem represents an **end-to-end blueprint of an Autonomous Software Factory**. 

The architecture demonstrates how a Kubernetes-native control plane orchestrates autonomous coding agents, while enforcing **strict isolation boundaries between owned application code, forked upstream dependencies, and the protected core factory infrastructure**.

```
┌────────────────────────────────────────────────────────────────────────────────────────────────────────┐
│                               SOVEREIGN KUBERNETES CLUSTER (GitOps / FluxCD)                          │
│                                                                                                        │
│  ┌──────────────────────────────────────────────────────────────────────────────────────────────────┐  │
│  │ 🔒 PROTECTED CORE FACTORY PLANE (High-Privilege / Zero-Trust)                                    │  │
│  │                                                                                                  │  │
│  │  • Dark Gravity Orchestrator (rust_CACD_autonomous_factory - Hatchet DAG, W3C-VC NHI Tokens)    │  │
│  │  • Jules Remediation Daemon (FluxCD alert webhooks, MLflow run tracking)                         │  │
│  │  • Enterprise LLM Gateway (LiteLLM hardened router, Antigravity streaming proxy)                │  │
│  │  • Sovereign Object Storage Tier (Self-hosted MinIO, Operator, KES, DirectPV)                   │  │
│  └───────────────────────────────────┬──────────────────────────────────────────────────────────────┘  │
│                                      │                                                                 │
│             Orchestration Directives │ Enforces Strict Sandboxing, CI/CD Gates & Non-Human IDs         │
│             & GitOps Desired State   │ (gVisor runsc isolation, Deny-All Network Policies, HITL)       │
│                                      ▼                                                                 │
│  ┌──────────────────────────────────────────────────────────────────────────────────────────────────┐  │
│  │ ⚡ WORKLOAD & EXECUTION DOMAINS (Autonomous Agent Workspaces)                                     │  │
│  │                                                                                                  │  │
│  │  ┌──────────────────────────────────────────────┐  ┌──────────────────────────────────────────┐  │  │
│  │  │ 📦 OWNED DOMAINS & APPLICATIONS              │  │ 🍴 FORKED & HARDENED UPSTREAMS           │  │  │
│  │  │ (Agent targets: code generation, PRs, tests) │  │ (Sovereignty, bugfixes & hardware SIMD)  │  │  │
│  │  │                                              │  │                                          │  │  │
│  │  │ • mlops-python-package (DVC, MLflow, Hydra)  │  │ • superpowers (Agentic execution harness)│  │  │
│  │  │ • llmops-python-package (ISO 42010 OpenWiki) │  │ • spec-kit (Spec-Driven Development)     │  │  │
│  │  │ • fastapi-autogen-team (Rust SSE squad)      │  │ • R2R-Engine / R2R-Application (RAG)     │  │  │
│  │  │ • devops_job_shop_scheduling (Optimization) │  │ • sha256-simd / highwayhash / simdjson   │  │  │
│  │  │ • semantica (Knowledge graphs & ontologies)  │  │ • minio / operator / mc / directpv       │  │  │
│  │  └──────────────────────────────────────────────┘  └──────────────────────────────────────────┘  │  │
│  └──────────────────────────────────────────────────────────────────────────────────────────────────┘  │
└────────────────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 📂 Repository Topology: Core vs. Owned vs. Forked

The repositories in this profile are structured into three distinct operational tiers to guarantee that untrusted or agentic code changes cannot compromise the core factory infrastructure:

### 1. 🔒 Protected Core Factory & Infrastructure (Kubernetes-Native)
The control plane and governance spine. These components run inside Kubernetes and direct autonomous agent operations, manage cryptographic non-human identities, route LLM traffic, and guard the cluster:
- **[`rust_CACD_autonomous_factory`](https://github.com/lgcorzo/rust_CACD_autonomous_factory) (Dark Gravity):** The brain of the factory. A Rust-based Continuous Architecture & Continuous Delivery (CA/CD) orchestrator coordinating a 6-phase DAG (Hatchet), minting Ed25519-signed Verifiable Credentials for Non-Human Identities (NHI), and dispatching missions into gVisor-isolated sandboxes.
- **[`Jules_remediator`](https://github.com/lgcorzo/Jules_remediator):** Automated Kubernetes incident remediator. Listens to FluxCD reconciliation alerts, classifies runtime errors, logs MLOps experiments to MLflow, and instructs agents to synthesize targeted PR patches.
- **[`gitops_internal_lgcorzo`](https://github.com/lgcorzo/gitops_internal_lgcorzo):** GitOps single source of truth managing the Kubernetes cluster state via FluxCD. Hosts infrastructure definitions, sealed secrets, and the internal LiteLLM LLM gateway with pre-warmed streaming proxies.
- **[`speckit-superpowers-bridge`](https://github.com/lgcorzo/speckit-superpowers-bridge):** The formal contract bridge uniting Spec-Driven Development (Spec Kit—defining **WHAT** via constitution, spec, plan, and tasks) with Superpowers execution discipline (**HOW** via TDD, subagents, and isolated worktrees).

### 2. 🚀 Owned Applications & Domain Standards
First-party production packages and enterprise systems where the autonomous factory operates—executing missions, updating documentation, running test suites, and driving releases:
- **[`mlops-python-package`](https://github.com/lgcorzo/mlops-python-package):** Enterprise MLOps standard featuring DVC data/model versioning, MLflow tracking, SHAP explainability, and automated CI test gates. Managed autonomously with strict OpenWiki documentation standards.
- **[`llmops-python-package`](https://github.com/lgcorzo/llmops-python-package):** Domain-driven LLMOps platform adhering to ISO/IEC/IEEE 42010:2022 and 15289:2019 standards, featuring prompt evaluations, MCP tool registries, and auto-generated OpenWiki architecture wikis.
- **[`fastapi-autogen-team`](https://github.com/lgcorzo/fastapi-autogen-team):** High-throughput microservice in native Rust (Axum + Rig), exposing OpenAI-compatible streaming SSE endpoints for multi-agent squads (Planner, Searcher, QA).
- **[`devops_job_shop_scheduling`](https://github.com/lgcorzo/devops_job_shop_scheduling):** Industrial operations research and genetic algorithm optimization for the Job Shop Scheduling Problem (JSP).
- **[`semantica`](https://github.com/lgcorzo/semantica):** Semantic domain modeling, ontologies, and knowledge graphs for complex physical systems.

### 3. 🍴 Forked Upstreams & Sovereign Infrastructure
Upstream open-source ecosystems maintained to guarantee supply-chain sovereignty, apply security hardening, patch critical bugs, or inject low-level hardware optimizations:
- **Autonomous & Spec Tooling Upstreams:**
  - **[`superpowers`](https://github.com/lgcorzo/superpowers):** Upstream fork of the agentic execution harness, integrating TDD workflows and review checkpoints.
  - **[`spec-kit`](https://github.com/lgcorzo/spec-kit):** Upstream fork of GitHub Spec Kit for Spec-Driven Development (SDD) tooling and CLI scaffolding.
- **Multimodal AI & RAG Infrastructure:**
  - **[`R2R-Engine`](https://github.com/lgcorzo/R2R-Engine) & [`R2R-Application`](https://github.com/lgcorzo/R2R-Application):** Hardened enterprise RAG platform with hybrid search, knowledge graph indexing, and full-stack observability.
  - **[`dark-litellm`](https://github.com/lgcorzo/dark-litellm):** Enterprise sovereign router and proxy for multi-model governance, scanned with Trivy and built hermetically.
- **Sovereign Object Storage Tier (Self-Hosted on Kubernetes):**
  - **[`minio`](https://github.com/lgcorzo/minio), [`operator`](https://github.com/lgcorzo/operator), [`mc`](https://github.com/lgcorzo/mc), [`kes`](https://github.com/lgcorzo/kes), [`directpv`](https://github.com/lgcorzo/directpv):** Complete sovereign S3 storage stack deployed on bare-metal Kubernetes, eliminating external cloud dependency for datasets, models, and build artifacts.
- **Hardware SIMD Primitives (AVX-512 & ARM64 Assembly):**
  - **[`sha256-simd`](https://github.com/lgcorzo/sha256-simd):** Up to 8x accelerated cryptographic hashing (>3 GB/s per core).
  - **[`highwayhash`](https://github.com/lgcorzo/highwayhash):** Native assembly hashing exceeding 10 GB/s per core.
  - **[`simdjson-go`](https://github.com/lgcorzo/simdjson-go):** Multi-gigabit JSON stream parsing for pipeline telemetry.

---

## 🔒 Security & Factory Isolation Model

To ensure autonomous agents cannot corrupt production services or leak credentials, the factory operates under strict defense-in-depth principles:

1. **Strict Sandboxing & Kernel Isolation:** All untrusted code execution generated by agents runs inside **gVisor (`runsc`)** or ephemeral container sandboxes with locked-down seccomp profiles, non-root users, and memory limits.
2. **Deny-All Network Boundaries:** Sandboxes lack ingress and possess zero egress access to the internal Kubernetes cluster API or control plane services.
3. **Non-Human Identity (NHI) Attestation:** Every automated agent mission receives an ephemeral, Ed25519-signed W3C Verifiable Credential defining precise capabilities, timeouts, and scopes.
4. **Mandatory Human-in-the-Loop (HITL) Merge Gate:** Autonomous agents are empowered to formulate plans, open branches, write tests, and submit PRs. However, **agents are strictly prohibited from merging pull requests into `main`**. Final merge verification remains a human checkpoint.
5. **GitOps Single Source of Truth:** Cluster state changes must pass through GitOps PR validation (FluxCD dry-run, Kustomize linting, Trivy vulnerability scans, Gitleaks) before being reconciled onto the cluster.

---

## 🌟 Flagship Repositories Matrix

| Repository | Role in Factory | Discipline & Architecture | Core Stack |
| :--- | :--- | :--- | :--- |
| [**`rust_CACD_autonomous_factory`**](https://github.com/lgcorzo/rust_CACD_autonomous_factory) | **Factory Core (Orchestrator)** | Autonomous CA/CD DAG, gVisor sandboxing & W3C-VC NHI | `Rust` `Hatchet` `gVisor` `Cargo` |
| [**`speckit-superpowers-bridge`**](https://github.com/lgcorzo/speckit-superpowers-bridge) | **Factory Core (Governance)** | Spec-Driven Development handoff bridge (WHAT vs HOW) | `Shell` `PowerShell` `Spec-Kit` `Superpowers` |
| [**`mlops-python-package`**](https://github.com/lgcorzo/mlops-python-package) | **Owned Application** | Industrial MLOps with DVC, MLflow tracking & SHAP gates | `Python` `DVC` `MLflow` `Hydra` `Poetry` |
| [**`llmops-python-package`**](https://github.com/lgcorzo/llmops-python-package) | **Owned Application** | ISO 42010 OpenWiki docs, multi-agent evaluation & MCP | `Python` `AutoGen` `ISO-42010` `OpenWiki` |
| [**`fastapi-autogen-team`**](https://github.com/lgcorzo/fastapi-autogen-team) | **Owned Application** | Native Rust high-throughput microservice with streaming SSE | `Rust` `Axum` `Rig` `Docker` |
| [**`devops_job_shop_scheduling`**](https://github.com/lgcorzo/devops_job_shop_scheduling) | **Owned Application** | Operations research & genetic algorithm heuristic optimization | `Python` `Operations-Research` `Optimization` |

---

<div align="center">

📍 Bilbao, Basque Country, Spain / Remote  
🔗 [Website](https://lgcorzo.github.io/) • [LinkedIn](https://www.linkedin.com/in/lgcorzo/) • [Curriculum Knowledge Base](https://notebook.google.com/notebook/ea63f8a7-1f9d-4326-8222-9e4429f37f90) • [Dark Gravity Architecture](https://notebook.google.com/notebook/116d5f03-2fb0-4fa7-bd7c-1c9849920abc)

</div>

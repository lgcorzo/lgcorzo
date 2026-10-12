# Dr. Luis Galo Corzo (`@lgcorzo`)

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org/)
[![Rust](https://img.shields.io/badge/Rust-1.80%2B-black?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Go](https://img.shields.io/badge/Go-1.22%2B-00ADD8?style=flat-square&logo=go&logoColor=white)](https://golang.org/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-Cloud--Native-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![MLOps](https://img.shields.io/badge/MLOps-DVC%20%7C%20MLflow%20%7C%20Hydra-0194E2?style=flat-square)](https://github.com/lgcorzo/mlops-python-package)
[![ISO Standards](https://img.shields.io/badge/Architecture-ISO%2042010%20%7C%2015289-2E7D32?style=flat-square)](https://github.com/lgcorzo/llmops-python-package)
[![SIMD Acceleration](https://img.shields.io/badge/Hardware%20SIMD-AVX--512%20%7C%20ARM64-FF6F00?style=flat-square)](https://github.com/lgcorzo/sha256-simd)

### **Industrial AI Architect | MLOps, LLMOps and Agentic Systems**
*Ph.D. in Engineering · Head of AI @ Lantek · 15+ Years in Physical & Industrial Systems*

[Portfolio Website](https://lgcorzo.github.io/) • [LinkedIn](https://www.linkedin.com/in/lgcorzo/) • [Curriculum Knowledge Base](https://notebook.google.com/notebook/ea63f8a7-1f9d-4326-8222-9e4429f37f90) • [Architecture Deep Dives](https://lgcorzo.github.io/architecture.html)

</div>

---

## 🔭 Executive Technical Profile

I design and engineer AI systems that bridge **industrial applications, machine learning lifecycles, LLM-based architectures, and production infrastructure**. 

My engineering background spans over 15 years in **mission-critical physical systems**—including railway traction converters (CAF), early 100% electric transit power systems (JEMA/Irizar), industrial 3D vision robotics (Inser Robótica), and a Doctorate in Electronics & Machine Vision (Tecnun/CEIT). 

Today, as **Head of AI at Lantek Sheet Metal Solutions**, I lead enterprise AI initiatives across CAD/CAM/MES platforms, transforming exploratory algorithms into reproducible, observable, testable, and secure production platforms.

My public technical ecosystem focuses on:
- **Reproducible MLOps & LLMOps:** Production-packaged pipelines replacing fragile notebooks with versioned data, model lineage, prompt observability, and automated quality gates.
- **High-Throughput Agentic Systems:** Multi-agent squads, low-latency microservices, and hybrid knowledge graph retrieval (RAG).
- **Autonomous Software Factories:** Advanced research into Continuous Architecture & Delivery (CA/CD) governed by strict specification contracts and isolated sandboxes.
- **Technological Sovereignty:** Self-hosted storage infrastructure and SIMD-vectorized cryptographic primitives ensuring zero supply-chain fragility.

---

## 🏛️ Technical Pillars & Architecture

```
┌─────────────────────────────────────────────────────────────────────────────────────────────────┐
│                       CORE IDENTITY: INDUSTRIAL AI & PRODUCTION PLATFORMS                       │
├────────────────────────────────┬────────────────────────────────┬───────────────────────────────┤
│ 1. Industrial AI & Operations  │ 2. MLOps Lifecycle Standards   │ 3. Enterprise LLMOps & Agents │
│    Research & Optimization     │    DVC · MLflow · Hydra · SHAP │    AutoGen · ISO 42010 · RAG  │
├────────────────────────────────┴────────────────────────────────┴───────────────────────────────┤
│                       ADVANCED SPECIALISATIONS: SYSTEMS & AUTONOMY                              │
├─────────────────────────────────────────────────┬───────────────────────────────────────────────┤
│ 4. Autonomous Agent Factories (Dark Gravity)    │ 5. Technological Sovereignty & SIMD Infra     │
│    Hatchet DAG · gVisor Sandboxing · SDD        │    Self-Hosted S3 (MinIO) · AVX-512 Assembly  │
└─────────────────────────────────────────────────┴───────────────────────────────────────────────┘
```

### 1. 🏭 Industrial AI & Applied Operations Research
Bridging physical manufacturing constraints with algorithmic optimization:
- **[`devops_job_shop_scheduling`](https://github.com/lgcorzo/devops_job_shop_scheduling):** Mathematical modeling and genetic algorithm heuristic optimization for the Job Shop Scheduling Problem (JSP), minimizing makespan across industrial constraints.
- **[`semantica`](https://github.com/lgcorzo/semantica):** Semantic graph modeling, ontologies, and domain-driven knowledge representations for industrial operations.

### 2. ⚙️ Production MLOps Lifecycle Standards
Packaging machine learning as disciplined software engineering:
- **[`mlops-python-package`](https://github.com/lgcorzo/mlops-python-package):** Enterprise-grade MLOps foundation implementing reproducible model pipelines (`training`, `evaluation`, `explanations` with SHAP, `promotion`). Features DVC data/model versioning (`dvc.yaml`), MLflow experiment tracking, Hydra configuration management, and automated CI test gates.

### 3. 🧠 Enterprise LLMOps, RAG & High-Throughput Agents
Orchestrating reliable generative AI and multi-agent coordination:
- **[`llmops-python-package`](https://github.com/lgcorzo/llmops-python-package):** Domain-driven LLMOps architecture adhering to ISO/IEC/IEEE 42010:2022 and 15289:2019 standards. Provides prompt evaluation, schema-validated agent interfaces, MCP tool integration, and automated OpenWiki architectural documentation.
- **[`fastapi-autogen-team`](https://github.com/lgcorzo/fastapi-autogen-team):** High-throughput AI service written in native Rust with Axum and Rig, exposing OpenAI-compatible streaming Server-Sent Events (SSE) for multi-agent squads (Planner, Searcher, QA).
- **[`R2R-Engine`](https://github.com/lgcorzo/R2R-Engine) & [`R2R-Application`](https://github.com/lgcorzo/R2R-Application):** State-of-the-art multimodal Retrieval-Augmented Generation (RAG) platform featuring hybrid knowledge graph indexing and a Next.js/React observability dashboard.

### 4. 🦀 Autonomous Software Factories & Systems Engineering
Advanced research in autonomous software delivery under formal governance:
- **[Dark Gravity (`rust_CACD_autonomous_factory`)](https://github.com/lgcorzo/rust_CACD_autonomous_factory):** Autonomous Continuous Architecture & Continuous Delivery (CA/CD) factory in Rust. Coordinates a 6-phase DAG via Hatchet, generates Ed25519-signed Non-Human Identity (NHI) verifiable credentials, and executes untrusted agent-written code inside isolated gVisor sandboxes with strict memory clamps.
- **[`speckit-superpowers-bridge`](https://github.com/lgcorzo/speckit-superpowers-bridge):** Architectural handoff bridge uniting Spec-Driven Development (Spec Kit—defining WHAT through formal specifications) with Superpowers execution discipline (HOW via TDD, isolated Git worktrees, and subagent review).

### 5. 🛡️ Technological Sovereignty & High-Performance Infrastructure
Eliminating supply-chain fragility and external licensing risks through sovereign maintenance:
- **Sovereign Object Storage Engine:** Self-hosted S3 storage tier deployed on Kubernetes ([`minio`](https://github.com/lgcorzo/minio), [`operator`](https://github.com/lgcorzo/operator), [`mc`](https://github.com/lgcorzo/mc), [`kes`](https://github.com/lgcorzo/kes), [`directpv`](https://github.com/lgcorzo/directpv)) guaranteeing persistent, independent artifact storage without vendor lock-in.
- **Hardware SIMD Vectorization (AVX-512 & ARM64):** Maintained and assembly-optimized cryptographic and streaming primitives for wire-speed data pipelines:
  - [`sha256-simd`](https://github.com/lgcorzo/sha256-simd): Up to 8x hardware acceleration (>3 GB/s per core).
  - [`highwayhash`](https://github.com/lgcorzo/highwayhash): Native assembly hashing exceeding 10 GB/s per core.
  - [`simdjson-go`](https://github.com/lgcorzo/simdjson-go): Gigabit-per-second JSON stream parsing for pipeline telemetry.

---

## 🌟 Flagship Repositories

| Repository | Discipline & Architecture | Core Stack |
| :--- | :--- | :--- |
| [**`mlops-python-package`**](https://github.com/lgcorzo/mlops-python-package) | **Industrial MLOps Standard** · DVC pipelines, MLflow tracking, SHAP explainability & CI gates | `Python` `DVC` `MLflow` `Hydra` `Poetry` |
| [**`llmops-python-package`**](https://github.com/lgcorzo/llmops-python-package) | **Enterprise LLMOps & Evaluation** · ISO 42010 OpenWiki docs, multi-agent evaluation & MCP | `Python` `AutoGen` `ISO-42010` `OpenWiki` |
| [**`fastapi-autogen-team`**](https://github.com/lgcorzo/fastapi-autogen-team) | **High-Throughput Agentic Service** · Low-latency Axum/Rig Rust microservice with streaming SSE | `Rust` `Axum` `Rig` `Streaming` `Docker` |
| [**`rust_CACD_autonomous_factory`**](https://github.com/lgcorzo/rust_CACD_autonomous_factory) | **Autonomous CA/CD Factory (Dark Gravity)** · Hatchet 6-phase DAG, gVisor sandboxing & NHI | `Rust` `Hatchet` `gVisor` `W3C-VC` `Cargo` |
| [**`speckit-superpowers-bridge`**](https://github.com/lgcorzo/speckit-superpowers-bridge) | **Spec-Driven Development Bridge** · Enforcing formal specs (WHAT) and TDD discipline (HOW) | `Shell` `PowerShell` `Spec-Kit` `Superpowers` |
| [**`devops_job_shop_scheduling`**](https://github.com/lgcorzo/devops_job_shop_scheduling) | **Applied Operations Research** · Genetic algorithm heuristic optimization for makespan scheduling | `Python` `Operations-Research` `Optimization` |

---

## 🔒 Engineering Governance & Quality Standards

- **Evidence Before Claims:** Every architectural pattern is backed by executable tests, reproducible pipelines, and concrete codebase implementations.
- **Human-in-the-Loop (HITL) Gate:** Autonomous agents are restricted from merging code into primary branches; production deployments require manual human review and signed gates.
- **Zero-Trust Workload Isolation:** Sandboxed execution environments with Deny-All egress policies, strict memory clamps, and ephemeral credential lifecycles.
- **Architectural Traceability:** AST-driven codebase knowledge graphs (`graphify`), strict ISO/IEC/IEEE 42010 viewpoint mapping, and automated living documentation.

---

<div align="center">

📍 Bilbao, Basque Country, Spain / Remote  
🔗 [Website](https://lgcorzo.github.io/) • [LinkedIn](https://www.linkedin.com/in/lgcorzo/) • [Curriculum Knowledge Base](https://notebook.google.com/notebook/ea63f8a7-1f9d-4326-8222-9e4429f37f90) • [Dark Gravity Architecture](https://notebook.google.com/notebook/116d5f03-2fb0-4fa7-bd7c-1c9849920abc)

</div>

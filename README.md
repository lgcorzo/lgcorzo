# Luis Galo Corzo (`@lgcorzo`)

<div align="center">

[![Rust](https://img.shields.io/badge/Rust-1.80%2B-black?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Go](https://img.shields.io/badge/Go-1.22%2B-00ADD8?style=flat-square&logo=go&logoColor=white)](https://golang.org/)
[![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-GitOps-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![FluxCD](https://img.shields.io/badge/FluxCD-GitOps%20v2-5B45E1?style=flat-square&logo=flux&logoColor=white)](https://fluxcd.io/)
[![SIMD](https://img.shields.io/badge/Hardware%20SIMD-AVX--512%20%7C%20ARM64-FF6F00?style=flat-square)](https://github.com/lgcorzo)
[![Dark Gravity](https://img.shields.io/badge/Autonomous%20Factory-Dark%20Gravity-blueviolet?style=flat-square)](https://github.com/lgcorzo/rust_CACD_autonomous_factory)
[![ISO Standards](https://img.shields.io/badge/Architecture-ISO%2042010%20%7C%2015289-2E7D32?style=flat-square)](https://github.com/lgcorzo)
[![Security Status](https://img.shields.io/badge/Secret%20Scanning-100%25%20Clean-success?style=flat-square&logo=github)](https://github.com/lgcorzo)

**Systems & AI Architect | Autonomous Software Factories | Sovereign Cloud-Native Infrastructure | Enterprise MLOps/LLMOps**

</div>

---

## 🔭 Executive Technical Overview

Architect and systems engineer specializing in the intersection of **low-level systems (Rust, hardware SIMD acceleration, distributed storage)**, **cloud-native infrastructure (Kubernetes, FluxCD GitOps, zero-trust security)**, and **frontier autonomous artificial intelligence (Autonomous Agent Factories, Spec-Driven Development, and Production RAG systems)**.

Dedicated to building resilient, sovereign, and self-remediating architectures where autonomous agents operate under strict formal specifications, verifiable non-human identities, and audited boundaries.

---

## 🏛️ Core Architectural Pillars

### 1. 🦀 Autonomous Software Factories & Systems in Rust
- **[Dark Gravity (`rust_CACD_autonomous_factory`)](https://github.com/lgcorzo/rust_CACD_autonomous_factory):** Autonomous Continuous Architecture & Continuous Delivery (CA/CD) software factory in Rust. Built on Hatchet DAG orchestration, Ed25519-signed Non-Human Identity (NHI) verifiable credentials, and isolated sandboxed execution. *(Explore the comprehensive [Dark Gravity Architecture Knowledge Base](https://notebook.google.com/notebook/116d5f03-2fb0-4fa7-bd7c-1c9849920abc))*.
- **[Jules Remediator (`Jules_remediator`)](https://github.com/lgcorzo/Jules_remediator):** Autonomous Kubernetes remediation engine. Subscribes to FluxCD alert webhooks, applies DDD-driven error classification, triggers remediation runs via Jules SDK, and audits every outcome in MLflow.
- **Modular Agent Ecosystem:** Active development and tooling in Rust (`adk-rust`, `rig`, `deepwiki-rs`) for frontier LLM orchestration with native real-time memory and execution pipelines.

### 2. 🛡️ Sovereign Dependencies & Critical Infrastructure for Dark Gravity
> **Why Sovereign Forks?** The [Dark Gravity Autonomous Factory](https://notebook.google.com/notebook/116d5f03-2fb0-4fa7-bd7c-1c9849920abc) requires complete, non-negotiable **technological sovereignty** over its runtime dependencies. When critical upstream projects face commercial license closures (such as MinIO moving away from open source), vendor lock-in risks, or unpatched vulnerabilities, Dark Gravity eliminates supply-chain fragility by maintaining **independent, sovereign forks**.
> 
> In these forks, **security is continuously audited, upstream errors and bugs are resolved independently, and CVEs are remediated directly**, guaranteeing the quality, isolation, and uninterrupted operational autonomy of Dark Gravity.

- **Sovereign Object Storage Engine:** Fully decoupled and self-hosted S3 storage tier deployed on Kubernetes ([`minio`](https://github.com/lgcorzo/minio), [`operator`](https://github.com/lgcorzo/operator), [`directpv`](https://github.com/lgcorzo/directpv), [`kes`](https://github.com/lgcorzo/kes), [`mc`](https://github.com/lgcorzo/mc), [`console`](https://github.com/lgcorzo/console)) ensuring persistent artifact storage without third-party licensing dependencies.
- **Hardware SIMD Vectorization Toolchain (AVX-512 & ARM64):** Independent maintenance and assembly optimization of high-throughput Go cryptographic and parsing primitives:
  - [`sha256-simd`](https://github.com/lgcorzo/sha256-simd): Up to 8x acceleration on AVX-512 and ARM64 extensions (>3 GB/s per core).
  - [`highwayhash`](https://github.com/lgcorzo/highwayhash): Native assembly hashing exceeding 10 GB/s per core.
  - [`simdjson-go`](https://github.com/lgcorzo/simdjson-go): Gigabit-per-second JSON stream parsing for real-time pipeline telemetry.
  - [`md5-simd`](https://github.com/lgcorzo/md5-simd), [`blake2b-simd`](https://github.com/lgcorzo/blake2b-simd), [`crc64nvme`](https://github.com/lgcorzo/crc64nvme): NVMe-speed integrity checksums.
  - [`sio`](https://github.com/lgcorzo/sio): Data At Rest Encryption (DARE) authenticated encryption format for secure data pipelines.

### 3. 🧠 Enterprise MLOps & LLMOps Architecture
- **[`llmops-python-package`](https://github.com/lgcorzo/llmops-python-package):** Enterprise template for production LLM operations conforming to ISO/IEC/IEEE 42010:2022 and ISO/IEC/IEEE 15289:2019, with OpenWiki automated documentation.
- **[`mlops-python-package`](https://github.com/lgcorzo/mlops-python-package):** Standardized MLOps package foundation integrating DVC, MLflow tracking, Hydra configurations, and automated CI/CD quality gates.
- **[`fastapi-autogen-team`](https://github.com/lgcorzo/fastapi-autogen-team):** Microservice deploying AutoGen multi-agent teams with OpenAI-compatible FastAPI endpoints and Kubernetes deployments.

### 4. ⚡ Production-Ready Agentic RAG Systems
- **[`R2R-Engine`](https://github.com/lgcorzo/R2R-Engine):** State-of-the-art multimodal Retrieval-Augmented Generation (RAG) platform with agentic workflows, REST API, and hybrid knowledge graph indexing.
- **[`R2R-Application`](https://github.com/lgcorzo/R2R-Application):** Full-stack Next.js and React administrative dashboard for R2R observability, pipeline tuning, and interaction.

### 5. 📐 Spec-Driven Development (SDD) & Agentic Discipline
- **[`speckit-superpowers-bridge`](https://github.com/lgcorzo/speckit-superpowers-bridge):** Architectural bridge uniting Spec-Driven Development (Spec Kit - defining WHAT via formal specs) with disciplined autonomous execution (Superpowers - enforcing HOW through TDD, isolated Git worktrees, and subagent review).

### 6. ☸️ Cloud-Native GitOps & Zero-Trust Infrastructure
- **[`gitops_internal_lgcorzo`](https://github.com/lgcorzo/gitops_internal_lgcorzo):** Enterprise Kubernetes infrastructure managed strictly via GitOps (FluxCD v2), sealed secrets (Bitnami kubeseal), network isolation, and automated vulnerability scanning (Trivy).

---

## 🌟 Flagship Repositories

| Repository | Focus & Architecture | Stack |
| :--- | :--- | :--- |
| [**rust_CACD_autonomous_factory**](https://github.com/lgcorzo/rust_CACD_autonomous_factory) | Autonomous CA/CD Agent Factory, DAG workflows & sandboxed code generation | `Rust` `Hatchet` `Docker` `OpenWiki` |
| [**speckit-superpowers-bridge**](https://github.com/lgcorzo/speckit-superpowers-bridge) | Handoff bridge between Spec Kit (SDD) and Superpowers execution discipline | `Shell` `PowerShell` `Spec-Kit` `Superpowers` |
| [**Jules_remediator**](https://github.com/lgcorzo/Jules_remediator) | Autonomous Kubernetes remediation triggered by FluxCD webhooks & logged to MLflow | `Rust` `Kubernetes` `FluxCD` `MLflow` `DDD` |
| [**llmops-python-package**](https://github.com/lgcorzo/llmops-python-package) | Production LLMOps template conforming to ISO 42010 & OpenWiki documentation | `Python` `Poetry` `MLflow` `OpenWiki` |
| [**R2R-Engine**](https://github.com/lgcorzo/R2R-Engine) | Advanced agentic multimodal RAG engine with hybrid graph retrieval | `Python` `FastAPI` `PostgreSQL` `Vector DB` |
| [**minio**](https://github.com/lgcorzo/minio) / [**sha256-simd**](https://github.com/lgcorzo/sha256-simd) | Sovereign S3 storage engine & AVX-512 hardware-accelerated primitives for Dark Gravity | `Go` `Assembly` `AVX-512` `ARM64` `Kubernetes` |

---

## 🔒 Security & Quality Posture

- **Secret Scanning:** 100% clean across all 72 repositories (0 exposed credentials, API tokens, or private keys).
- **Autonomous Supply Chain Hardening:** Sovereign maintenance of foundational dependencies to insulate core factories from upstream licensing changes and unpatched bugs.
- **Branch Protection & HITL:** Strict Human-in-the-Loop policies requiring green CI/CD gates, linter verification, and manual approval for production merges.
- **Traceability & AST Documentation:** Automated code knowledge graphs (`graphify`), Abstract Syntax Tree extraction, and strict ISO viewpoint alignment.

---

<div align="center">

📍 Basque Country / Remote  
🔗 [GitHub Profile](https://github.com/lgcorzo) • [Curriculum Knowledge Base](https://notebook.google.com/notebook/ea63f8a7-1f9d-4326-8222-9e4429f37f90) • [Dark Gravity Architecture](https://notebook.google.com/notebook/116d5f03-2fb0-4fa7-bd7c-1c9849920abc)

</div>

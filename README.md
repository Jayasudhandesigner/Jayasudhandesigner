# Jayasudhan M
**Founding AI Product Manager at TS Techy | B.Tech in AI & Data Science**

[![Profile Views](https://komarev.com/ghpvc/?username=Jayasudhandesigner&label=Profile+Views&color=0e75b6&style=flat)](https://github.com/Jayasudhandesigner)
[![GitHub Stars](https://img.shields.io/github/stars/Jayasudhandesigner?style=flat&color=FFD700&label=Total%20Stars)](https://github.com/Jayasudhandesigner?tab=repositories)
[![PyPI Package](https://img.shields.io/pypi/v/pygenguard?color=38BDF8&label=PyGenGuard)](https://pypi.org/project/pygenguard/)
[![PM Artifacts](https://img.shields.io/badge/PM_Artifacts-PRDs_%26_Evals-blue)](https://github.com/Jayasudhandesigner/pm-artifacts)

> **AI Product Manager who specs and ships non-deterministic AI systems & agents.**  
> I write specifications for probabilistic software, design eval-first benchmarks, and leverage AI-assisted "vibe coding" tools to ship production prototypes at extreme velocity.

---

### 🛠️ Tech Stack & AI PM Capabilities

#### 🧠 AI Product Management Stack
* **Probabilistic PRDs & System Specs**: Fallback architectures, confidence thresholds, error budgets, HITL (Human-in-the-Loop) escalation paths.
* **Eval-First Development & LLMOps**: Quantitative benchmarking (RAGAS, DeepEval), grounding accuracy, hallucination tracking, p95 latency & token cost optimization.
* **AI Security & Governance**: PII / CCPA compliance, prompt injection defense, risk stratification engines, EU AI Act & NIST AI RMF audit trails.

#### 💻 Technical Stack
[![My Skills](https://skillicons.dev/icons?i=python,fastapi,tensorflow,pytorch,docker,aws,postgres,redis,react,git,github,linux&perline=6)](https://skillicons.dev)
* **Backend & AI Ops**: Python, FastAPI, TensorFlow, PyTorch, Docker, AWS (EC2/Free Tier), PostgreSQL, Redis, React.

#### ⚡ Shipping Advantage (AI-Assisted "Vibe Coding" Stack)
* **Tools**: `Cursor`, `Claude 3.7 / Sonnet`, `Antigravity IDE`, `GitHub Copilot`, `v0.dev`, `Bolt.new`
* **Product Impact**: I don't just write PRDs and wait for engineering cycles. I leverage state-of-the-art AI coding tools to personally build, test, and deploy functional prototypes, runtime guardrails, and MLOps pipelines in days.

---

## 🚀 Featured Products & Systems

#### 🌾 [Poultra7](https://poultra7.com) — Poultry Industry B2B Escrow Platform
- **Problem**: Poultry input sellers (feed mills, chicken hatcheries, veterinary medicine distributors) face payment delays, paper documentation friction, and default risks when transacting with small and medium farms on informal credit.
- **My Decision**: Built Poultra7 as a digital escrow agent. The system holds buyer funds, automates transaction paperwork, and executes release triggers upon delivery confirmation so small sellers do not risk working capital or waste time managing paperwork.
- **User & Target Market**: Small and medium poultry input sellers and buyers across India.
- **Live Site**: [poultra7.com](https://poultra7.com)

---

#### 🛡️ [PyGenGuard](https://github.com/Jayasudhandesigner/pygenguard) — GenAI Governance Middleware Framework
*Published Package on [PyPI (v0.2.0)](https://pypi.org/project/pygenguard/)*

- **Problem**: Enterprises deploying GenAI into production face prompt injections, session hijacking, PII leaks, and unmanaged token burn rates ("denial-of-wallet").
- **My Decision**: Designed deterministic, offline security middleware evaluating requests across 5 security planes (*Identity*, *Intent*, *Context*, *Economics*, *Compliance*) **before** hitting the LLM API. 
- **Key Mechanics**:
  - **Deterministic Rule Checks**: 0.1ms per plane execution without model inference latency or external API dependencies.
  - **Identity Fingerprinting**: Cryptographic hash of IP + User-Agent + TLS fingerprint; penalizes trust score by 50 points on session drift to prevent hijacking.
  - **Structured Audit Logging**: Outputs JSON audit traces tagged for **EU AI Act (Article 13)** and **NIST AI RMF (GV-3)** compliance.
  - **Extensibility**: Includes `AsyncGuard` for FastAPI, Redis session store adapter, and a `BasePlane` plugin architecture.

---

#### 🩺 [Clinical Trial Risk Prediction Platform](https://github.com/Jayasudhandesigner/MLOps-System-for-Clinical-Trial-Risk-Prediction) — MLOps Patient Retention System
*Container Image on [Docker Hub](https://hub.docker.com/r/sudhan2004/clinical-dropout-api)*

- **Problem**: Clinical trial coordinators discover patient dropouts reactively after missed visits, incurring replacement costs up to tens of thousands of dollars per participant.
- **My Decision**: Built an end-to-end MLOps pipeline featuring a 3-tier cost-weighted risk stratification engine (`Low <40%`, `Medium 40-80%`, `Critical >80%`) to trigger targeted interventions before dropouts happen.
- **Key Metrics & Tradeoffs**:
  - **Stratified Intervention Budgeting**: $0.50 automated SMS alert for low risk, $45 clinical consultation for medium risk, and $500 dedicated retention team deployment for critical risk.
  - **Model Accuracy**: **85% dropout prediction accuracy**.
  - **Infrastructure Optimization**: Reduced Docker image size from **3 GB to 655 MB (78% reduction)** for low-cost cloud hosting on AWS Free Tier (`t2.micro`) with **<100ms API latency**.

---

## 🧠 How I Work

> **PRDs for Non-Deterministic Systems**  
> I write specifications for AI products around probabilistic behavior, confidence limits, fallback triggers, and error budgets — not static wireframes.

> **Eval-First Development**  
> Every feature requires quantitative baselines tracking grounding accuracy, hallucination rates, latency, and cost per task across iterations.

> **Defensible Product Decisions**  
> I document what was chosen, what was rejected, and the trade-offs between false positives and false negatives for end users.

---

<div align="center">

**📁 [Explore PM Artifacts — PRDs, Eval Reports & Product Teardowns](https://github.com/Jayasudhandesigner/pm-artifacts)**

</div>

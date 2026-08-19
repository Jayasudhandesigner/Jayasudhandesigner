<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=160&section=header&text=Jayasudhan%20M&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=AI%20Product%20Manager%20%E2%80%94%20specs%20%26%20ships%20non-deterministic%20AI%20agents&descAlignY=60&descColor=38BDF8&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=38BDF8&center=true&vCenter=true&width=700&lines=Founding+AI+Product+Manager+%40+TS+Techy;B.Tech+AI+%26+Data+Science+%E2%80%94+Graduated+June+2026;I+build+what+I+spec.+I+measure+what+I+ship." alt="Typing SVG" />

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Jayasudhandesigner&label=Profile+Views&color=0e75b6&style=flat)

</div>

---

## 🧭 Who I Am

I am an AI Product Manager who specs and ships systems that operate under non-deterministic conditions — AI security middleware, clinical risk engines, and enterprise software. I focus on real user problems, clear risk thresholds, and auditable metrics.

I am applying to AI PM, AI Product Owner, and Associate PM roles in India and Europe (Google, Microsoft, JPMorganChase, Hawk AI, and similar). My PM artifacts — PRDs, eval reports, and teardowns — are compiled in [`pm-artifacts`](https://github.com/Jayasudhandesigner/pm-artifacts).

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

## 🛠️ Stack

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=python,fastapi,tensorflow,docker,aws,react,postgres,git,github,linux&perline=5)](https://skillicons.dev)

</div>

---

## 📊 GitHub Activity

<div align="center">

<img height="155" src="https://github-readme-stats.vercel.app/api?username=Jayasudhandesigner&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
&nbsp;
<img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jayasudhandesigner&layout=compact&theme=tokyonight&hide_border=true&langs_count=5" />

</div>

---

## 🐍 Contribution Graph

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Jayasudhandesigner/Jayasudhandesigner/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Jayasudhandesigner/Jayasudhandesigner/output/github-snake.svg" />
    <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/Jayasudhandesigner/Jayasudhandesigner/output/github-snake.svg" />
  </picture>
</div>

---

<div align="center">

**📁 [Explore PM Artifacts — PRDs, Eval Reports & Product Teardowns](https://github.com/Jayasudhandesigner/pm-artifacts)**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

</div>

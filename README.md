<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=160&section=header&text=Jayasudhan%20M&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=AI%20Product%20Manager%20%E2%80%94%20specs%20%26%20ships%20non-deterministic%20AI%20agents&descAlignY=60&descColor=38BDF8&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=38BDF8&center=true&vCenter=true&width=700&lines=Founding+AI+Product+Manager+%40+TS+Techy;B.Tech+AI+%26+Data+Science+%E2%80%94+Graduated+June+2026;I+build+what+I+spec.+I+measure+what+I+ship." alt="Typing SVG" />

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Jayasudhandesigner&label=Profile+Views&color=0e75b6&style=flat)

</div>

---

## 🧭 Who I Am

I am an AI Product Manager who writes specs for systems that are probabilistic by design — agents that hallucinate, pipelines that drift, models that degrade under load. I care about three things: the problem being real, the metric being honest, and the failure mode being documented before it hits a user.

I am applying to AI PM and Associate PM roles in India and Europe (Google, Microsoft, JPMorganChase, Hawk AI, and similar). My PM artifacts — PRDs, eval reports, product teardowns — are in the [`pm-artifacts`](https://github.com/Jayasudhandesigner/pm-artifacts) repo.

---

## 🚀 What I Have Built

#### 🌾 [Poultra7](https://poultra7.com) — Poultry Industry B2B Escrow Platform
The poultry supply chain in India runs on informal trust — feed suppliers, chicken farms, and medicine sellers transact without contracts, guarantees, or dispute resolution. When a deal goes wrong, the smaller seller absorbs the loss.

I built Poultra7 to act as a digital escrow agent for small and medium sellers across the poultry value chain. The platform handles transaction paperwork, payment holding, and release triggers so that sellers can trade without chasing buyers or drowning in manual documentation.

- **User**: Small-to-medium poultry input sellers (feed, medicine, equipment)
- **Core mechanism**: Escrow-backed transaction flow with automated release conditions
- **Problem it replaced**: Phone-call-based trust, paper receipts, zero recourse on default
- **Live at**: [poultra7.com](https://poultra7.com)

---

#### 🛡️ [PyGenGuard](https://github.com/Jayasudhandesigner/pygenguard) — GenAI Runtime Governance Layer
*Live on [PyPI](https://pypi.org/project/pygenguard/)*

Enterprises deploying LLMs in regulated environments face a compliance gap: the model is not deterministic, but compliance is. PII leaks, prompt injections, and unpredictable token costs are not edge cases — they are design-time risks that need a policy layer.

PyGenGuard sits between your application and the LLM. It enforces intent validation, CCPA-aligned PII detection, prompt injection blocking, and cost budgets before any token reaches the model. All policies are deterministic and auditable.

- **Decision**: Enforce policies at the middleware layer, not inside the model — model behavior is not trustworthy enough to self-govern
- **What I rejected**: Prompt-level guardrails (too easy to jailbreak) and post-hoc filtering (too late for cost control)
- **Outcome**: >95% malicious prompt block rate at <5ms added latency; 40–60% token cost reduction via early rejection

---

#### 🩺 [MLOps System — Clinical Trial Risk Prediction](https://github.com/Jayasudhandesigner/MLOps-System-for-Clinical-Trial-Risk-Prediction) — Patient Dropout Prevention
Clinical trial coordinators operate reactively. By the time a patient misses a visit, the dropout has already happened. The question is not "did this patient drop out?" — it is "which patients are at risk right now, and who should I call first?"

This is a full MLOps system — training pipeline, serving layer, drift monitoring, and CI/CD — built around a 3-tier risk stratification model. The threshold decision is the most important product choice: I optimized for recall over precision, because a false negative (missing a high-risk patient) is more damaging than a false positive (unnecessary coordinator outreach).

- **Decision**: High recall threshold — coordinator time is cheaper than a patient lost to trial
- **What I rejected**: Balanced F1 optimization, which treats coordinator time and patient retention as equal costs — they are not
- **Outcome**: 85% dropout prediction accuracy; 78% Docker image size reduction via multi-stage builds

---

## 🧠 How I Work

**PRDs for Non-Deterministic Systems**
I write specs that define fallback paths, confidence thresholds, and error budgets. A spec that only describes the happy path is not a spec.

**Eval-First Development**
Nothing ships without a baseline. I track grounding accuracy, hallucination rate, p95 latency, and cost per resolved task — and I publish the v1 numbers even when they are embarrassing.

**Honest Tradeoffs**
Every product decision is a tradeoff. I name what I chose, what I rejected, and who bears the cost of each failure mode.

---

## 🛠️ Stack I Work With

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

**📁 [PM Artifacts — PRDs, Eval Reports, Product Teardowns](https://github.com/Jayasudhandesigner/pm-artifacts)**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

</div>

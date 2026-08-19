# Jayasudhan M
**AI Product Manager who specs and ships non-deterministic systems.**

Founding AI Product Manager at TS Techy | B.Tech in AI & Data Science (Graduating June 2026)

<img src="https://capsule-render.vercel.app/api?type=waving&color=1e1e2e&height=120&section=header&text=AI%20Product%20Manager%20Portfolio&fontSize=28&fontColor=cdd6f4" width="100%"/>

---

### Pinned Projects & Product Decisions

| Project | Problem it Solves | My Decision | Outcome |
| :--- | :--- | :--- | :--- |
| **[PyGenGuard](https://github.com/Jayasudhandesigner/PyGenGuard)** | LLMs in regulated enterprise environments leak PII, accept prompt injections, and generate unpredictable token costs. | Built deterministic runtime governance middleware enforcing intent, PII/CCPA compliance, and injection blocking before model invocation. | >95% malicious-prompt block rate at <5ms overhead; 40–60% token cost reduction via early rejection. Live on PyPI. |
| **[Clinical Trial Risk Prediction Platform](https://github.com/Jayasudhandesigner/clinical-trial-risk)** | Clinical trial coordinators miss early warning signs of patient dropouts before manual intervention is possible. | Designed a 3-tier risk stratification engine prioritized for high recall, accepting false positives to protect patient retention. | 85% dropout-risk prediction accuracy; 78% Docker image size reduction. [MEASURE: Coordinator intervention lead time] |
| **[Enterprise RAG Intelligence (Groq)](https://github.com/Jayasudhandesigner/enterprise-rag-groq)** | Multi-document enterprise search lag (>2s) breaks user focus during live analysis sessions. | Capped retrieval depth and optimized reranking pipeline to prioritize sub-second latency over marginal recall gains. | Cut p90 response latency from 2.1s to 0.9s across 75+ concurrent sessions. [MEASURE: Task completion rate change] |
| **[AI Appointment Automation Engine](https://github.com/Jayasudhandesigner/appointment-automation-engine)** | Patient booking via WhatsApp/voice fails during ambiguous requests, lost slots, or silent drop-offs. | Enforced strict human-in-the-loop (HITL) fallback triggers whenever slot availability or intent confidence drops below threshold. | Zero unhandled conversational dead-ends in end-to-end multi-channel pilot. [MEASURE: HITL escalation rate %] |
| **[Multi-Agent Orchestration System](https://github.com/Jayasudhandesigner/langgraph-multi-agent-triage)** | Single-prompt LLMs collapse under multi-step domain workflows (alert triage & routing). | Architected a LangGraph supervisor-agent layout with bounded state retries, typed outputs, and execution tracing. | Achieved deterministic step routing. [MEASURE: Task success rate vs single-prompt baseline %] |
| **[LLM Evaluation Harness & Report](https://github.com/Jayasudhandesigner/llm-eval-harness)** | GenAI product regressions and hallucinations pass unnoticed without continuous quantitative benchmarking. | Implemented an eval-first harness (RAGAS/DeepEval) tracking task completion, grounding, hallucination, latency, and cost per task. | Established production eval baseline; drove grounding accuracy from [MEASURE: v1 %] to [MEASURE: v2 %]. |
| **[FlixMood Recommender](https://github.com/Jayasudhandesigner/FlixMood)** | Cold-start users receive generic recommendations when mood context is missing. | Paired Matrix Factorization (SVD) with item feature vectors (TF-IDF) for hybrid mood-aware filtering. | [MEASURE: Precision@K and cold-start coverage rate] |

---

### How I Work

- **PRDs for Non-Deterministic Systems**: I define probabilistic feature specs around fallback paths, confidence boundaries, and error budgets—not static wireframes.
- **Eval-First Development**: Features don't ship without quantitative eval baselines measuring grounding, hallucination rate, latency, and cost per task.
- **Shipping Velocity**: I reduce scope to core decision boundaries and test hypotheses using functional prototypes built in days.

---

### Portfolio & Contact

- **PM Artifacts Repo (PRDs, Eval Reports, Product Teardowns, Metrics Case Study)**: [`pm-artifacts`](https://github.com/Jayasudhandesigner/pm-artifacts)
- **LinkedIn**: [linkedin.com/in/jayasudhanm]([NEED: LinkedIn profile URL])
- **Email**: [NEED: Professional email address]

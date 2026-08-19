# Jayasudhan M

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&lines=Jayasudhan+M;AI+Product+Manager;I+spec+and+ship+non-deterministic+AI+agents." alt="Typing SVG" />
  
  <p><b>Founding AI Product Manager at TS Techy</b> • B.Tech in AI & Data Science (Graduating June 2026)</p>

  <a href="https://github.com/Jayasudhandesigner/pm-artifacts"><b>📁 Explore PM Artifacts (PRDs & Eval Reports) »</b></a>
</div>

---

### 🚀 Pinned Projects & Product Decisions

#### 🛡️ 1. [PyGenGuard](https://github.com/Jayasudhandesigner/PyGenGuard) — GenAI Governance Middleware
* **Problem**: Regulated enterprises cannot adopt LLMs due to PII leaks, prompt injections, and unmanaged token budgets.
* **My Decision**: Built deterministic runtime governance middleware enforcing intent, CCPA safety, and early injection blocking prior to model execution.
* **Outcome**: **>95% malicious prompt block rate** at **<5ms overhead**, cutting token costs by **40–60%**. *(Live on PyPI)*

#### 🩺 2. [Clinical Trial Risk Platform](https://github.com/Jayasudhandesigner/clinical-trial-risk) — Patient Retention Engine
* **Problem**: Coordinators miss early dropout signals before manual intervention is possible.
* **My Decision**: Architected a 3-tier risk stratification model prioritized for high recall—accepting false positives to safeguard retention.
* **Outcome**: **85% dropout prediction accuracy** & **78% Docker size reduction**. `[MEASURE: Coordinator intervention lead time]`

#### ⚡ 3. [Enterprise RAG Intelligence](https://github.com/Jayasudhandesigner/enterprise-rag-groq) — Sub-Second Multi-Doc Search
* **Problem**: 2.1s query latency killed user focus during multi-document search sessions.
* **My Decision**: Capped retrieval depth and optimized reranking pipeline to prioritize latency over marginal recall gains.
* **Outcome**: Cut p90 response time **2.1s → 0.9s** across 75+ concurrent sessions. `[MEASURE: Task completion impact]`

#### 💬 4. [AI Appointment Automation Engine](https://github.com/Jayasudhandesigner/appointment-automation-engine) — Multi-Channel Patient Booking
* **Problem**: Multi-turn patient scheduling fails on ambiguous requests, disappearing slots, or silent drop-offs.
* **My Decision**: Enforced explicit confidence thresholds that trigger human-in-the-loop (HITL) escalation before booking failure occurs.
* **Outcome**: Zero unhandled conversational dead-ends in multi-channel pilot. `[MEASURE: HITL escalation rate %]`

#### 🤖 5. [Multi-Agent Orchestration System](https://github.com/Jayasudhandesigner/langgraph-multi-agent-triage) — Alert & Triage Router
* **Problem**: Single-prompt LLMs fail under multi-step domain workflows (financial crime / alert triage).
* **My Decision**: Designed a LangGraph supervisor-agent graph with bounded state retries, typed schemas, and execution tracing.
* **Outcome**: Deterministic step routing & execution visibility. `[MEASURE: Success rate vs single-prompt baseline %]`

#### 📊 6. [LLM Evaluation Harness](https://github.com/Jayasudhandesigner/llm-eval-harness) — Quantitative GenAI Benchmarking
* **Problem**: Model regressions and prompt hallucinations pass unnoticed without continuous evaluation.
* **My Decision**: Built an eval-first harness (RAGAS / DeepEval) tracking grounding, hallucination, latency, and cost per task across releases.
* **Outcome**: Baseline failure audit; improved grounding accuracy from `[MEASURE: v1 %]` to `[MEASURE: v2 %]`.

#### 🎬 7. [FlixMood Recommender](https://github.com/Jayasudhandesigner/FlixMood) — Hybrid Mood Filtering
* **Problem**: Standard recommenders fail cold-start users without mood context.
* **My Decision**: Combined Matrix Factorization (SVD) with item feature vectors (TF-IDF) for mood-aware hybrid filtering.
* **Outcome**: `[MEASURE: Precision@K & cold-start coverage rate]`

---

### 🧠 How I Work

> **PRDs for Non-Deterministic Systems**  
> I define probabilistic feature specs around fallback paths, confidence boundaries, and error budgets—not static wireframes.

> **Eval-First Development**  
> Features don't ship without quantitative eval baselines measuring grounding, hallucination rate, latency, and cost per task.

> **Shipping Velocity**  
> I reduce scope to core decision boundaries and test hypotheses using functional prototypes built in days.

---

<div align="center">
  <p><b>Connect with me:</b></p>
  <a href="https://github.com/Jayasudhandesigner/pm-artifacts"><b>📄 PM Artifacts Repo</b></a> • 
  <a href="[NEED: LinkedIn profile URL]"><b>LinkedIn</b></a> • 
  <a href="mailto:[NEED: Email]"><b>Email</b></a>
</div>

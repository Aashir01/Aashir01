<!-- ═══════════════════════════ BANNER ═══════════════════════════ -->
<p align="center">
  <img src="https://raw.githubusercontent.com/Aashir01/Aashir01/main/assets/banner.svg" alt="Aashir Noman, AI Engineer working on agentic systems and applied ML" width="100%" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Aashir01/Aashir01/main/assets/tagline.svg" alt="I build LLM systems that hold up in production. Agent orchestration, retrieval, guardrails, evals. 820 tests across six shipped systems. Open to remote AI Engineering roles." width="760" />
</p>

<!-- ═══════════════════════════ LINKS ═══════════════════════════ -->
<p align="center">
  <a href="https://aashirnoman.dev"><img src="https://img.shields.io/badge/Portfolio-38BDAE?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/aashir-noman-138820152"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://www.upwork.com/freelancers/aashir1"><img src="https://img.shields.io/badge/Upwork-6FDA44?style=for-the-badge&logo=upwork&logoColor=white" alt="Upwork"/></a>
  <a href="https://orcid.org/0009-0004-2126-5419"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"/></a>
  <a href="mailto:azac965@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## What I do

I build **LLM systems that get to touch real money, real patients and real decisions.** Most of my actual work has very little to do with prompting. It goes into the deterministic fallbacks, the spend limits, the injection boundaries, the approval gates, and the eval suites that fail a build when accuracy slips.

```yaml
name:       Aashir Noman
role:       AI / ML Engineer  ·  agentic systems, retrieval, applied ML
stack:      Python · FastAPI · LangGraph · Claude · Postgres · Docker
location:   Pakistan (UTC+5). Remote-first, full EU overlap, US mornings
status:     Open to remote AI/ML roles and long-term contracts
```

- 🏗️ Six production systems in the open, with **820 tests** between them. Engines, guardrails and eval suites, not notebooks.
- 🛡️ Most of my work sits in the **trust layer**: prompt-injection defence, signed execution, spend ceilings, human approval, honest statistics.
- 🏆 **Top Rated** on Upwork, delivering AI/ML work for international clients since 2023.
- 🌍 Former **Omdena** collaborator on the Sri Lankan Autism Prediction Project (2023-2024).
- 📊 Active on Kaggle. My March Machine Learning Mania entry used Elo ratings, Massey Ordinals and temperature-scaled ensembles.

---

## 🚀 Flagship Work

> Six systems, 820 tests between them. Every count comes from that repo's own suite.
> Five of the six run end to end with no API key, on deterministic or synthetic fallbacks.

<table>
<tr>
<td width="50%" valign="top">

### 🚢 Meridian: Autonomous Logistics Control Plane
An agent mesh that watches ports, vessels and inventory, spots disruptions, and executes a response against ERP/TMS/WMS. It works inside limits no model can talk its way past.

**Why it's hard:** the graph is *cyclic*. A Resilience Analyst can veto the Broker's diversion and send the decision back, rather than moving the bottleneck somewhere worse.

`Tiered autonomy` · `Ed25519-signed execution` · `Monte Carlo CVaR₉₀ ranking`
`Brandes betweenness + cascade sim` · `3-layer injection quarantine`

**Stack:** Python · Claude (Haiku triage / Opus planning) · FastAPI · Kafka · TimescaleDB · React

![tests](https://img.shields.io/badge/tests-185-38BDAE?style=flat-square)
![license](https://img.shields.io/badge/license-Apache--2.0-4B5563?style=flat-square)
[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Aashir01/Supply-Chain-and-Logistics-Agentic-system)

</td>
<td width="50%" valign="top">

### 🛡️ VisaGuard: Visa Document Intelligence
Scans a visa application bundle and reports what's wrong before the consulate does: missing documents, name mismatches across files, insufficient funds, expired cover, non-compliant photos.

**Why it's hard:** the Schengen refusal decoder is **deterministic and free**. Annex VI fixes eleven numbered grounds, so it matches official wording rather than guessing with a model. Decoded refusals then get graded against the check that preceded them, which turns real casework into a ranked work queue for the rule packs.

`11 corridors, provenance-tagged rules` · `ICAO 9303 MRZ check digits`
`Deterministic-first, 2-3 LLM calls per bundle` · `Hard per-check spend cap`

**Stack:** FastAPI · Next.js · Claude / DeepSeek · Tesseract · Fernet-encrypted PHI

![tests](https://img.shields.io/badge/tests-224-38BDAE?style=flat-square)
![cost](https://img.shields.io/badge/free%20tier-%240.00%2Fcheck-6E56CF?style=flat-square)
[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Aashir01/Visa-Check)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏥 Medical Insurance Appeals Bot
Reads denial letters, drafts legally grounded appeals, and routes every one to a licensed human before it leaves the building. The AI never sends anything on its own.

**Why it's hard:** the liability rule is enforced in **three independent layers** (role gate, authorization gate, delivery gate), and a test suite fails the build if any one of them regresses.

`LangGraph state machine` · `HIPAA / PHI-at-rest encryption` · `X12 835 EDI intake`
`Zero-downtime key rotation` · `Weighted extraction evals as a CI gate`

**Stack:** FastAPI · LangGraph · Claude · Postgres · Alembic · Fly.io / Render

![tests](https://img.shields.io/badge/tests-119-38BDAE?style=flat-square)
![HIPAA](https://img.shields.io/badge/HIPAA-documented-6E56CF?style=flat-square)
[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Aashir01/Medical-Insurance-Appeal-Bots)

</td>
<td width="50%" valign="top">

### 📖 Quran Research Agent
Deterministic retrieval and agentic research over a closed corpus of 6,236 ayat, 130k morphological segments and 1,651 roots. Ask for every occurrence of a root and you get **all 854**, computed in SQL, not the twenty most similar.

**Why it's hard:** scripture is rendered from Postgres via placeholders, never generated. An unresolvable reference fails visibly instead of producing plausible text.

`Exhaustive > probabilistic retrieval` · `Multiple-comparison correction by default`
`Violations serialised before support` · `MCP server (14 tools)`

**Stack:** FastAPI · PostgreSQL · Next.js PWA · LangGraph · MCP

![tests](https://img.shields.io/badge/tests-89-38BDAE?style=flat-square)
![eval](https://img.shields.io/badge/golden%20eval-53%20items-38BDAE?style=flat-square)
[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Aashir01/Quran-Research-Agent)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧰 mini-agent: A Coding Agent, Built to Be Read
The agent loop is about nine lines long. The machinery around it is the part that takes months, and this builds that machinery in six visible stages, across 12 model providers behind two wire protocols.

**Why it's hard:** the edit-application ladder. When the model's "replace X with Y" doesn't match byte-for-byte, progressively looser passes retry, but **each one must find exactly one match**. Ambiguity is always an error, never a guess.

`Schema-level plan mode (write tools absent, not blocked)` · `Shadow-git undo`
`Tool-result offloading + prefix-stable prompt caching` · `Monotonic verification ledger`

**Stack:** TypeScript · Node 22+ · Anthropic Messages + OpenAI Chat transports

![tests](https://img.shields.io/badge/tests-40-38BDAE?style=flat-square)
![license](https://img.shields.io/badge/license-MIT-4B5563?style=flat-square)
[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Aashir01/agent-cli)

</td>
<td width="50%" valign="top">

### 📈 MFIE: Macro-Informed Financial Intelligence Engine
Treats a chart pattern as a *hypothesis* and the macroeconomy as the *evidence*. A setup becomes a signal only after surviving a chain of econometric filters.

**Why it's hard:** the Market Cycle Compass corrects for **overlapping observations**. A factor scoring t = -7.3 uncorrected came out at t ≈ -0.9 once the correction was applied. On synthetic data it correctly reports *no measurable edge*.

`Asymmetric filters (veto freely, boost ≤1.25×)` · `Lead-aligned factor aggregation`
`Non-monotonic curve regime` · `Quarter-Kelly + portfolio CVaR budget`

**Stack:** Python · pandas/numpy (no TA-Lib) · SQLAlchemy · TimescaleDB · Streamlit

![tests](https://img.shields.io/badge/tests-163-38BDAE?style=flat-square)
![license](https://img.shields.io/badge/license-MIT-4B5563?style=flat-square)
[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Aashir01/Trading-Analyst)

</td>
</tr>
</table>

---

## 🧭 How I build AI systems

None of these are slogans. Each one is load-bearing in the repos above.

| Principle | Where it shows up |
|---|---|
| **Compute what code can compute.** | Distances, draft limits, legal driving hours and days-of-cover are arithmetic. The model only gets asked what code cannot settle, and infeasible options are filtered out *before* it ever sees them. |
| **Treat all external text as hostile.** | Vessel names, headlines and recalled memories reach prompts and none are written by the operator. Structural fencing → detective scoring → quarantine, backed by tests for what must *not* be flagged. |
| **Guardrails may only tighten.** | Tier rules can raise an action's tier, never lower it, so a new rule can never widen autonomy by accident. Spend ceilings and treasury caps are pure code. |
| **Degrade, never stop.** | Every system boots with no API key and no vendor: deterministic policies, synthetic providers, offline engines. You can evaluate the whole product before signing anything. |
| **Report the number chance predicts.** | Testing 1,651 roots at p<0.05 yields ~83 "findings" from noise. The correction is applied before results return. It isn't a switch anyone can turn off. |
| **Name the gaps.** | VisaGuard, MFIE, mini-agent and the Appeals Bot each close their README by naming what isn't built: unimplemented fax delivery, synthetic eval cases, unfitted thresholds. A tool that hides those is worse than no tool. |

---

## 🛠 Tech Stack

<table>
  <tr>
    <td valign="top"><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
    </td>
  </tr>
  <tr>
    <td valign="top"><b>LLM / Agents</b></td>
    <td>
      <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
      <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white"/>
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
      <img src="https://img.shields.io/badge/MCP-6E56CF?style=flat-square"/>
      <img src="https://img.shields.io/badge/Structured%20Outputs-6E56CF?style=flat-square"/>
      <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
      <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
      <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td valign="top"><b>Retrieval</b></td>
    <td>
      <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white"/>
      <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white"/>
      <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/BM25-4B5563?style=flat-square"/>
      <img src="https://img.shields.io/badge/Graph%20traversal-4B5563?style=flat-square"/>
    </td>
  </tr>
  <tr>
    <td valign="top"><b>ML / Data</b></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
      <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td valign="top"><b>Backend & Web</b></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square&logo=timescale&logoColor=black"/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
      <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td valign="top"><b>Infra & Tooling</b></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
      <img src="https://img.shields.io/badge/Alembic-6BA81E?style=flat-square&logo=sqlalchemy&logoColor=white"/>
      <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
      <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white"/>
      <img src="https://img.shields.io/badge/Fly.io-24175B?style=flat-square&logo=flydotio&logoColor=white"/>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
    </td>
  </tr>
</table>

---

<details>
<summary><b>📂 More work →</b></summary>

<br>

| Project | What it is | Tech |
|---|---|---|
| [DataSense AI](https://github.com/Aashir01/AI-Data-Analyst-Agent) | Full-stack SaaS data-analyst agent. Profiling, IsolationForest anomalies, forecasts, and chat-with-data behind a whitelisted query planner | Next.js, FastAPI, Postgres, Redis/RQ |
| [Enterprise AI Knowledge Assistant](https://github.com/Aashir01/Enterprise-AI-Knowledge-Assistant) | Production RAG assistant for enterprise document search, with hybrid retrieval, source-grounded answers and a containerised deploy | FastAPI, LangChain, FAISS/Qdrant |
| [El Madina Viajes](https://github.com/Aashir01/EL-MADINA-VIAJES) | Tour-booking platform: a dating/pricing engine that rebuilds a full itinerary around any departure date, shared by UI and API so they can't disagree | Next.js, TypeScript, Vitest |
| [Hierarchical Agent Swarm](https://github.com/Aashir01/hierarchical-agent-swarm) | Manager/worker tree coordinating 100+ agents, with results bubbling from leaves up to the root | Python |
| [Nexus Motion](https://github.com/Aashir01/nexus-motion-AI-video-agency) | Multi-agent pipeline automating end-to-end video production | Python, multi-agent |
| [Spain Appointment Bot](https://github.com/Aashir01/spain-visa-appointment-bot) | Appointment tracking and notification automation | Python |
| [March ML Mania 2026](https://github.com/Aashir01/-March-Machine-Learning-Mania-2026) | Kaggle tournament model using Elo, Pythagorean efficiency, Massey Ordinals and calibrated ensembles | Python, scikit-learn |
| [My Portfolio](https://github.com/Aashir01/My_Portfolio) | Personal site, live at [aashirnoman.dev](https://aashirnoman.dev) | TypeScript, React |
| [Deep Learning Projects](https://github.com/Aashir01/Deep-Learning-Projects) | Applied DL notebooks and experiments | Jupyter, PyTorch |

</details>

---

## 🤝 Let's work together

I'm open to **remote AI/ML engineering roles** and **long-term consulting work**, especially where an LLM system has to be trusted with something that matters. In practice that means agent orchestration, retrieval over proprietary corpora, guardrails and approval workflows, or evaluation infrastructure for a team that's shipping fast and flying blind.

**Good fit if you need:** an agent pipeline that degrades safely · retrieval that cites and refuses · evals that gate CI · a second opinion on where your LLM system will break.

<p align="center">
  <a href="https://linkedin.com/in/aashir-noman-138820152"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://aashirnoman.dev"><img src="https://img.shields.io/badge/View%20Portfolio-38BDAE?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:azac965@gmail.com"><img src="https://img.shields.io/badge/Send%20an%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <a href="https://github.com/Aashir01?tab=followers"><img src="https://img.shields.io/github/followers/Aashir01?label=Followers&style=flat-square&color=38BDAE" alt="Followers"/></a>
</p>

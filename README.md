<!-- ═══════════════════════════ BANNER ═══════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=Aashir%20Noman&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20Engineer%20%C2%B7%20Agentic%20Systems%20%C2%B7%20Applied%20ML&descAlignY=55&descSize=18" width="100%" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=800&color=38BDAE&center=true&vCenter=true&width=700&lines=I+build+LLM+systems+that+hold+up+in+production.;Agent+orchestration+%C2%B7+retrieval+%C2%B7+guardrails+%C2%B7+evals;550%2B+tests+across+four+flagship+systems.;Open+to+remote+AI+Engineering+roles." alt="Typing SVG" />
  </a>
</p>

<!-- ═══════════════════════════ LINKS ═══════════════════════════ -->
<p align="center">
  <a href="https://aashirnoman.online"><img src="https://img.shields.io/badge/Portfolio-38BDAE?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/aashir-noman-138820152"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://www.upwork.com/freelancers/aashir1"><img src="https://img.shields.io/badge/Upwork-6FDA44?style=for-the-badge&logo=upwork&logoColor=white" alt="Upwork"/></a>
  <a href="https://orcid.org/0009-0004-2126-5419"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"/></a>
  <a href="mailto:azac965@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## What I do

I build **LLM systems that are allowed to touch real money, real patients, and real decisions** — which means most of my work is the part that isn't the prompt: deterministic fallbacks, tiered autonomy limits, injection boundaries, human approval gates, and evaluation harnesses that fail the build.

```yaml
name:       Aashir Noman
role:       AI / ML Engineer  ·  agentic systems, retrieval, applied ML
stack:      Python · FastAPI · LangGraph · Claude · Postgres · Docker
location:   Pakistan (UTC+5) — remote-first, overlaps EU fully & US mornings
status:     Open to remote AI/ML roles and long-term contracts
```

- 🏗️ Four production-grade systems in the open, carrying **185 / 163 / 119 / 89 tests** respectively — engines, guardrails, and eval suites, not notebooks.
- 🛡️ Specialism in the **trust layer of AI systems**: prompt-injection defence, signed execution, spend ceilings, human-in-the-loop enforcement, honest statistics.
- 🏆 **Top Rated** on Upwork, delivering AI/ML work for international clients since 2023.
- 🌍 Former **Omdena** collaborator (Sri Lankan Autism Prediction Project, 2023–2024).
- 📊 Active on Kaggle — March Machine Learning Mania with Elo, Massey Ordinals, and temperature-scaled ensembles.

---

## 🚀 Flagship Work

<table>
<tr>
<td width="50%" valign="top">

### 🚢 Meridian — Autonomous Logistics Control Plane
An agent mesh that watches ports, vessels and inventory, detects disruptions, and executes a response against ERP/TMS/WMS — inside limits a model cannot talk its way past.

**Why it's hard:** the graph is *cyclic* — a Resilience Analyst can veto the Broker's diversion and send the decision back rather than moving the bottleneck somewhere worse.

`Tiered autonomy` · `Ed25519-signed execution` · `Monte Carlo CVaR₉₀ ranking`
`Brandes betweenness + cascade sim` · `3-layer injection quarantine`

**Stack:** Python · Claude (Haiku triage / Opus planning) · FastAPI · Kafka · TimescaleDB · React

![tests](https://img.shields.io/badge/tests-185-38BDAE?style=flat-square)
![license](https://img.shields.io/badge/license-Apache--2.0-4B5563?style=flat-square)
[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Aashir01/Supply-Chain-and-Logistics-Agentic-system)

</td>
<td width="50%" valign="top">

### 🏥 Medical Insurance Appeals Bot
Reads denial letters, drafts legally grounded appeals, and routes every one to a licensed human before it leaves the building. The AI never sends anything on its own.

**Why it's hard:** the liability rule is enforced in **three independent layers** — role gate, authorization gate, delivery gate — with a test suite that fails the build if any of them regresses.

`LangGraph state machine` · `HIPAA / PHI-at-rest encryption` · `X12 835 EDI intake`
`Zero-downtime key rotation` · `Weighted extraction evals as a CI gate`

**Stack:** FastAPI · LangGraph · Claude · Postgres · Alembic · Fly.io / Render

![tests](https://img.shields.io/badge/tests-119-38BDAE?style=flat-square)
![HIPAA](https://img.shields.io/badge/HIPAA-documented-6E56CF?style=flat-square)
[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Aashir01/Medical-Insurance-Appeal-Bots)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📖 Quran Research Agent
Deterministic retrieval and agentic research over a closed corpus — 6,236 ayat, 130k morphological segments, 1,651 roots. Ask for every occurrence of a root and you get **all 854**, computed in SQL, not the twenty most similar.

**Why it's hard:** scripture is rendered from Postgres via placeholders, never generated. Unresolvable references fail visibly instead of producing plausible text.

`Exhaustive > probabilistic retrieval` · `Multiple-comparison correction by default`
`Violations serialised before support` · `MCP server (14 tools)`

**Stack:** FastAPI · PostgreSQL · Next.js PWA · LangGraph · MCP

![tests](https://img.shields.io/badge/tests-89-38BDAE?style=flat-square)
![eval](https://img.shields.io/badge/golden%20eval-53%20items-38BDAE?style=flat-square)
[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Aashir01/Quran-Research-Agent)

</td>
<td width="50%" valign="top">

### 📈 MFIE — Macro-Informed Financial Intelligence Engine
Treats a chart pattern as a *hypothesis* and the macroeconomy as the *evidence*. A setup becomes a signal only after surviving a chain of econometric filters.

**Why it's hard:** the Market Cycle Compass corrects for **overlapping observations** — a factor scoring t = −7.3 uncorrected measured t ≈ −0.9 once corrected. On synthetic data it correctly reports *no measurable edge*.

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

These aren't slogans — each one is load-bearing in the repos above.

| Principle | Where it shows up |
|---|---|
| **Compute what code can compute.** | Distances, draft limits, legal driving hours and days-of-cover are arithmetic. The model is asked only what code cannot settle — and infeasible options are filtered out *before* it ever sees them. |
| **Treat all external text as hostile.** | Vessel names, headlines and recalled memories reach prompts and none are written by the operator. Structural fencing → detective scoring → quarantine, backed by tests for what must *not* be flagged. |
| **Guardrails may only tighten.** | Tier rules can raise an action's tier, never lower it, so a new rule can never widen autonomy by accident. Spend ceilings and treasury caps are pure code. |
| **Degrade, never stop.** | Every system boots with no API key and no vendor: deterministic policies, synthetic providers, offline engines. You can evaluate the whole product before signing anything. |
| **Report the number chance predicts.** | Testing 1,651 roots at p<0.05 yields ~83 "findings" from noise. The correction is applied before results return — not offered as an option. |
| **Name the gaps.** | Every README has a *Known limitations* section. A tool that hides them is worse than no tool. |

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
| [Enterprise AI Knowledge Assistant](https://github.com/Aashir01/Enterprise-AI-Knowledge-Assistant) | Production RAG assistant for enterprise document search — hybrid retrieval, source-grounded answers, containerised | FastAPI, LangChain, FAISS/Qdrant |
| [AI Data Analyst Agent](https://github.com/Aashir01/AI-Data-Analyst-Agent) | Conversational agent that explores datasets, writes and runs analysis code, explains results | Python, tool-calling, pandas |
| [agent-cli](https://github.com/Aashir01/agent-cli) | A coding-agent CLI built from scratch | TypeScript |
| [Nexus Motion](https://github.com/Aashir01/nexus-motion-AI-video-agency) | Multi-agent pipeline automating end-to-end video production | Python, multi-agent |
| [Visa Check](https://github.com/Aashir01/Visa-Check) · [Spain Appointment Bot](https://github.com/Aashir01/spain-visa-appointment-bot) | Appointment tracking and notification automation | Python |
| [March ML Mania 2026](https://github.com/Aashir01/-March-Machine-Learning-Mania-2026) | Kaggle tournament model — Elo, Pythagorean efficiency, Massey Ordinals, calibrated ensembles | Python, scikit-learn |
| [My Portfolio](https://github.com/Aashir01/My_Portfolio) | Personal site — [aashirnoman.online](https://aashirnoman.online) | TypeScript, React |
| [Deep Learning Projects](https://github.com/Aashir01/Deep-Learning-Projects) | Applied DL notebooks and experiments | Jupyter, PyTorch |

</details>

---

## 📈 GitHub Analytics

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=Aashir01&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDAE&icon_color=38BDAE&include_all_commits=true&count_private=true" alt="GitHub Stats" />
  <img width="41%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aashir01&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDAE&langs_count=8" alt="Top Languages" />
</p>

<p align="center">
  <img width="90%" src="https://github-readme-activity-graph.vercel.app/graph?username=Aashir01&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=38BDAE&line=38BDAE&point=FFFFFF&area=true" alt="Contribution Graph" />
</p>

---

## 🤝 Let's work together

I'm open to **remote AI/ML engineering roles** and **long-term consulting engagements** — especially where an LLM system has to be trusted with something consequential: agent orchestration, retrieval over proprietary corpora, guardrails and approval workflows, or evaluation infrastructure for a team that's shipping fast and flying blind.

**Good fit if you need:** an agent pipeline that degrades safely · retrieval that cites and refuses · evals that gate CI · a second opinion on where your LLM system will break.

<p align="center">
  <a href="https://linkedin.com/in/aashir-noman-138820152"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://aashirnoman.online"><img src="https://img.shields.io/badge/View%20Portfolio-38BDAE?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:azac965@gmail.com"><img src="https://img.shields.io/badge/Send%20an%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Aashir01&label=Profile%20views&color=38BDAE&style=flat-square" alt="Profile views" />
  <a href="https://github.com/Aashir01?tab=followers"><img src="https://img.shields.io/github/followers/Aashir01?label=Followers&style=flat-square&color=38BDAE" alt="Followers"/></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=120&section=footer" width="100%" />
</p>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0F172A,50:1E3A8A,100:0EA5E9&text=MANJUNATH%20BHASKAR&fontColor=ffffff&fontSize=42&fontAlignY=38&desc=AI%20Agent%20Security%20%7C%20Applied%20AI%20Engineer%20%7C%20Data%20%26%20Cloud&descAlignY=58"/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=23&duration=3500&pause=1000&color=0EA5E9&center=true&vCenter=true&width=900&lines=Breaking+and+hardening+AI+agent+infrastructure;Model+Context+Protocol+security+research;Multi-agent+systems+that+run+on+your+own+laptop;Cryptographic+guarantees+over+good+intentions)](https://git.io/typing-svg)

<p>
<img src="https://img.shields.io/badge/M.Sc._Cybersecurity-BTU_Cottbus--Senftenberg-0EA5E9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/M.Sc._Applied_Data_Science-SRH_Heidelberg-1E3A8A?style=for-the-badge"/>
</p>

<p>
<a href="https://maps.google.com/?q=Mannheim,Germany">
<img src="https://img.shields.io/badge/Mannheim-Germany-181717?style=for-the-badge&logo=googlemaps"/>
</a>
<a href="https://linkedin.com/in/manjunath230">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin"/>
</a>
<a href="mailto:manjunathbhaskargv@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail"/>
</a>
<a href="https://pypi.org/project/mcp-scan/">
<img src="https://img.shields.io/badge/PyPI-mcp--scan-3775A9?style=for-the-badge&logo=pypi&logoColor=white"/>
</a>
<a href="https://www.researchgate.net/profile/Manjunath-Bhaskar-2">
<img src="https://img.shields.io/badge/ResearchGate-Publications-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white"/>
</a>
</p>

<p>
<img src="https://komarev.com/ghpvc/?username=manjunathbhaskar&style=for-the-badge&color=0EA5E9"/>
<img src="https://img.shields.io/github/followers/manjunathbhaskar?style=for-the-badge&logo=github"/>
<img src="https://img.shields.io/github/stars/manjunathbhaskar?affiliations=OWNER&style=for-the-badge"/>
</p>

</div>

---

# About

I work on the security of AI agent infrastructure: the tooling, protocols and pipelines that let language models act on the world.

Currently **Founding Engineer** at a stealth AI startup and **Applied AI Researcher** at [Shankyaa](https://shankyaa.com), working on cryptographic agent security, prompt-injection defence, and high-throughput ML pipelines. Deepening the security side through an **M.Sc. in Cybersecurity** at BTU Cottbus-Senftenberg.

Before that I spent three years building production data infrastructure, including a year at the **Global Legal Entity Identifier Foundation** in Frankfurt, where the pipelines I built published reference data consumed by regulated financial institutions. That is where I learned to care about what a system *guarantees* rather than what it usually does.

Most of my open-source work now goes into the **Model Context Protocol** ecosystem, finding and fixing attack surfaces in the plumbing LLMs use to talk to the world.

### Currently open to

- AI / ML Engineering
- AI Agent Security and Red-Teaming
- Platform, Data and DevOps Engineering
- Research collaboration in AI safety and evaluation

---

# Recognition

| Award | Event | Work |
|---|---|---|
| **2nd place of 6,000+ entrants** | [RAISE Summit 2026](https://raise-paris.com), Paris (Crusoe track) | Factory Digital Twin with physics-informed neural networks and zero-trust sensor telemetry |
| **Finalist** | HackXplore Karlsruhe, ZEISS track | Cryptographic EEG / motor BCI, Pedersen commitments and Schnorr ZK proofs, 94% motor-intent accuracy at 250 Hz |
| **Finalist** | HackXplore Karlsruhe, LBBW track | Legatum, a 9-layer agent swarm turning philanthropic intent into on-chain verifiable impact |

---

# AI Agent Security

Independent security research on the Model Context Protocol ecosystem and on LLM red-teaming frameworks.

### Merged

| PR | What it fixes |
|---|---|
| [ComposioHQ/composio#3921](https://github.com/ComposioHQ/composio/pull/3921) | **JSON Schema validation gap.** An unsatisfiable `allOf` member now correctly rejects every value instead of silently widening, closing a hole in tool-call parameter validation |
| [deepset-ai/haystack#12217](https://github.com/deepset-ai/haystack/pull/12217) | **`DocumentJoiner` `top_k=0`.** Treated as unset instead of silently returning an empty result set |

### Open

| PR | What it fixes |
|---|---|
| [NVIDIA/garak#1981](https://github.com/NVIDIA/garak/pull/1981) | **Homoglyph probes.** Tests LLM resistance to visual confusable attacks on tool names |
| [modelcontextprotocol/python-sdk#3141](https://github.com/modelcontextprotocol/python-sdk/pull/3141) | **Unicode homoglyph spoofing.** Rejects tool names containing Cyrillic/Greek lookalikes and bidi characters |
| [modelcontextprotocol/python-sdk#3175](https://github.com/modelcontextprotocol/python-sdk/pull/3175) | **OAuth auth-method confusion.** Stops sending `client_id` in the token body under `client_secret_basic` |
| [modelcontextprotocol/inspector#1732](https://github.com/modelcontextprotocol/inspector/pull/1732) | **DNS-rebinding TOCTOU.** Pins resolved IPs so the proxy fetch cannot be flipped to instance metadata |
| [googleapis/mcp-toolbox#3674](https://github.com/googleapis/mcp-toolbox/pull/3674) | **Slowloris.** Adds `ReadHeaderTimeout` to prevent connection exhaustion on the Go MCP server |
| [mark3labs/mcp-go#939](https://github.com/mark3labs/mcp-go/pull/939) | **Panic recovery.** Recovers panics in `executeRegularToolAsTask` under hybrid task mode |

### Closed, kept as reference implementations

| PR | Context |
|---|---|
| [microsoft/PyRIT#2242](https://github.com/microsoft/PyRIT/pull/2242) | `MaliciousToolCallInjection`, an indirect prompt-injection strategy for agentic red-teaming. Closed pending a broader unified agent-testing design the maintainers are shaping |
| [ModelContextProtocol-Security/mcpserver-audit#4](https://github.com/ModelContextProtocol-Security/mcpserver-audit/pull/4) | Prompt-injection and tool-scope security checks for MCP server auditing |
| [567-labs/instructor#2476](https://github.com/567-labs/instructor/pull/2476) | Builds partial model instances for incomplete `list[BaseModel]` items during streaming |

### 🛠 mcp-scan

```bash
pip install mcp-scan
mcp-scan web_search wеb_search    # the second one is Cyrillic е (U+0435)
```

A malicious MCP server can register a tool whose name renders **identically** to a legitimate one in every font, bypassing ASCII allow-lists while routing calls to its own handler. `mcp-scan` catches bidi control characters, NFKC-detectable homoglyphs, surviving confusables, invisible characters and oversized names.

→ [github.com/manjunathbhaskar/mcp-scan](https://github.com/manjunathbhaskar/mcp-scan)

---

# Featured Projects

<details>
<summary><b>BlackSwanX</b> — Adversarial multi-agent prediction engine, zero API cost</summary>

<br/>

| | |
|---|---|
| **Stack** | Python, Ollama, SQLite, Graph RAG |
| **Scale** | 179 expert agents + 200 citizen agents per run |
| **Design** | Elite / citizen / jury tiers, multi-agent debate with corrective feedback loops |
| **Novelty** | Cognitive Dissonance scoring: finds the widest gap between crowd belief and expert fear |
| **Safety** | Kill-switch, adversarial "BlackSwan Assassin", stateful self-auditing across runs |
| **Privacy** | Runs 100% locally, no API keys, no data leaves the machine |
| **Repo** | [BlackSwanXMain](https://github.com/manjunathbhaskar/BlackSwanXMain) |

Most prediction tools tell you what the crowd thinks. BlackSwanX looks for where the crowd is wrong, then stress-tests that thesis with an injector that asks what happens if the assumption collapses.

</details>

<details>
<summary><b>Factory Digital Twin</b> — RAISE Summit 2026, 2nd of 6,000+ entrants</summary>

<br/>

| | |
|---|---|
| **Stack** | PyTorch, FastAPI, HMAC-SHA256, VLM verification |
| **Physical layer** | MH-PINN: shared LSTM core with per-phenomenon heads (vibration, thermal, RUL, cure pressure, fatigue) |
| **Information layer** | PRAETOR: HMAC verification → three-stage triage → cited advisory → Advocate/Skeptic debate → Jury → tooled operator |
| **Interface** | Frozen cross-layer contract, `SignedReading{payload, signature}`, tested end to end |
| **Data honesty** | Every dataset labelled real / simulated / synthetic, down to the message signature. No confidential data used |
| **Repo** | [Crusoe](https://github.com/manjunathbhaskar/Crusoe) |

An agent that advises a factory operator, where every reading is authenticated, every recommendation is cited, and autonomous action is gated behind verified human intervention.

</details>

<details>
<summary><b>BrainID</b> — Neural identity, motor BCI and cryptographic memory tagging</summary>

<br/>

| | |
|---|---|
| **Stack** | CEEMDAN denoising, CatBoost, Pedersen commitments, Schnorr ZKP |
| **Hardware** | Unicorn Hybrid Black, 8 channels, 250 Hz |
| **Motor BCI** | Predicts a keypress before the finger moves: 94% accuracy, 100% precision |
| **Identity vault** | Authenticates from a brainwave fingerprint with **0 bytes** of brain data stored on any server |
| **Repo** | [braind-eeg](https://github.com/manjunathbhaskar/braind-eeg) |

Your face can be photographed and your voice cloned. Brainwaves originate inside the skull and cannot be replayed from a static recording. Even if the auth database is stolen, it contains only a commitment indistinguishable from a random number.

</details>

<details>
<summary><b>Legatum</b> — Intelligence-first philanthropic banking</summary>

<br/>

| | |
|---|---|
| **Stack** | TypeScript, agent orchestration, on-chain verification |
| **Design** | 9-layer AI agent swarm |
| **Goal** | Turning philanthropic intent into on-chain verifiable impact |
| **Repo** | [Legatum](https://github.com/manjunathbhaskar/Legatum) |

</details>

<details>
<summary><b>Viscosity</b> — The VC brain: sourcing, screening, diligence, decision</summary>

<br/>

| | |
|---|---|
| **Stack** | TypeScript, LLM agents, persistent memory layer |
| **Design** | Cold-start founder scoring, unaveraged three-axis scoring, per-claim Trust Score |
| **Why it matters** | Averaging scores destroys the signal. Viscosity keeps the axes separate and traces every claim |
| **Repo** | [Viscosity](https://github.com/manjunathbhaskar/Viscosity) |

</details>

<details>
<summary><b>Solar Energy Forecasting</b> — M.Sc. thesis, grade 1.8</summary>

<br/>

| | |
|---|---|
| **Stack** | CEEMDAN, temporal convolutional networks, CatBoost |
| **Result** | 25% improvement in forecast accuracy over baselines |
| **Repo** | [Developing-an-Advanced-Forecasting-Model-for-Solar-Energy-Predictions](https://github.com/manjunathbhaskar/Developing-an-Advanced-Forecasting-Model-for-Solar-Energy-Predictions) |

Hybrid architecture: decompose the signal, model the temporal structure, boost the residuals.

</details>

---

# Tech Stack

**Languages and ML**

<p>
<img src="https://skillicons.dev/icons?i=python,ts,js,go,sqlite"/>
<img src="https://skillicons.dev/icons?i=pytorch,sklearn,fastapi"/>
</p>

**Data and Infrastructure**

<p>
<img src="https://skillicons.dev/icons?i=postgres,mysql,docker,kubernetes,terraform,githubactions,aws,gcp,linux"/>
</p>

**Security and agents**

`MCP` · `Prompt-injection defence` · `Ed25519` · `HMAC` · `Pedersen commitments` · `Schnorr ZKP` · `Zero-trust architecture` · `garak` · `PyRIT` · `Ollama` · `Graph RAG` · `LangFuse`

---

# Experience

**Founding Engineer** · Stealth AI Startup, Fulda
`Agentic memory` `Cryptographic agent control` `Evaluation frameworks` `Async Python`

**Applied AI Researcher** · Shankyaa, Germany
`Media integrity` `Privacy-preserving biometrics` `High-throughput pipelines`

**Data Engineer, Cloud Security & Automation** · GLEIF, Frankfurt am Main
`Python ELT` `Data quality gates in CI/CD` `Regulated financial data`

**Data Engineer, DevSecOps & Cloud** · Torry Harris Business Solutions, India
`Terraform` `IAM/SSO as code` `dbt + BigQuery at 10 TB+/month`

---

# Certifications

![](https://img.shields.io/badge/Microsoft-Fabric_Data_Engineer_(DP--700)-0078D4?style=for-the-badge&logo=microsoft)
![](https://img.shields.io/badge/Microsoft-Azure_Security_Engineer_(AZ--500)-0078D4?style=for-the-badge&logo=microsoftazure)
![](https://img.shields.io/badge/AWS-DevOps_Specialization-FF9900?style=for-the-badge&logo=amazonaws)
![](https://img.shields.io/badge/Databricks-Fundamentals-FF3621?style=for-the-badge&logo=databricks)

---

# GitHub Analytics

<p align="center">
<img height="180em" src="https://github-readme-stats-manjunathbhaska.vercel.app/api?username=manjunathbhaskar&show_icons=true&count_private=true&theme=tokyonight&hide_border=true"/>
<img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=manjunathbhaskar&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
<img src="https://github-readme-stats-manjunathbhaska.vercel.app/api/top-langs/?username=manjunathbhaskar&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
<img width="100%" src="https://github-profile-trophy-manjunathbhas.vercel.app/?username=manjunathbhaskar&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&margin-w=15" alt="GitHub Trophies"/>
</p>

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=manjunathbhaskar&theme=tokyo-night&hide_border=true"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/manjunathbhaskar/manjunathbhaskar/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/manjunathbhaskar/manjunathbhaskar/output/github-snake.svg"/>
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/manjunathbhaskar/manjunathbhaskar/output/github-snake.svg"/>
  </picture>
</p>

---

# Current Focus

```yaml
Researching:
  - AI agent security and the MCP attack surface
  - Adversarial evaluation of agentic systems
  - Alignment drift in agents with persistent memory

Building:
  - mcp-scan and upstream hardening for MCP
  - Local-first multi-agent systems (zero API cost)
  - Evaluation and gating frameworks

Reading:
  - Interpretability and faithful explanation
  - Continual and lifelong learning

Open_To:
  - AI / ML engineering
  - Agent security and red-teaming
  - Research collaboration
```

---

<div align="center">

<a href="mailto:manjunathbhaskargv@gmail.com">Email</a> •
<a href="https://linkedin.com/in/manjunath230">LinkedIn</a> •
<a href="https://github.com/manjunathbhaskar">GitHub</a> •
<a href="https://shankyaa.com">Shankyaa</a> •
<a href="https://www.researchgate.net/profile/Manjunath-Bhaskar-2">ResearchGate</a>

> *"Prefer guarantees to good behaviour."*

<img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=120&color=0:0EA5E9,50:1E3A8A,100:0F172A"/>

</div>

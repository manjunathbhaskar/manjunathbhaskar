![Header](static/github-header-image-old.png)

<h3>Data & Applied AI Engineer · Cloud Security Specialist · Based in Germany</h3>

<p>
Currently a <b>Founding Engineer</b> at a stealth AI startup and <b>Applied AI Researcher</b> at <a href="https://shankyaa.com">Shankyaa</a>, where I work on cryptographic agent security, prompt injection defences, and high-throughput ML pipelines. Deepening the security layer through an <b>M.Sc. in Cybersecurity</b> at BTU Cottbus-Senftenberg.
</p>

<p>
🏆 <b>2nd place out of 6,000+ teams</b> — <a href="https://raise-paris.com">RAISE Summit 2026</a>, Paris &nbsp;|&nbsp; Factory Digital Twin with Physics-Informed Neural Networks & zero-trust sensor telemetry<br/>
🥈 <b>Finalist</b> — HackXplore Karlsruhe (ZEISS Track) &nbsp;|&nbsp; Cryptographic EEG/Motor BCI with Pedersen ZK-Proofs & 94% motor-intent accuracy at 250 Hz
</p>

<p>
Open-source focus: <b>AI agent security</b> and the <b>Model Context Protocol (MCP)</b> ecosystem — finding and fixing attack surfaces in the infrastructure LLMs use to talk to the world.
</p>

---

### 🔐 Active Security Contributions

| PR | What it fixes |
|---|---|
| [googleapis/mcp-toolbox#3674](https://github.com/googleapis/mcp-toolbox/pull/3674) | **Slowloris** — adds `ReadHeaderTimeout` to prevent connection exhaustion on the Go MCP server |
| [modelcontextprotocol/inspector#1732](https://github.com/modelcontextprotocol/inspector/pull/1732) | **DNS-rebinding TOCTOU** — pins resolved IPs so the proxy fetch can't be flipped to instance metadata |
| [modelcontextprotocol/python-sdk#3141](https://github.com/modelcontextprotocol/python-sdk/pull/3141) | **Unicode homoglyph spoofing** — rejects tool names containing Cyrillic/Greek lookalikes and bidi chars |
| [microsoft/PyRIT#2242](https://github.com/microsoft/PyRIT/pull/2242) | **Prompt injection** — new `MaliciousToolCallInjection` attack strategy for agentic pipeline red-teaming |
| [NVIDIA/garak#1981](https://github.com/NVIDIA/garak/pull/1981) | **Homoglyph probes** — tests LLM resistance to visual confusable attacks on tool names |

### 🛠 mcp-scan

```bash
pip install mcp-scan
mcp-scan web_search wеb_search   # catches Cyrillic е ≠ Latin e
```

CLI scanner for MCP tool names — detects homoglyphs, bidirectional chars, and Unicode confusables → [github.com/manjunathbhaskar/mcp-scan](https://github.com/manjunathbhaskar/mcp-scan)

---

### 📈 My GitHub Stats
<div style="display: flex;" align="center">
     <img align="center" width="48%"
          style="margin: 20px; padding: 0 4px;"
          src="https://github-readme-streak-stats.herokuapp.com/?user=manjunathbhaskar&count_private=true&show_icons=true&theme=tokyonight&hide_border=true" 
          alt="Manjunathbhaskar" />
     <img align="center" width="48%"
          style="margin: 20px; padding: 0 4px;"
          src="https://github-readme-stats-sigma-five.vercel.app/api?username=manjunathbhaskar&show_icons=true&locale=en&count_private=true&show_icons=true&theme=tokyonight&hide_border=true"
          alt="manjunathbhaskar" />
</div>

<br/>
<div style="display: flex;" align="center">
     <img align="center" width="48%"
          style="margin: 20px; padding: 0 4px;"
          src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=manjunathbhaskar&show_icons=true&theme=tokyonight&hide_border=true&layout=compact" 
          alt="languages" />
</div>

<br/>
<div style="display: flex;" align="center"> 
    <img align="center"
        src="https://github-profile-trophy.vercel.app/?username=manjunathbhaskar&theme=tokyonight&no-frame=true&column=-1"
        style="margin: 20px; padding: 0 4px;"
        alt="manjunathbhaskar" />
</div>

---

### ⚡ Technologies

<p>
    <img alt="python" src="https://img.shields.io/badge/Python-black?logo=python&amp;style=plastic" /> <img alt="numpy" src="https://img.shields.io/badge/NumPy-black?logo=numpy&amp;style=plastic" /> <img alt="pandas" src="https://img.shields.io/badge/Pandas-black?logo=pandas&amp;style=plastic" /> <img alt="plotly" src="https://img.shields.io/badge/Folium-black?logo=folium&amp;style=plastic" /> <img alt="scikit-learn" src="https://img.shields.io/badge/Scikit%20Learn-black?logo=scikit-learn&amp;style=plastic" /> <img alt="tensorflow" src="https://img.shields.io/badge/Tensorflow-black?logo=tensorflow&amp;style=plastic" /> <img alt="opencv" src="https://img.shields.io/badge/OpenCV-black?logo=opencv&amp;style=plastic" /> <img alt="pytorch" src="https://img.shields.io/badge/Pytorch-black?logo=pytorch&amp;style=plastic" /> <img alt="fastapi" src="https://img.shields.io/badge/Django-black?logo=django&amp;style=plastic" /> <img alt="html5" src="https://img.shields.io/badge/HTML5-black?logo=html5&amp;style=plastic" /> <img alt="css3" src="https://img.shields.io/badge/JavaScript-black?logo=javascript&amp;style=plastic" /> <img alt="mysql" src="https://img.shields.io/badge/MySQL-black?logo=mysql&amp;style=plastic" /> <img alt="postgresql" src="https://img.shields.io/badge/PostgreSQL-black?logo=postgresql&amp;style=plastic" /> <img alt="mongodb" src="https://img.shields.io/badge/Kibana-black?logo=kibana&amp;style=plastic" /> <img alt="vscode" src="https://img.shields.io/badge/VSCode-black?logo=visual-studio-code&amp;style=plastic" /> <img alt="chrome" src="https://img.shields.io/badge/Google%20Chrome-black?logo=google-chrome&amp;style=plastic" /> <img alt="brave" src="https://img.shields.io/badge/Brave-black?logo=brave&amp;style=plastic" /> <img alt="git" src="https://img.shields.io/badge/Git-black?logo=git&amp;style=plastic" /> <img alt="docker" src="https://img.shields.io/badge/Docker-black?logo=docker&amp;style=plastic" /> <img alt="kubernetes" src="https://img.shields.io/badge/Kubernetes-black?logo=kubernetes&amp;style=plastic" /> <img alt="terraform" src="https://img.shields.io/badge/Terraform-black?logo=terraform&amp;style=plastic" /> <img alt="github-actions" src="https://img.shields.io/badge/Github%20Actions-black?logo=github-actions&amp;style=plastic" /> <img alt="google-cloud-platform" src="https://img.shields.io/badge/GCP-black?logo=google-cloud&amp;style=plastic" /> <img alt="amazon-aws" src="https://img.shields.io/badge/AWS-black?logo=amazon-aws&amp;style=plastic" /> <img alt="heroku" src="https://img.shields.io/badge/Heroku-black?logo=heroku&amp;style=plastic" /> <img alt="jupyter" src="https://img.shields.io/badge/Jupyter Notebook-black?logo=jupyter&amp;style=plastic" /> <img alt="googlecolab" src="https://img.shields.io/badge/Google Colab-black?logo=googlecolab&amp;style=plastic" />
</p>

<p align="center">
    <img alt="Visitors" src="https://visitor-badge.laobi.icu/badge?page_id=manjunathbhaskar&color=blue"/>
    <img alt="Profile Views" src="https://komarev.com/ghpvc/?username=manjunathbhaskar"/>
    <img alt="Stars" src="https://img.shields.io/github/stars/manjunathbhaskar/manjunathbhaskar?style=flat-square&labelColor=343b41"/>
</p>

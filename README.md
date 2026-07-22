![Header](static/github-header-image-old.png)

<h3>Security researcher focused on <b>AI agent security</b> and the <b>Model Context Protocol (MCP)</b> ecosystem — finding and fixing attack surfaces in the infrastructure LLMs use to talk to the world.</h3>

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
    <img alt="python" src="https://img.shields.io/badge/Python-black?logo=python&style=plastic" />
    <img alt="go" src="https://img.shields.io/badge/Go-black?logo=go&style=plastic" />
    <img alt="typescript" src="https://img.shields.io/badge/TypeScript-black?logo=typescript&style=plastic" />
    <img alt="pytorch" src="https://img.shields.io/badge/PyTorch-black?logo=pytorch&style=plastic" />
    <img alt="tensorflow" src="https://img.shields.io/badge/TensorFlow-black?logo=tensorflow&style=plastic" />
    <img alt="docker" src="https://img.shields.io/badge/Docker-black?logo=docker&style=plastic" />
    <img alt="kubernetes" src="https://img.shields.io/badge/Kubernetes-black?logo=kubernetes&style=plastic" />
    <img alt="github-actions" src="https://img.shields.io/badge/Github%20Actions-black?logo=github-actions&style=plastic" />
    <img alt="google-cloud-platform" src="https://img.shields.io/badge/GCP-black?logo=google-cloud&style=plastic" />
    <img alt="amazon-aws" src="https://img.shields.io/badge/AWS-black?logo=amazon-aws&style=plastic" />
    <img alt="postgresql" src="https://img.shields.io/badge/PostgreSQL-black?logo=postgresql&style=plastic" />
    <img alt="git" src="https://img.shields.io/badge/Git-black?logo=git&style=plastic" />
</p>

<p align="center">
    <img alt="Visitors" src="https://visitor-badge.laobi.icu/badge?page_id=manjunathbhaskar&color=blue"/>
    <img alt="Profile Views" src="https://komarev.com/ghpvc/?username=manjunathbhaskar"/>
    <img alt="Stars" src="https://img.shields.io/github/stars/manjunathbhaskar/manjunathbhaskar?style=flat-square&labelColor=343b41"/>
</p>

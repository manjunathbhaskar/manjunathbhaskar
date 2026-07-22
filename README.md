## manjunath bhaskar

Security researcher focused on **AI agent security** and the **Model Context Protocol (MCP)** ecosystem. I find and fix attack surfaces in the infrastructure that LLMs use to talk to the world.

---

### Active contributions

| PR | What it fixes |
|---|---|
| [googleapis/mcp-toolbox#3674](https://github.com/googleapis/mcp-toolbox/pull/3674) | Slowloris — adds `ReadHeaderTimeout` to prevent connection exhaustion on the Go MCP server |
| [modelcontextprotocol/inspector#1732](https://github.com/modelcontextprotocol/inspector/pull/1732) | DNS-rebinding TOCTOU — pins resolved IPs so the proxy fetch can't be flipped to instance metadata between check and connect |
| [modelcontextprotocol/python-sdk#3141](https://github.com/modelcontextprotocol/python-sdk/pull/3141) | Unicode homoglyph spoofing — rejects tool names containing Cyrillic/Greek lookalikes and bidirectional formatting chars |
| [microsoft/PyRIT#2242](https://github.com/microsoft/PyRIT/pull/2242) | New `MaliciousToolCallInjection` attack strategy — red-teams agentic pipelines against indirect prompt injection via spoofed tool responses |
| [NVIDIA/garak#1981](https://github.com/NVIDIA/garak/pull/1981) | New homoglyph detection probes — tests LLM resistance to visual confusable attacks on tool names |

---

### mcp-scan

A CLI that scans MCP tool names for Unicode-based spoofing attacks.

```bash
pip install mcp-scan
mcp-scan web_search wеb_search  # Cyrillic е ≠ Latin e
```

→ [github.com/manjunathbhaskar/mcp-scan](https://github.com/manjunathbhaskar/mcp-scan)

---

### Focus area

The attack surface at the boundary between LLMs and external tools — where tool names, OAuth tokens, HTTP timeouts, and DNS resolution decisions create exploitable windows. Most of this is invisible in normal use and only matters when an adversary controls part of the environment.

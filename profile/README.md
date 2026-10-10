<div align="center">

<img src="https://deepbluedynamics.com/og-preview.png" width="700" alt="Deep Blue Dynamics" />

<br/>
<br/>

**Agentic infrastructure. Container-native. Production-ready.**

[![Site](https://img.shields.io/badge/Site-0055CC?style=flat-square&logo=googlechrome&logoColor=white)](https://deepbluedynamics.com)
[![Docs](https://img.shields.io/badge/Docs-0055CC?style=flat-square&logo=gitbook&logoColor=white)](https://deepbluedynamics.com/docs)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/DeepBlueDynamics)

</div>

---

DeepBlue Dynamics builds open source agentic tooling for the marine electronics market. DeepBlue's promise: agents and people can ask questions of a boat's instruments, logs and documents, on board and without a connection.

```
interfaces   →   orchestration   →   services
  hyperia          nemesis8         nuts.services
```

## Projects

| Project | | Description |
|---------|---|-------------|
| **[meridian](https://github.com/DeepBlueDynamics/meridian)** | vessel navigation | Next-generation navigation for vessels. |
| **[lume](https://github.com/DeepBlueDynamics/lume)** | search + telemetry | Documents and time-series telemetry in one store: BM25, embeddings, a knowledge graph and Signal K SQL in one Rust binary that runs on the boat's Raspberry Pi. |
| **[nemesis8](https://github.com/DeepBlueDynamics/nemesis8)** | agent runtime | Run AI agents anywhere in one binary — multi-provider, 69+ MCP tools, Docker-native execution, Pokeball environments. |
| **[hyperia](https://github.com/DeepBlueDynamics/hyperia)** | terminal interface | Terminal emulator built for agents — MCP sidecar, Stream Deck support, deep nemesis8 integration. |
| **[grubcrawler](https://github.com/DeepBlueDynamics/grubcrawler)** | web crawler | Agentic web crawler in one container: clean markdown from any URL, PDFs with OCR, Ghost Protocol vision fallback, MCP server for your coding agent. |
| **[ferricula](https://github.com/DeepBlueDynamics/ferricula-alpha)** | agent memory | Memory engine and cognition stack for language-model agents: experience that decays, evidence kept verbatim, hybrid recall, dream cycles. |

### Get started with nemesis8

```bash
# macOS / Linux
curl -sSL https://nemesis8.nuts.services/install.sh | bash

# Windows
irm https://nemesis8.nuts.services/install.ps1 | iex
```

```bash
nemesis8 --provider claude interactive
nemesis8 pokeball run hyperagents --prompt "analyze the meta-agent loop"
```

> **nemesis8 is the kernel. Everything else plugs into it.**

## nuts.services

Hosted production endpoints — single sign-on through NUTS auth.

| Service | Endpoint | Description |
|---------|----------|-------------|
| **auth** | [auth.nuts.services](https://auth.nuts.services) | Platform identity — JWT + `ahp_` API tokens that every service verifies |
| **shivvr** | [shivvr.nuts.services](https://shivvr.nuts.services) | Ephemeral embedding + hybrid search: GTR-T5, EmbeddingGemma 2, SigLIP image embeddings |
| **ferricula** | [ferricula.nuts.services](https://ferricula.nuts.services) | Thermodynamic memory — personality archetypes, decay, dream cycles |
| **grub** | [grub.nuts.services](https://grub.nuts.services) | Hosted grubcrawler: markdown from any URL, PDFs, MCP at `/mcp/` |
| **tunnel** | [tunnel.nuts.services](https://tunnel.nuts.services) | Expose localhost to the internet |
| **sdrrand** | [sdrrand.nuts.services](https://sdrrand.nuts.services) | True-random entropy relay — hardware randomness from radio (RTL-SDR) |

---

```
The container is the contract.
Agents must be portable.
Memory must be external.
Interfaces should disappear.
Systems must compose.
```

---

<div align="center">

[deepbluedynamics.com](https://deepbluedynamics.com) &nbsp;·&nbsp; [docs](https://deepbluedynamics.com/docs)

</div>

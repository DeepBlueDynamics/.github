<div align="center">

<img src="https://deepbluedynamics.com/og-preview.png" width="700" alt="Deep Blue Dynamics" />

<br/>
<br/>

**Agentic infrastructure. Container-native. Production-ready.**

[![Site](https://img.shields.io/badge/deepbluedynamics.com-0055CC?style=flat-square)](https://deepbluedynamics.com)
[![Docs](https://img.shields.io/badge/docs-0055CC?style=flat-square)](https://deepbluedynamics.com/docs)
&nbsp;
[![nemesis8](https://img.shields.io/github/stars/DeepBlueDynamics/nemesis8?style=flat-square&logo=github&label=nemesis8&color=0066FF)](https://github.com/DeepBlueDynamics/nemesis8)
[![hyperia](https://img.shields.io/github/stars/DeepBlueDynamics/hyperia?style=flat-square&logo=github&label=hyperia&color=00AAFF)](https://github.com/DeepBlueDynamics/hyperia)
[![grubcrawler](https://img.shields.io/github/stars/DeepBlueDynamics/grubcrawler?style=flat-square&logo=github&label=grubcrawler&color=00CC88)](https://github.com/DeepBlueDynamics/grubcrawler)
[![ferricula](https://img.shields.io/github/stars/DeepBlueDynamics/ferricula-arena?style=flat-square&logo=github&label=ferricula&color=FF6633)](https://github.com/DeepBlueDynamics/ferricula-arena)

</div>

---

We build AI infrastructure that runs where it matters — inside containers, across networks, through terminals, into real systems.

```
interfaces  →  orchestration  →  services
 hyperia    →    nemesis8     →  grubcrawler · ferricula
```

---

### [nemesis8](https://github.com/DeepBlueDynamics/nemesis8) &nbsp;·&nbsp; agent runtime

Run AI agents anywhere. One binary.

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

Multi-provider (Claude · Gemini · Codex · OpenClaw) &nbsp;·&nbsp; 69+ MCP tools &nbsp;·&nbsp; Docker-native execution &nbsp;·&nbsp; HTTP gateway &nbsp;·&nbsp; Pokeball environments

[![latest release](https://img.shields.io/github/v/release/DeepBlueDynamics/nemesis8?style=flat-square&color=0066FF&label=latest)](https://github.com/DeepBlueDynamics/nemesis8/releases)

> **nemesis8 is the kernel. Everything else plugs into it.**

---

### [hyperia](https://github.com/DeepBlueDynamics/hyperia) &nbsp;·&nbsp; terminal interface

Terminal emulator built for agents. MCP sidecar. Stream Deck support. Deep integration with nemesis8.

[![latest release](https://img.shields.io/github/v/release/DeepBlueDynamics/hyperia?style=flat-square&color=00AAFF&label=latest)](https://github.com/DeepBlueDynamics/hyperia/releases)

### [grubcrawler](https://github.com/DeepBlueDynamics/grubcrawler) &nbsp;·&nbsp; web crawler

High-speed distributed crawler built for autonomous agents. Feeds data into the stack.

### [ferricula](https://github.com/DeepBlueDynamics/ferricula-arena) &nbsp;·&nbsp; memory engine

Personality archetypes, memory decay, dream cycles. External memory for agents that need identity.

```bash
docker run -p 8000:8000 ghcr.io/deepbluedynamics/ferricula-arena:latest
```

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

[deepbluedynamics.com](https://deepbluedynamics.com) &nbsp;·&nbsp; [docs](https://deepbluedynamics.com/docs) &nbsp;·&nbsp; [nemesis8 pokeball registry](https://github.com/DeepBlueDynamics/nemesis8-pokeballs)

</div>

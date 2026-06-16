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

We build AI infrastructure that runs where it matters — inside containers, across networks, through terminals, into real systems.

```
interfaces   →   orchestration   →   services
  hyperia          nemesis8         nuts.services
```

## Projects

| Project | | Description |
|---------|---|-------------|
| **[meridian](https://github.com/DeepBlueDynamics/meridian)** | vessel navigation | Next-generation navigation for vessels. |
| **[nemesis8](https://github.com/DeepBlueDynamics/nemesis8)** | agent runtime | Run AI agents anywhere in one binary — multi-provider, 69+ MCP tools, Docker-native execution, Pokeball environments. |
| **[hyperia](https://github.com/DeepBlueDynamics/hyperia)** | terminal interface | Terminal emulator built for agents — MCP sidecar, Stream Deck support, deep nemesis8 integration. |

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
| **shivvr** | [shivvr.nuts.services](https://shivvr.nuts.services) | Ephemeral semantic embedding + hybrid search (GTR-T5-base, 768d) |
| **ferricula** | [ferricula.nuts.services](https://ferricula.nuts.services) | Thermodynamic memory — personality archetypes, decay, dream cycles |
| **grub** | [grub.nuts.services](https://grub.nuts.services) | Agentic web crawler — high-speed distributed crawling for autonomous agents |
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

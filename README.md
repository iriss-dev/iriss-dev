<div align="center">
  <img src="./assets/banner.png" alt="Profile Banner" width="100%" />

  # Iris (iriss-dev) 👋
  
  **Backend & Security Systems Developer** · **Developer Ergonomics** · **High-Throughput Tooling**

  <p align="center">
    <a href="https://github.com/iriss-dev/ip-sentinel"><img src="https://img.shields.io/badge/ip--sentinel-830k%20ops%2Fs-blue?style=for-the-badge&logo=target" alt="ip-sentinel" /></a>
    <a href="https://github.com/iriss-dev/envshield"><img src="https://img.shields.io/badge/envshield-pre--commit-red?style=for-the-badge&logo=shield" alt="envshield" /></a>
    <a href="https://github.com/iriss-dev/draincord"><img src="https://img.shields.io/badge/draincord-zero--dep-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="draincord" /></a>
  </p>
  <p align="center">
    <a href="https://twitter.com/irissmth1"><img src="https://img.shields.io/badge/Twitter-@irissmth1-1DA1F2?style=flat-square&logo=x&logoColor=white" alt="Twitter" /></a>
    <a href="mailto:iriss.smith08@proton.me"><img src="https://img.shields.io/badge/ProtonMail-iriss.smith08-6D4AFF?style=flat-square&logo=protonmail&logoColor=white" alt="ProtonMail" /></a>
  </p>
</div>

---

### About Me

Hi! I'm Iris, an independent developer focusing on backend infrastructure, zero-dependency utility libraries, and high-concurrency security systems.

- 🌐 Creator of **[ip-sentinel](https://github.com/iriss-dev/ip-sentinel)** — 100% offline Datacenter, Tor, and VPN detection engine running at **830,000+ lookups/sec** (<0.005 ms).
- 🛡️ Creator of **[envshield](https://github.com/iriss-dev/envshield)** — 1-second pre-commit secret leak prevention & `.env` guardian for Git.
- ⚡ Creator of **[draincord](https://github.com/iriss-dev/draincord)** — Zero-dependency Discord webhook log drain with rate-limit backoff and SQLite spooling.
- 🤖 Lead developer of **Axis** — Autonomous Discord security bot with anti-nuke triggers, raid mitigation, device/IP ban-evasion heuristics, and a zero-trust web panel.
- ⚙️ Stack & Philosophy: Zero external dependencies where possible, strict TypeScript, Radix tries, SQLite WAL persistence, and Linux servers.

---

### Open Source Highlights

<table>
  <tr>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/iriss-dev/ip-sentinel">ip-sentinel</a></h3>
      <p>Zero-dependency, offline IP intelligence. Instant Datacenter, Tor, and VPN detection with radix-tree CIDR matching in <b>&lt;0.005 ms</b>.</p>
      <p>
        <img src="https://img.shields.io/github/actions/workflow/status/iriss-dev/ip-sentinel/ci.yml?branch=main&label=CI&style=flat-square" alt="CI" />
        <img src="https://img.shields.io/badge/speed-830k%2Fsec-success?style=flat-square" alt="Speed" />
      </p>
      <code>npx ip-sentinel 104.16.1.1</code>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/iriss-dev/envshield">envshield</a></h3>
      <p>1-second Git pre-commit hook and CI scanner that prevents leaked <code>.env</code> files, Discord tokens, OpenAI keys, and AWS credentials in <b>&lt;15ms</b>.</p>
      <p>
        <img src="https://img.shields.io/github/actions/workflow/status/iriss-dev/envshield/ci.yml?branch=main&label=CI&style=flat-square" alt="CI" />
        <img src="https://img.shields.io/badge/setup-1%20sec-blue?style=flat-square" alt="Setup" />
      </p>
      <code>npx envshield install</code>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/iriss-dev/draincord">draincord</a></h3>
      <p>Resilient Discord webhook log drain with automatic batching, rate-limit backoff, and persistent SQLite WAL spooling across crashes.</p>
      <p>
        <img src="https://img.shields.io/github/actions/workflow/status/iriss-dev/draincord/ci.yml?branch=main&label=CI&style=flat-square" alt="CI" />
        <img src="https://img.shields.io/badge/deps-zero-brightgreen?style=flat-square" alt="Deps" />
      </p>
      <code>npm install draincord</code>
    </td>
  </tr>
</table>

---

### Core Security Engine

#### 🛡️ Axis — Autonomous Discord Security Sentinel
> Multi-layered server protection system designed to isolate rogue administrators, mitigate mass raids, and preserve tamper-evident forensic records.

- **Anti-Nuke Engine**: Threshold-based action tracking (bulk channel/role deletions, mass bans) with instant rogue admin isolation and rollback.
- **Anti-Raid & Evasion**: Real-time screening of new members with VPN/proxy heuristics, Tor exit node detection, and hardware fingerprint checks.
- **Zero-Trust Web Portal**: Cloudflare Tunnel-secured web dashboard and verification portal with MFA and Argon2-hashed sessions.
- **Dual-Node Coordination**: Leased leader-election protocol across geographically separate VPS instances to prevent duplicate actions.

---

### Skills & Technologies

<p align="left">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Discord.js-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord.js" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/Luau-00A2FF?style=for-the-badge&logo=roblox&logoColor=white" alt="Luau" />
</p>

---

### Connect

- **ProtonMail**: `iriss.smith08@proton.me`
- **Twitter / X**: [@irissmth1](https://twitter.com/irissmth1)
- **GitHub**: [@iriss-dev](https://github.com/iriss-dev)

---

<div align="center">
  <sub>Engineered with care · Systems stability first 🌸</sub>
</div>

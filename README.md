<div align="center">
  <img src="./assets/banner.png" alt="Profile Banner" width="100%" />

  # Iris (iriss-dev) 👋
  
  **Cybersecurity & Systems Developer** · **Defensive Engineering & Threat Intel** · **Python & Low-Latency Tooling**

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

Hi! I'm Iris, an independent developer specializing in **cybersecurity engineering**, threat detection, network forensics, and high-performance backend infrastructure.

- 🛡️ **Cybersecurity & Threat Defense**: Building autonomous anti-abuse engines, intrusion detection systems, and tamper-evident audit trails. Experienced in threat modeling, anti-nuke mechanisms, and network-level evasion analysis.
- 🐍 **Python & Systems Tooling**: Writing security tools, threat intelligence scrapers, log analysis pipelines, and automation utilities in **Python** alongside low-latency **TypeScript / Node.js** runtimes.
- 🌐 Creator of **[ip-sentinel](https://github.com/iriss-dev/ip-sentinel)** — 100% offline Datacenter, Tor, and VPN detection engine running at **830,000+ lookups/sec** (<0.005 ms).
- 🔒 Creator of **[envshield](https://github.com/iriss-dev/envshield)** — 1-second pre-commit secret leak prevention & `.env` guardian for Git.
- ⚡ Creator of **[draincord](https://github.com/iriss-dev/draincord)** — Zero-dependency Discord webhook log drain with rate-limit backoff and SQLite spooling.
- 🤖 Lead developer of **Axis** — Multi-layered Discord security engine with rogue-admin containment, JA4/IP fingerprinting, and a zero-trust administrative vault.

---

### Cybersecurity & Defensive Engineering

```text
┌─────────────────────────┬────────────────────────────────────────────────────────┐
│ Domain                  │ Focus & Production Implementation                      │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ Threat Intel & Python   │ Automated Python scrapers & parsers for threat feeds,  │
│                         │ BGP/ASN aggregation, Tor consensus sync & log triage.  │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ Anti-Abuse & Forensics  │ Radix-tree bitwise CIDR matching, JA4 fingerprinting,  │
│                         │ device posture checks, velocity gates & ban evasion.   │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ Applied Cryptography    │ Argon2id / SHA-256 peppered hashing, blind signatures, │
│                         │ Ed25519 payload signing & Merkle-tree hash audit logs. │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ System Hardening        │ Zero-open-port via Cloudflare Tunnels, systemd cgroup  │
│                         │ sandboxing, UFW isolation & pre-commit leak blockers.  │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ AppSec & Static Triage  │ Shannon entropy heuristics, regex token extraction &   │
│                         │ AST secret leak prevention in CI / pre-commit stages.  │
└─────────────────────────┴────────────────────────────────────────────────────────┘
```

---

### Open Source Projects

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

### Security Sentinel Engine

#### 🛡️ Axis — Autonomous Discord Security Sentinel
> Multi-layered server protection system designed to isolate rogue administrators, mitigate mass raids, and preserve tamper-evident forensic records.

- **Anti-Nuke Containment**: Real-time velocity tracking on destructive administrative actions (mass channel/role deletion, bulk bans) with immediate isolation and state rollback.
- **Anti-Raid & Evasion**: Screening of joining members against datacenters, Tor relays, proxy ranges, and hardware/device fingerprints.
- **Zero-Trust Administrative Vault**: Cloudflare Tunnel-secured web console with WebAuthn/FIDO2 passkeys, TOTP 2FA, and Argon2 session derivation.
- **Resilient Distributed Coordination**: Zero-dependency leader election across geographically isolated VPS nodes.

---

### Skills & Technologies

#### Languages & Core
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Luau-00A2FF?style=for-the-badge&logo=roblox&logoColor=white" alt="Luau" />
</p>

#### Cybersecurity & Infrastructure
<p align="left">
  <img src="https://img.shields.io/badge/Threat_Intel-Python_Pipelines-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Threat Intel" />
  <img src="https://img.shields.io/badge/Cybersecurity-Defensive_Ops-red?style=for-the-badge&logo=target" alt="Cybersecurity" />
  <img src="https://img.shields.io/badge/Applied_Cryptography-Ed25519_/_Argon2-black?style=for-the-badge&logo=letsencrypt" alt="Cryptography" />
  <img src="https://img.shields.io/badge/Linux_Hardening-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Cloudflare_Zero_Trust-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/SQLite_WAL-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

---

### Connect

- **ProtonMail**: `iriss.smith08@proton.me`
- **Twitter / X**: [@irissmth1](https://twitter.com/irissmth1)
- **GitHub**: [@iriss-dev](https://github.com/iriss-dev)

---

<div align="center">
  <sub>Engineered with care · Systems stability & threat defense first 🌸</sub>
</div>

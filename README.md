<div align="center">
  <img src="./assets/banner.png" alt="Profile Banner" width="100%" />

  # Iris (iriss-dev) 👋
  
  **Backend & Security Developer** · **Discord Infrastructure** · **Systems Tooling**

  <p align="center">
    <a href="https://github.com/iriss-dev/draincord"><img src="https://img.shields.io/badge/Open%20Source-draincord-5865F2?style=for-the-badge&logo=github&logoColor=white" alt="draincord" /></a>
    <a href="https://twitter.com/irissmth1"><img src="https://img.shields.io/badge/Twitter-@irissmth1-1DA1F2?style=for-the-badge&logo=x&logoColor=white" alt="Twitter" /></a>
    <a href="mailto:iriss.smith08@proton.me"><img src="https://img.shields.io/badge/ProtonMail-iriss.smith08-6D4AFF?style=for-the-badge&logo=protonmail&logoColor=white" alt="ProtonMail" /></a>
  </p>
</div>

---

### About Me

Hi! I'm Iris, an independent developer specializing in high-throughput backend infrastructure, Discord security automation, and resilient telemetry systems.

- 🔭 Creator of **[draincord](https://github.com/iriss-dev/draincord)** — Zero-dependency Discord webhook log drain with rate-limit backoff, smart batching, and SQLite spooling.
- 🛡️ Lead developer of **Axis** — Autonomous Discord security bot featuring anti-nuke triggers, raid mitigation, device/IP ban-evasion heuristics, and a zero-trust web panel.
- ⚙️ Focused on zero-dependency architectures, deterministic rate-limit negotiation, SQLite WAL persistence, and Luau runtime systems.
- 💬 Ask me about Discord bot concurrency, anti-abuse defenses, webhook resilience, or server hardening.
- 📫 Reach me directly at `iriss.smith08@proton.me` or on Twitter/X [`@irissmth1`](https://twitter.com/irissmth1).

---

### Featured Projects

#### ⚡ [draincord](https://github.com/iriss-dev/draincord) — Resilient Discord Webhook Drain
> Zero-dependency log drain for Discord webhooks with smart batching, rate-limit backoff, and persistent SQLite spooling across crashes.

- **Compliant Batching**: Automatically groups bursts into Discord-compliant payloads (max 10 embeds, 5,000 char safety margin).
- **Rate-Limit Resilience**: Reads `X-RateLimit-*` headers and handles HTTP 429 gracefully without dropping events.
- **SQLite WAL Spooling**: Powered by Node's native `node:sqlite`. Unsent items survive server reboots and process exits.
- **Pino & Syslog Adapter**: First-class stream transport (`createDraincordStream`) for existing Node backends.

```bash
npm install draincord
```

```typescript
import { Draincord } from 'draincord';

const drain = new Draincord({
  webhookUrl: process.env.DISCORD_WEBHOOK_URL!,
  storage: 'sqlite', // persistent crash recovery
  flushIntervalMs: 2000
});

drain.info('Auth', 'User session verified', { ip: '127.0.0.1' });
```

---

#### 🛡️ Axis — Autonomous Discord Security Bot
> Multi-layered server protection system designed to isolate rogue administrators, mitigate raids, and log immutable forensic records.

- **Anti-Nuke Protection**: Threshold-based action detection (mass channel/role deletion, bulk bans) with instant rogue admin isolation and state rollback.
- **Anti-Raid & Evasion Engine**: Real-time screening of new members with VPN/proxy heuristics, Tor exit node detection, and hardware fingerprint checks.
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

### Hi, I'm Kalyan (Dev)👋

I'm a Cybersecurity grad student at **Northeastern University** (MS, '27), based in Boston.
I build security tools, break things on purpose, and spend a lot of time on how real systems actually fail.

- 🔭 Currently working on post-quantum cryptography (TLS, E2EE messaging, embedded benchmarks), edge security in Rust, and Cloudflare Workers tooling
- 🔬 Research: post-quantum signatures for Cortex-M secure boot, with Prof. Rolando Herrero
- 🌱 Learning kernel internals, eBPF, firmware security, and offensive-sec certification material
- 🛠️ Interests: AppSec · PQC · vuln research · secure code review · embedded security · edge/network security
- 📫 Reach me: [LinkedIn](https://www.linkedin.com/in/gk-eh/) · [Portfolio](https://kalyangopalam.com/) · kalyan.dev.me@gmail.com

---

### 🔧 Projects I actively work on

- **[Cloudflint](https://github.com/Kalyan-Deva/cloudflint)** — edge reverse proxy, WAF and cache written from scratch in Rust (tokio, hyper, rustls): Cloudflare-style filter DSL, request coalescing, stale-while-revalidate, hot-swapped config. 485 tests.
- **pqdoctor / Flarebox** `Private Repo, Still in Development` — post-quantum readiness scanner for TLS and SSH (CLI, web, GitHub Action) inside a Tauri 2 desktop app for running and deploying Cloudflare Workers projects.
- **Quietwire** `Private Repo` — post-quantum end-to-end encrypted chat on Cloudflare Workers: PQXDH, ML-KEM ratchet, sealed sender, multi-device, key transparency, calls.
- **Peregrine** `Private Repo` — hybrid post-quantum TLS 1.3 reverse proxy in Rust (X25519MLKEM768) with handshake telemetry. Measures what PQ costs: ~3.3× the handshake bytes, ~2× the latency.
- **Merlin** `Private Repo` — nRF7002 DK (nRF5340) firmware benchmarking ML-KEM / ML-DSA against hardware-accelerated P-256 on CryptoCell-312, all through PSA on Zephyr.
- **[Numa](https://github.com/Kalyan-Deva/Numa)** — native Android adaptive-schedule and accountability app (Kotlin, Jetpack Compose, Room, Glance widgets).
- **[Lexicon](https://github.com/Kalyan-Deva/Lexicon)** `Private Repo, Still in Development` — knowledge platform with web, application, and terminal clients for structured technical notes.
- **[Bounty-Hawk](https://github.com/Kalyan-Deva/Bounty-Hawk)** — recon and bug bounty workspace for organizing targets, findings, and reports.
- **MITRE eCTF 2026 — NeuSense** — secure embedded design: key derivation, AEAD, replay protection, access control on constrained hardware.
- **Redhawk** *(in progress — public soon)* — new security project, details to follow.

---

### 🚀 Live & Shipped

Things I've deployed, published, or released to the public.

| Release | What it is | Where |
|---|---|---|
| **Lexicon (Web)** | Knowledge platform, live production build | [lexicon.kalyangopalam.com](https://lexicon.kalyangopalam.com) |
| **Lexicon TUI** | Terminal client for Lexicon, published release | [GitHub Release](https://github.com/Kalyan-Deva/Lexicon) |
| **Quietwire** | Post-quantum E2EE chat, live on Cloudflare Workers | [chat.devme.online](https://chat.devme.online) |
| **Connect** | Scan-to-connect card (Worker + D1) for Cloudflare Connect 2026 | [connect.kalyangopalam.com](https://connect.kalyangopalam.com) |
| **Cloudflint** | Rust edge proxy + WAF + cache, public repo with CI | [github.com/Kalyan-Deva/cloudflint](https://github.com/Kalyan-Deva/cloudflint) |
| **Little Hours** | Cozy always-on-top Windows desk widget (Tauri 2 + Rust), v1.0.0 installer | [GitHub Release](https://github.com/Kalyan-Deva/little-hours/releases) |
| **Numa** | Native Android app, signed APK release | [GitHub Release](https://github.com/Kalyan-Deva/Numa/releases) |
| **Bounty-Hawk** | Recon and bug bounty workspace, public repo | [github.com/Kalyan-Deva/Bounty-Hawk](https://github.com/Kalyan-Deva/Bounty-Hawk) |
| **Portfolio** | Personal site, live deployment | [kalyangopalam.com](https://kalyangopalam.com) |

More releases and public builds are on the way — check the [pinned repositories](https://github.com/Kalyan-Deva) for the latest.

---

### 🧰 Tech I use

**Languages**  
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/-Java-007396?style=flat&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**Frameworks & Platforms**  
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![Cloudflare Workers](https://img.shields.io/badge/-Cloudflare%20Workers-F38020?style=flat&logo=cloudflare&logoColor=white)
![Tauri](https://img.shields.io/badge/-Tauri-24C8D8?style=flat&logo=tauri&logoColor=white)
![Tokio](https://img.shields.io/badge/-Tokio-000000?style=flat&logo=rust&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat&logo=flask&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/-Jetpack%20Compose-4285F4?style=flat&logo=jetpackcompose&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Zephyr](https://img.shields.io/badge/-Zephyr%20RTOS-7929D2?style=flat&logo=zephyrproject&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Security**  
![Burp Suite](https://img.shields.io/badge/-Burp%20Suite-FF6633?style=flat&logo=burpsuite&logoColor=white)
![Wireshark](https://img.shields.io/badge/-Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/-Nmap-4682B4?style=flat&logo=gnubash&logoColor=white)
![Snort](https://img.shields.io/badge/-Snort-EE2E24?style=flat&logo=snort&logoColor=white)
![ML-KEM / ML-DSA](https://img.shields.io/badge/-ML--KEM%20%2F%20ML--DSA-5A3FD8?style=flat&logo=letsencrypt&logoColor=white)
![rustls](https://img.shields.io/badge/-rustls-DEA584?style=flat&logo=rust&logoColor=black)

**Data**  
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![SQLite / D1](https://img.shields.io/badge/-SQLite%20%2F%20D1-003B57?style=flat&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat&logo=prisma&logoColor=white)

---

### 📊 GitHub Stats

<p align="center">
  <img
    width="49%"
    src="./assets/github-stats.svg"
    alt="Kalyan Gopalam's GitHub statistics"
  />
  <img
    width="49%"
    src="./assets/top-languages.svg"
    alt="Kalyan Gopalam's most-used languages"
  />
</p>

---

### 📌 Highlights

- Research on post-quantum signatures for secure boot on Cortex-M, with Prof. Rolando Herrero (Fall 2026)
- Benchmarked ML-KEM / ML-DSA against hardware-accelerated ECC on real nRF5340 silicon (CY5120 Applied Cryptography)
- Built a from-scratch Rust edge proxy + WAF with 485 tests and green CI
- Shipped post-quantum TLS and post-quantum E2EE messaging, end to end
- MITRE eCTF 2026 — secure embedded system (crypto, access control, protocol hardening)
- Hands-on work with honeypots, IDS/IPS, and network monitoring
- Focused on responsible disclosure and practical security engineering
- Attending Cloudflare Connect 2026 (Oct 19–21, San Francisco) — say hi

---

### 📫 Reach out

If you're working on security tooling, post-quantum migration, open-source security projects, or AppSec research — happy to talk.

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gk-eh/)
[![Portfolio](https://img.shields.io/badge/-Portfolio-D85A30?style=flat&logo=firefox&logoColor=white)](https://kalyangopalam.com/)
[![Connect](https://img.shields.io/badge/-Connect%20Card-FF5B3A?style=flat&logo=cloudflare&logoColor=white)](https://connect.kalyangopalam.com)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:kalyan.dev.me@gmail.com)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Kalyan-Deva)

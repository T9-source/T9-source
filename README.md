<div align="center">

<a href="https://git.io/typing-svg">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1200&color=D4AF37&center=true&vCenter=true&random=false&width=720&height=110&lines=Hi+there+%F0%9F%91%8B+I'm+AhmeD;Computer+Engineer+%E2%9A%99%EF%B8%8F;Full-Stack+Developer+%F0%9F%92%BB;Penetration+Tester+%F0%9F%94%90" alt="Typing SVG" /></a>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=14&pause=2000&color=F6E27A&center=true&vCenter=true&width=560&height=40&lines=%E2%9C%A6+T9+SOURCE+%E2%9C%A6+BUILT+DIFFERENT+%E2%9C%A6" alt="T9 Source" />

<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=T9-source&label=PROFILE+VIEWS&style=for-the-badge&color=D4AF37&labelColor=0d1117)](https://github.com/T9-source)
[![Followers](https://img.shields.io/github/followers/T9-source?label=FOLLOWERS&style=for-the-badge&color=D4AF37&labelColor=0d1117&cacheSeconds=3600)](https://github.com/T9-source?tab=followers)
[![Stars](https://img.shields.io/github/stars/T9-source?affiliations=OWNER&label=STARS&style=for-the-badge&color=D4AF37&labelColor=0d1117&cacheSeconds=3600)](https://github.com/T9-source?tab=repositories)
[![Open to Work](https://img.shields.io/badge/OPEN%20TO%20WORK-D4AF37?style=for-the-badge&logo=hackthebox&logoColor=black&labelColor=0d1117)](#-lets-connect)

</div>

---

## 🌊 Spotlight — Aether (Flagship)

<div align="center">

**Local-first, open-source API security proxy.** Intercept, inspect, replay
and rewrite HTTP/1 · HTTP/2 · WebSocket traffic — a Rust engine built for
speed, a virtualized console that stays fast at 100k+ flows, and **zero
telemetry, ever**.

[![Release](https://img.shields.io/github/v/release/T9-source/aether?label=RELEASE&style=for-the-badge&color=D4AF37&labelColor=0d1117&cacheSeconds=3600)](https://github.com/T9-source/aether/releases)
![Rust](https://img.shields.io/badge/Rust-1.85+-DEA584?style=for-the-badge&logo=rust&logoColor=white&labelColor=0d1117)
![License](https://img.shields.io/badge/License-Apache_2.0-blue?style=for-the-badge&labelColor=0d1117)
[![CI](https://img.shields.io/github/actions/workflow/status/T9-source/aether/ci.yml?label=CI&style=for-the-badge&labelColor=0d1117&cacheSeconds=3600)](https://github.com/T9-source/aether/actions/workflows/ci.yml)
[![CodeQL](https://img.shields.io/github/actions/workflow/status/T9-source/aether/codeql.yml?label=CodeQL&style=for-the-badge&labelColor=0d1117&cacheSeconds=3600)](https://github.com/T9-source/aether/actions/workflows/codeql.yml)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/T9-source/aether/badge)](https://api.scorecard.dev/projects/github.com/T9-source/aether)

</div>

- 🔐 **TLS MITM done right** — rustls + rcgen CA, wire-truth preserving codec
- ⚡ **100k flows without breaking a sweat** — SQLite WAL + FTS5 search (~0.5ms pages), benchmarked in CI with performance budgets
- 🧩 **Sandboxed WASM plugin host (V0.3)** — fail-closed `plugin.toml` manifests, capability vocabulary, checksum pinning — plugins edit, never execute
- 🤖 **MCP built-in** — your local AI assistant (Claude Desktop, VS Code) queries your captured flows over MCP — read-only by default, fully offline
- 🛡️ **Hardened like a security product should be** — fuzzed parsers, CodeQL, SHA-pinned CI, OpenSSF Scorecard, coordinated disclosure policy

<div align="center">

| Intercept | History | Viewer | Connect |
|---|---|---|---|
| ![Intercept](assets/aether-intercept.webp) | ![History](assets/aether-history.webp) | ![Viewer](assets/aether-viewer.webp) | ![Connect](assets/aether-connect.webp) |

</div>

```bash
# 1) grab a release binary — macOS (arm64/x64) · Linux (musl static) · Windows
#    https://github.com/T9-source/aether/releases/latest
# 2) or run from source:
cargo run -p aether-cli -- serve --memory   # up in 30 seconds
```

> **Why not mitmproxy or Burp?** Every flow lands in **local SQLite your AI can
> search over MCP** — mitmproxy keeps flows in RAM (their own tracker, open
> since 2017), Burp AI is cloud-only, Reqable is closed-source. Full
> vendor-sourced comparison → [docs/comparison.md](https://github.com/T9-source/aether/blob/main/docs/comparison.md)

📌 **Repo:** [T9-source/aether](https://github.com/T9-source/aether) ·
[Release 0.2.1](https://github.com/T9-source/aether/releases/tag/0.2.1) ·
Roadmap: WASM plugin host ✓ → query language → AI layer (BYO-key, off by default)

---

## 💫 About Me

- 🔐 **Penetration Tester** — web application pentesting, network security & vulnerability assessment
- 💻 **Full-Stack Developer** — management systems, e-commerce stores, dashboards & web design
- ⚙️ **Computer Engineer** — I build it, I break it, then I secure it
- 🌍 Working with clients worldwide — open for remote projects & collaborations

---

## ⭐ Security Flagship — CloudFail-Killer (CloudKill)

<div align="center">

### 🔓 [CloudKill — Origin IP Discovery](https://github.com/T9-source/cloudfail-killer)

**Multi-source, IPv6-native reconnaissance** that finds origin
servers hidden behind Cloudflare — 15+ passive & active data sources, a 7-stage enrichment
pipeline, and confidence-scored results. Built for pentesters & bug bounty hunters.

[![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?logo=python&logoColor=white)](https://github.com/T9-source/cloudfail-killer)
[![PyPI](https://img.shields.io/pypi/v/cloudkill?logo=pypi&logoColor=white)](https://pypi.org/project/cloudkill/)
[![Tests](https://img.shields.io/badge/tests-343%20passed-17A05D?logo=pytest&logoColor=white)](https://github.com/T9-source/cloudfail-killer)
[![IPv6](https://img.shields.io/badge/IPv6--Native-FF6B35)](https://github.com/T9-source/cloudfail-killer)
[![SARIF](https://img.shields.io/badge/exports-SARIF%202.1-4B32C3)](https://github.com/T9-source/cloudfail-killer)
[![License](https://img.shields.io/badge/license-MIT-17A05D)](https://github.com/T9-source/cloudfail-killer)

<img src="assets/cloudfail-repo.png" alt="CloudKill" width="640" />

`crt.sh` · `Shodan` · `Censys` · `Wayback` · `URLScan` · `DNSDumpster` · `GitHub Dorking` · signed reports (ed25519) · plugin sources · CI mode

</div>

---

## 🌐 Live Systems

<div align="center">

| ✦ | System | Stack |
|---|---|---|
| 🍳 | **[Gadgeta — Magic & Innovation](https://gadgate.vercel.app)** | Next.js 16 · Prisma · Neon Postgres |
| 👞 | **[Yalla Shiaka — Shoes Store](https://yallashiaka.vercel.app)** | Next.js 16 · Prisma · Admin & Supervisors |
| 🔧 | **[Noor Center — Maintenance System](https://noorcenter.gt.tc)** | Laravel · MySQL · Role-based |
| 🛵 | **[اطلبني — Zone Delivery App](https://otlobny-chi.vercel.app)** | Android APK · Web App · Admin Panel · V2 |
| 💼 | **[My Portfolio](https://jemyv2.vercel.app)** | Next.js 16 · React 19 · bilingual & dark-first |

</div>

---

## 🛵 Spotlight — اطلبني (Latest Release)

<div align="center">

<img src="assets/otlobny-qr.png" alt="اطلبني — امسح واطلب" width="170" />

**📱 امسح الكود واطلب من المنيب فوراً**

**أول زون-ابليكيشن في مصر** — منصة توصيل مخصوصة لمنطقة المنيب بالكامل:
مطاعم بتدير منيوهاتها بنفسها + أي طلبات يومية (سوبر ماركت · صيدلية · مشاوير) + كباتن من أهل المنطقة بإسناد لحظي + لوحة تحكم كاملة — **بصفر تكاليف سيرفر**.

[![Release](https://img.shields.io/badge/release-v2.1-0098B0?style=for-the-badge&labelColor=0d1117)](https://otlobny-chi.vercel.app)
[![Security](https://img.shields.io/badge/security%20audit-0%20findings-17A05D?style=for-the-badge&labelColor=0d1117)](https://otlobny-chi.vercel.app)
[![Server cost](https://img.shields.io/badge/server%20cost-%240-2E7DD1?style=for-the-badge&labelColor=0d1117)](https://otlobny-chi.vercel.app)
[![OPEN APP](https://img.shields.io/badge/OPEN%20APP-%F0%9F%9B%B5%20LIVE-0098B0?style=for-the-badge&labelColor=0d1117)](https://otlobny-chi.vercel.app/)

| تطبيق أندرويد | لوحة تحكم الإدارة | طلب أونلاين |
|---|---|---|
| <img src="assets/otlobny-app.png" width="240" alt="app" /> | <img src="assets/otlobny-admin.png" width="300" alt="admin" /> | <img src="assets/otlobny-web.png" width="240" alt="web" /> |

**جديد v2.1:** بوابة أصحاب المطاعم (كل مطعم يدير منيوه وأسعاره وصور أصنافه من التطبيق) · إسناد الأوردرات للكباتن بمهلة قبول 30 ثانية وإعادة توجيه تلقائية · تصعيد واتساب تلقائي للإدارة بعد 5 دقايق من غير استلام · أرشفة شهرية تحافظ على البيانات مهما كبرت.

**تجربة كاملة لايف:** تطبيق أندرويد + موقع طلب + لوحة إدارة + نظام كباتن معتمدين — شغالة على منطقة حقيقية، والبنية جاهزة للتوسع لمناطق جديدة.

</div>

---

## 🚀 Featured Projects

| Project | About |
|---|---|
| 🌊 **[Aether](https://github.com/T9-source/aether)** → [**v0.2.1**](https://github.com/T9-source/aether/releases/tag/0.2.1) | **Flagship** API security proxy in Rust — MITM h1/h2/WS · 100k-flow console · sandboxed WASM plugin host · MCP for local AI · fuzzed + Scorecard-hardened · zero telemetry |
| 🔓 **[CloudFail-Killer (CloudKill)](https://github.com/T9-source/cloudfail-killer)** → [**PyPI**](https://pypi.org/project/cloudkill/) | **Flagship security tool** — origin-IP discovery behind Cloudflare · 15+ sources · 343 tests · SARIF & signed reports |
| 🛵 **[Otlobny — اطلبني](https://otlobny-chi.vercel.app)** → [**LIVE**](https://otlobny-chi.vercel.app/) | 🚀 Zone-locked delivery platform — Android (native Java) · Web · Admin dashboard · Restaurant self-service portal · 30s live dispatch · 0 security findings |
| 🔧 **[Noor Center](https://noorcenter.gt.tc)** → [**LIVE**](https://noorcenter.gt.tc) | 🔧 Maintenance-center management system — Laravel · MySQL · roles |
| 🍳 **[Gadgeta Store](https://gadgate.vercel.app)** → [**LIVE**](https://gadgate.vercel.app) | 🍳 Magic & Innovation e-commerce — golden deals · coupons · Neon Postgres |
| 👞 **[Yalla Shiaka Store](https://yallashiaka.vercel.app)** → [**LIVE**](https://yallashiaka.vercel.app) | 🥾 E-commerce with admin & supervisor dashboards — Next.js · Prisma |
| [**Cinematic Landings**](https://github.com/T9-source/monolith-landing) | ⬡ MONOLITH · OBLIVION · ECHO · NOVA — WebGL experiences, zero build |
| 💼 **[Portfolio Website](https://jemyv2.vercel.app)** → [**LIVE**](https://jemyv2.vercel.app) | 💼 Bilingual (AR/EN) portfolio — Next.js 16 · React 19 · dark-first · live GitHub dashboard |

---

## 🛡️ Cybersecurity Arsenal

<div align="center">

[![Kali Linux](https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)](https://www.kali.org/)
[![Burp Suite](https://img.shields.io/badge/Burp%20Suite-D4AF37?style=for-the-badge&labelColor=0d1117&color=D4AF37)](https://portswigger.net/burp)
[![Nmap](https://img.shields.io/badge/Nmap-2E7D32?style=for-the-badge&labelColor=0d1117&color=2E7D32)](https://nmap.org/)
[![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&labelColor=0d1117&color=2596CD)](https://www.metasploit.com/)
[![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&labelColor=0d1117&color=1679A7)](https://www.wireshark.org/)
[![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-5C90BF?style=for-the-badge&labelColor=0d1117&color=5C90BF)](https://www.zaproxy.org/)
[![sqlmap](https://img.shields.io/badge/sqlmap-D4AF37?style=for-the-badge&labelColor=0d1117&color=8B6914)](https://sqlmap.org/)
[![Hydra](https://img.shields.io/badge/THC%20Hydra-6C3483?style=for-the-badge&labelColor=0d1117&color=6C3483)](https://github.com/vanhauser-thc/thc-hydra)
[![Hashcat](https://img.shields.io/badge/Hashcat-D4AF37?style=for-the-badge&labelColor=0d1117&color=8B6914)](https://hashcat.net/hashcat/)
[![Nessus](https://img.shields.io/badge/Nessus-00A0DF?style=for-the-badge&labelColor=0d1117&color=00A0DF)](https://www.tenable.com/products/nessus)
[![Aircrack-ng](https://img.shields.io/badge/Aircrack--ng-1B865F?style=for-the-badge&labelColor=0d1117&color=1B865F)](https://www.aircrack-ng.org/)

</div>

---

## 💻 Tech Stack

<div align="center">

**Frontend & UI**

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind,bootstrap&theme=dark" alt="Frontend skills" /></a>

**Backend & Databases**

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=nodejs,express,php,laravel,python,rust,mysql,postgres,mongodb&theme=dark" alt="Backend skills" /></a>

**Tools & DevOps**

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=git,github,docker,linux,bash,vscode,postman,vercel&theme=dark" alt="Tools skills" /></a>

**Mobile & Delivery**

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=java,android,flutter&theme=dark" alt="Mobile skills" /></a>

</div>

---

## 📊 GitHub Stats

<div align="center">

<img width="70%" src="https://streak-stats.demolab.com?user=T9-source&hide_border=true&background=0d1117&ring=D4AF37&fire=D4AF37&currStreakLabel=D4AF37&sideLabels=c9d1d9&dates=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9" alt="GitHub streak" />

<br/>

<img src="profile-summary-card-output/github_dark/0-profile-details.svg" alt="Profile summary" />
<img src="profile-summary-card-output/github_dark/1-repos-per-language.svg" alt="Repos per language" />

<img src="profile-summary-card-output/github_dark/2-most-commit-language.svg" alt="Most commit language" />
<img src="profile-summary-card-output/github_dark/4-productive-time.svg" alt="Productive time" />

<sub>🔄 self-rendered daily by GitHub Actions — never rate-limited</sub>

</div>

---

## 🏆 Achievements

<div align="center">

[![🥇 5 LIVE SYSTEMS](https://img.shields.io/badge/🥇-5_LIVE_SYSTEMS-D4AF37?style=for-the-badge&labelColor=0d1117)](https://github.com/T9-source?tab=repositories)
[![📦 10+ REPOSITORIES](https://img.shields.io/badge/📦-10%2B_REPOSITORIES-D4AF37?style=for-the-badge&labelColor=0d1117)](https://github.com/T9-source?tab=repositories)
[![🌊 AETHER 0.2.1 RELEASED](https://img.shields.io/badge/🌊-AETHER_0.2.1_RELEASED-D4AF37?style=for-the-badge&labelColor=0d1117)](https://github.com/T9-source/aether/releases)
[![🔓 CLOUDKILL ON PYPI](https://img.shields.io/badge/🔓-CLOUDKILL_ON_PYPI-D4AF37?style=for-the-badge&labelColor=0d1117)](https://pypi.org/project/cloudkill/)
[🛵 OTLOBNY v2.1 LIVE](https://img.shields.io/badge/🛵-OTLOBNY_v2.1_LIVE-0098B0?style=for-the-badge&labelColor=0d1117)
[![🔐 SECURITY FIRST](https://img.shields.io/badge/🔐-SECURITY_FIRST-17A05D?style=for-the-badge&labelColor=0d1117)](https://github.com/T9-source/cloudfail-killer)
[![⚡ ZERO SERVER COSTS](https://img.shields.io/badge/⚡-ZERO_SERVER_COSTS-2E7DD1?style=for-the-badge&labelColor=0d1117)](https://otlobny-chi.vercel.app)

</div>

---

## 🤝 Let's Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-T9--source-D4AF37?style=for-the-badge&logo=github&logoColor=black&labelColor=0d1117)](https://github.com/T9-source)
[![Email](https://img.shields.io/badge/Email-ntgi46@proton.me-D4AF37?style=for-the-badge&logo=protonmail&logoColor=black&labelColor=0d1117)](mailto:ntgi46@proton.me)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-%2B20%20114%20825%202590-D4AF37?style=for-the-badge&logo=whatsapp&logoColor=black&labelColor=0d1117)](https://wa.me/201148252590)

**Open for** pentest engagements 🔐 • full-stack builds 💻 • collaborations 🤝

*Find a vulnerability in my code? Congrats — you passed the first test.* 😏

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=12&pause=2000&color=D4AF37&center=true&vCenter=true&width=420&height=36&lines=%E2%9C%A6+AHMED+%C2%B7+T9+SOURCE+%C2%B7+CAIRO%2C+EGYPT+%E2%9C%A6" alt="Signature" />

</div>

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/T9-source/T9-source/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/T9-source/T9-source/output/github-snake.svg">
  <img alt="Snake animation" src="https://raw.githubusercontent.com/T9-source/T9-source/output/github-snake.svg">
</picture>

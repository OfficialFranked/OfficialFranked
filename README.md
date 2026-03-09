<h1 align="center">Franked</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=30&duration=3000&pause=1000&center=true&vCenter=true&width=750&lines=Secure+Software+Licensing+Platform;Hardware+Locked+License+Keys;Cloud+Protection+%26+Launcher+Delivery;Developer+SDKs+%7C+Analytics+%7C+Webhooks" />
</p>

<p align="center">
The modern platform for managing software licenses.
</p>

<p align="center">
Generate keys, track activations, bind to hardware, and protect your revenue — all from a single dashboard.
</p>

<p align="center">
<img src="https://img.shields.io/badge/license-Proprietary-blue.svg">
<img src="https://img.shields.io/badge/platform-SaaS-black">
<img src="https://img.shields.io/badge/security-HMAC%20%2B%20Encryption-green">
</p>

---

# 🚀 Features

| Feature | Description |
|--------|-------------|
| **License Keys** | LIFETIME, TIME_BASED, and SUBSCRIPTION licenses with flexible expiry and activation limits |
| **HWID Locking** | Bind licenses to hardware. Prevent key sharing while allowing device changes |
| **Cloud Protect** | VMProtect-style exe protection: XOR-encrypted payloads, anti-debug, anti-tamper |
| **Secure API** | HMAC-signed requests, encrypted responses, anti-replay protection |
| **Webhooks** | Real-time events: `license.activated`, `license.revoked`, `anomaly_detected` |
| **Analytics** | Activation trends, geo distribution, usage monitoring |
| **SDKs** | Python, C++, C#, Rust — integrate in minutes |
| **Launcher** | Versioned app delivery with signed manifests |

---

# 🧩 Stack

### Backend
- **Fastify**
- **Prisma**
- **PostgreSQL**
- **Redis**

### Frontend
- **Next.js 15**
- **React 19**
- **TailwindCSS**

### Infrastructure
- **Railway** → API deployment  
- **Netlify** → Web + Admin dashboard  

### Security
- JWT authentication  
- HMAC request signing  
- encrypted payloads  
- hardware fingerprinting  

---

# ⚡ Quick Start

```bash
git clone https://github.com/OfficialFranked/license-platform.git
cd license-platform
npm install
cp .env.example .env
npm run db:push
npm run dev

See:

RAILWAY_SETUP.md

for production deployment.

📂 Project Structure
license-platform/

apps/
  api/            Fastify API (auth, billing, licenses, protect, webhooks)
  web/            Customer dashboard (franked.xyz)
  admin/          Admin panel (admin.franked.xyz)

packages/
  database/       Prisma schema
  auth/           JWT helpers and middleware
  crypto/         HMAC, encryption, license utilities
  launcher-core/  Manifest signing, fingerprint hashing
  protect-launcher/ C++ stub for exe protection

clients/
  demo apps

scripts/
  PayPal plan creation, etc.
🌐 Platform Links
Service	Link
Dashboard	https://franked.xyz

Admin	https://admin.franked.xyz

Docs	https://franked.xyz/docs

Pricing	https://franked.xyz/pricing
🏆 GitHub Stats
<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=OfficialFranked&show_icons=true&theme=tokyonight&hide_border=true" /> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=OfficialFranked&layout=compact&theme=tokyonight&hide_border=true" /> </p>
🔥 Contribution Streak
<p align="center"> <img src="https://github-readme-streak-stats.herokuapp.com/?user=OfficialFranked&theme=tokyonight&hide_border=true" /> </p>
👀 Repository Views
<p align="center"> <img src="https://komarev.com/ghpvc/?username=OfficialFranked&style=for-the-badge&color=blue"> </p>
📜 License

Proprietary.
All rights reserved.

<p align="center"> Built by the Franked platform team. </p> ```

# Sohan (@SohanV1)

**Systems & Web Engineer** · Focused on defensive OSINT, network reconnaissance, internet infrastructure, and production web engineering.

```
• Focus: Defensive OSINT · Network Protocols (RFC 8484 / 6962) · Full-Stack Systems
• Primary Stack: TypeScript · Next.js (App Router) · React 18/19 · Node.js · Tailwind CSS
• Environment: Linux (Kali / Ubuntu) · Windows · POSIX Shell · Git
• Philosophy: Strict YAGNI · Zero-bloat architectures · Test-driven verification
```

---

## 🏛️ Flagship Engineering Projects

### 🔍 [Internet Archaeologist Platform](https://github.com/SohanV1/internet-archaeologist-platform)
*Multi-Agent Defensive OSINT & Temporal Forensics Suite*
- **The Engineering Challenge**: Building a distributed passive reconnaissance system that reconstructs historical web footprints and surfaces infrastructure drift without active scanning or touching target infrastructure.
- **Technical Architecture**:
  - RFC 8484 DNS-over-HTTPS (DoH) wire-format resolver and RFC 6962 Certificate Transparency log parser (`crt.sh`).
  - Temporal Wayback Machine CDX timeline indexer with automated diff and change detection.
  - Server-Sent Events (SSE) streaming telemetry pipeline with unbuffered client updates.
  - Outbound SSRF mitigation pipeline blocking internal IP spaces, loopbacks, and dangerous protocols (`file://`, `gopher://`).
  - Cryptographic evidence ledger utilizing SHA-256 integrity hashes for forensic audit chains.
- **Verification & Rigor**: 22 Jest test suites with **293 verified passing tests**; dual-attestation Target Authorization Gate enforcing compliance with `ETHICAL_OSINT_CHARTER.md`.
- **Stack**: Next.js 16 (App Router), React 19, TypeScript (Strict), Tailwind CSS, D3.js, Jest.
- **Deployment**: [Live Production Platform](https://internet-archaeologist-platform.netlify.app) · [Source Code](https://github.com/SohanV1/internet-archaeologist-platform)

---

### ⌚ [AI Builder Notifier](https://github.com/SohanV1/ai-builder-notifier)
*Smartwatch & WhatsApp Interactive Gate for Autonomous AI Coding Workflows*
- **The Engineering Challenge**: Autonomous coding agents running in terminal loops can inadvertently introduce unwanted scaffolding or execute destructive edits. This tool provides an asynchronous, human-in-the-loop approval bridge.
- **Technical Architecture**:
  - Real-time WhatsApp multi-device integration via Baileys Web protocol.
  - Change Significance Analyzer (`utils.js`) computing AST/diff line counts and heuristic risk before triggering push alerts.
  - Interactive two-way daemon capturing user `approve` / `reject` commands with automated rollback execution via shell wrappers.
- **Stack**: Node.js, JavaScript (ESM), Baileys, Shell / PowerShell, OpenCode / Antigravity plugins.
- **Source Code**: [GitHub Repository](https://github.com/SohanV1/ai-builder-notifier)

---

### 🌿 [Iris Biotech](https://irisbiotech.co.in)
*High-Performance B2B Export Architecture & Cold-Chain Logistics Platform*
- **The Engineering Challenge**: Replacing slow aggregator listings with a high-performance, edge-rendered commercial quotation portal for international floriculture trade, engineered for sub-second international loading.
- **Technical Architecture**:
  - React 18, TypeScript, and Vite bundled with custom post-build SSG pre-rendering generating 28 pre-rendered route directories.
  - Complete JSON-LD enterprise schema disambiguating agricultural entity identity from life-science namesakes across search engines.
  - Secure quotation request pipeline integrated directly with business mail workflows.
- **Stack**: React 18, TypeScript, Vite, Tailwind CSS, Lucide React, Netlify Edge CDN.
- **Deployment**: [Verified Production Site](https://irisbiotech.co.in)

---

### 🌸 [3G Floratech 3D Showcase](https://3g-floritech.netlify.app)
*Interactive 3D Cutout & Commercial Produce Engineering Platform*
- **The Engineering Challenge**: Delivering an interactive, 360-degree viewport showcase with glassmorphism UI tokens while maintaining low bundle size and 60 FPS scroll performance across mobile and desktop.
- **Technical Architecture**:
  - Vite 6 build pipeline with rollup code-splitting and zero bloated 3D heavyweight runtimes.
  - Scroll-driven MorphFlow timeline with custom CSS glassmorphism and agronomic data matrices.
- **Stack**: Vite 6, Modern ES6+ JavaScript, Responsive CSS3, Netlify CI/CD.
- **Deployment**: [Live Showcase Deployment](https://3g-floritech.netlify.app)

---

### 🎯 [JEE Advanced Goal Tracker](https://github.com/SohanV1/jee-advanced-goal-tracker-)
*Academic Analytics & 6-Stage Chapter Lifecycle Engine*
- **The Engineering Challenge**: Managing high-volume academic syllabus velocity across Physics, Chemistry, and Mathematics with persistent client-side state and cloud resilience.
- **Technical Architecture**:
  - 6-stage chapter workflow engine: Theory → Coaching Module → PYQ Analysis → 3x Scheduled Spaced-Repetition Revisions.
  - Client-side `localStorage` data persistence with portable JSON backup import/export and Firestore security rules synchronization.
- **Stack**: HTML5, CSS3, JavaScript, Firebase Firestore Rules.
- **Source Code**: [GitHub Repository](https://github.com/SohanV1/jee-advanced-goal-tracker-)

---

## 🛠️ Demonstrated Technical Capabilities

| Domain | Practical & Verified Experience |
| :--- | :--- |
| **Defensive Security & OSINT** | RFC 8484 DNS-over-HTTPS, RFC 6962 CT Logs, Wayback CDX, SSRF Defense, PII Masking, Forensic Hashing |
| **Languages & Runtimes** | TypeScript (Strict), JavaScript (ES2024+), Node.js, Bash / POSIX Shell, HTML5, CSS3 |
| **Frameworks & UI** | Next.js 14/16 (App Router), React 18/19, Vite, Tailwind CSS, D3.js, Lucide |
| **Architecture & Protocols** | REST, Server-Sent Events (SSE), Webhooks, JSON-LD Schema, Git, Netlify CI/CD |
| **System Environments** | Kali Linux, Ubuntu WSL, Windows 11, Command-Line Utilities, Home Assistant IoT |

---

## 🔬 Current Engineering Focus

- Hardening DNS and SSL certificate transparency ingestion pipelines with automated ASN clustering.
- Exploring multi-agent coordination pipelines and deterministic verification in agentic software engineering.
- Studying physical cold-chain IoT telemetry and agricultural sensor automation.

---

## 📬 Contact & Links

- **GitHub**: [@SohanV1](https://github.com/SohanV1)
- **Live Systems**: [Internet Archaeologist](https://internet-archaeologist-platform.netlify.app) · [Iris Biotech](https://irisbiotech.co.in) · [3G Floratech](https://3g-floritech.netlify.app)

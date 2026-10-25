<div align="center">

<a href="https://fixsphere.netlify.app">
  <img src="https://demolab.com" alt="FixSphere Header" />
</a>

<pre>
███████╗██╗██╗  ██╗███████╗██████╗ ██╗  ██╗███████╗██████╗ ███████╗
██╔════╝██║╚██╗██╔╝██╔════╝██╔══██╗██║  ██║██╔════╝██╔══██╗██╔════╝
█████╗  ██║ ╚███╔╝ ███████╗██████╔╝███████║█████╗  ██████╔╝█████╗  
██╔══╝  ██║ ██╔██╗ ╚════██║██╔═══╝ ██╔══██║██╔══╝  ██╔══██╗██╔══╝  
██║     ██║██╔╝ ██╗███████║██║     ██║  ██║███████╗██║  ██║███████╗
╚═╝     ╚═╝╚═╝  ╚═╝╚══════╝╚═╝     ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚══════╝
</pre>

<a href="https://fixsphere.netlify.app">
  <img src="https://demolab.com" alt="Terminal Telemetry" />
</a>

</div>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=fixsphere-prod&label=REPO%20VIEWS&color=ff6b00&style=flat-square" alt="Views" />
  <img src="https://img.shields.io/badge/BUILD-PASSING-10b981?style=flat-square&logo=githubactions&logoColor=white" alt="Build" />
  <img src="https://img.shields.io/badge/OCR_ENGINE-TESSERACT_v5-3b82f6?style=flat-square" alt="OCR" />
  <img src="https://img.shields.io/badge/RADAR_RADIUS-10_KM-f59e0b?style=flat-square" alt="Radar" />
</p>

<p align="center">
  <a href="https://fixsphere.netlify.app" target="_blank">
    <img src="https://img.shields.io/badge/%F0%9F%9A%80_LAUNCH_LIVE_PROTOTYPE-FF6B00?style=for-the-badge&logoColor=white" alt="Launch Live App" />
  </a>
  <a href="#features">
    <img src="https://img.shields.io/badge/FEATURES-111726?style=for-the-badge&logo=sparkles&logoColor=ff6b00" alt="Features" />
  </a>
  <a href="#architecture">
    <img src="https://img.shields.io/badge/ARCHITECTURE-111726?style=for-the-badge&logo=serverless&logoColor=3b82f6" alt="Architecture" />
  </a>
  <a href="#tech-stack">
    <img src="https://img.shields.io/badge/TECH_STACK-111726?style=for-the-badge&logo=javascript&logoColor=10b981" alt="Tech Stack" />
  </a>
  <a href="#team">
    <img src="https://img.shields.io/badge/TEAM-111726?style=for-the-badge&logo=github&logoColor=ffffff" alt="Team" />
  </a>
</p>

*Bringing **Zomato & Rapido-style** hyperlocal doorstep convenience to electronics repair and warranty management.*

---

## Features

FixSphere eliminates traditional offline friction in electronics repair—from faded paper receipts to hours wasted in service queues:

* **🧠 Neural Vision Vault:** Snaps paper receipts or invoices and automatically extracts Brand, Model, 15-Digit IMEI/Serial, Purchase Date, and Price via client-side OCR (*Tesseract.js*).
* **🛰️ 10km Category-Isolated Radar:** Maps verified service hubs within a 10km radius while strictly isolating **Smartphone Hubs** vs. **Laptop Hubs** so repair categories never collide.
* **🛵 Doorstep Technician Dispatch:** Rapido-style on-demand technician booking with transparent distance pricing (**₹49 Base Fee + ₹15/km Travel Fuel Charge**) and a 5–10 min verification call.
* **🔐 Cryptographic Receipt Export:** Generates downloadable tamper-proof PNG thermal receipts to prevent warranty claim rejections caused by lost bills.

---

## Architecture

```rust
 ____________________________________________________________________________________

|                                                                                    |
|   .---------.        .--------------.        .-------------.           __          |
|   | "PAPER" |  ===>  |  NEURAL_OCR  |  ===>  |  10KM_RADAR |  ===>   _ \<_         |
|   | INVOICE |        | (TESSERACT)  |        |  HUB_ENGINE |        (_)/(_)        |
|   '---------'        '--------------'        '-------------'     DOORSTEP_TECH     |
|        |                    |                       |                  |           |
|   [Snap Photo]       [Extracts IMEI]         [Category Match]   [49 + 15/km Fee]   |
|____________________________________________________________________________________|
```

---

## Tech Stack

| Layer | Technology / Protocol |
| :--- | :--- |
| **Frontend UI & 3D Shaders** | HTML5, Tailwind CSS, Vanilla JS (3D Perspective Tilt, Silver Glare Shaders) |
| **Geospatial Radar Engine** | Leaflet.js, Geoapify Geocoding API, Haversine Distance Formula |
| **Client-Side Neural Vision** | Tesseract.js (100% On-Device OCR, Zero Server Latency) |
| **Storage & Deployment** | Browser LocalStorage, HTML5 Canvas API, Netlify Edge CDN |

---

## Team

- **Priyanshu Jasrotia** (Lead Developer) — [GitHub Profile](https://github.com/prityanshuj)
- **Akriti** (Presentation & Strategy) — [GitHub Profile](https://github.com/)
- **[Team Member 3]** (Documentation & Testing) — [GitHub Profile](https://github.com/)

---

<div align="center">
  <b>⚡ FixSphere — Built for Seamless Hardware Protection ⚡</b>
</div>

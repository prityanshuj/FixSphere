<p align="center">
  <img src="https://demolab.com" alt="FixSphere Header" />
</p>

```text
███████╗██╗██╗  ██╗███████╗██████╗ ██╗  ██╗███████╗██████╗ ███████╗
██╔════╝██║╚██╗██╔╝██╔════╝██╔══██╗██║  ██║██╔════╝██╔══██╗██╔════╝
█████╗  ██║ ╚███╔╝ ███████╗██████╔╝███████║█████╗  ██████╔╝█████╗  
██╔══╝  ██║ ██╔██╗ ╚════██║██╔═══╝ ██╔══██║██╔══╝  ██╔══██╗██╔══╝  
██║     ██║██╔╝ ██╗███████║██║     ██║  ██║███████╗██║  ██║███████╗
╚═╝     ╚═╝╚═╝  ╚═╝╚══════╝╚═╝     ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚══════╝
```

<p align="center">
  <img src="https://demolab.com" alt="Terminal Telemetry" />
</p>

<p align="center">
  <img src="https://komarev.com" alt="Views" />
  <img src="https://shields.io" alt="Build" />
  <img src="https://shields.io" alt="OCR" />
  <img src="https://shields.io" alt="Radar" />
</p>

<p align="center">
  <a href="https://fixsphere.netlify.app" target="_blank">
    <img src="https://shields.io" alt="Launch Live App" />
  </a>
  <a href="#features">
    <img src="https://shields.io" alt="Features" />
  </a>
  <a href="#architecture">
    <img src="https://shields.io" alt="Architecture" />
  </a>
  <a href="#tech-stack">
    <img src="https://shields.io" alt="Tech Stack" />
  </a>
  <a href="#team">
    <img src="https://shields.io" alt="Team" />
  </a>
</p>

<p align="center">
  <em>Bringing <b>Zomato & Rapido-style</b> hyperlocal doorstep convenience to electronics repair and warranty management.</em>
</p>

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

- **Priyanshu Jasrotia** (Lead Developer) — [GitHub Profile](https://github.com)
- **Akriti** (Presentation & Strategy) — [GitHub Profile](https://github.com)
- **[Team Member 3]** (Documentation & Testing) — [GitHub Profile](https://github.com)

---

<div align="center">
  <b>⚡ FixSphere — Built for Seamless Hardware Protection ⚡</b>
</div>

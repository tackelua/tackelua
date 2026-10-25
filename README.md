# Bùi Gia Thịnh (`@tackelua`)

**Embedded Engineering Lead & Project Manager (PMP® · PSM™) · Founder at [GithSoft](https://githsoft.com)**

<p align="center">
  <img src="https://img.shields.io/badge/Qt%20%2F%20C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" height="18" alt="C++">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="18" alt="Python">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" height="18" alt="Docker">
  <img src="https://img.shields.io/badge/IoT%20%2F%20ESP-41CD52?style=flat-square&logo=arduino&logoColor=white" height="18" alt="IoT">
  <a href="https://portctl.pages.dev"><img src="https://img.shields.io/badge/portctl-Rust_CLI-DEA584?style=flat-square&logo=rust&logoColor=white" height="18" alt="portctl"></a>
  <a href="https://githsoft.com"><img src="https://img.shields.io/badge/GithSoft-00e5ff?style=flat-square&logo=cloudflare&logoColor=white" height="18" alt="GithSoft"></a>
  <a href="https://sosline.org"><img src="https://img.shields.io/badge/sosline.org-ef4444?style=flat-square&logo=google-earth&logoColor=white" height="18" alt="sosline"></a>
  <img src="https://img.shields.io/badge/PMP%C2%AE%20%7C%20PSM%E2%84%A2-6366f1?style=flat-square" height="18" alt="Certifications">
  <a href="https://www.youtube.com/@buigiathinh"><img src="https://img.shields.io/badge/YouTube-red?style=flat-square&logo=youtube&logoColor=white" height="18" alt="YouTube"></a>
</p>

> 10+ years in systems engineering (since 2016). Currently serving as **Embedded Engineering Lead & Project Manager** (Qt/C++, Embedded Linux) with **PMP® & PSM™** credentials. Now coding primarily with purpose: building high-leverage internal tools, automation pipelines, and AI-assisted workflows to empower the engineering team and streamline Project Management (PM) execution, while crafting native systems tooling under [GithSoft](https://githsoft.com).

---

### 🚀 Featured Systems & Products

| Project | Domain | Stack | Highlights & Deployment |
| :--- | :--- | :--- | :--- |
| **[portctl](https://portctl.pages.dev)** | Modern Systems | Pure Rust, Cloudflare Tunnels, POSIX | Zero-daemon port manager, socket probe, and instant edge ingress. `brew install tackelua/tap/portctl` |
| **[AutoMiner](https://autominer-archived.githsoft.com)** | IoT Hardware | C++, ESP8266, Hardware Watchdog | Industrial mining rig watchdog & multi-relay power recovery controller (Archived Heritage, 2017). |
| **[WordRadar](https://wordradar.githsoft.com)** | NLP / EdTech | Node.js, Express, SQLite, D3.js | Smart English frequency analyzer powered by SM-2 spaced repetition engine. |
| **[YouTube Mindmap](https://mindmap.githsoft.com)** | AI Distillation | Next.js 14, MindElixir Canvas, LLM Pipeline | AI-driven video transcript extraction to interactive multi-dimensional mindmaps. |
| **[SOS Platform](https://sosline.org)** | Civic Tech / Edge | Cloudflare Pages, Workers, D1, PWA | Humanitarian emergency rescue platform (`sosvn.vn`) running at zero infra cost. |
| **Torvin** *(Active Dev · Private Alpha)* | Secret Vault / AI Security | Rust, AES-GCM, Argon2id, Local Enclave | Zero-knowledge secrets vault and token broker for developers & AI agents (preventing token leaks). |
| **[GithSoft Studio](https://githsoft.com)** | Engineering Lab | Modern Web, Edge CDN | Central portal for GithSoft software tools, AI lab, and engineering publications. |
| **[GithSoft Image Lab](https://imagelab.githsoft.com)** | AI Vision | On-Device AI, WebGL, Compute Workers | High-throughput AI image enhancement & neural upscaling running on client GPU. |

---

### 🧭 Engineering Portfolio

<details>
<summary>🖥️ <b>Embedded Systems, Linux & Qt/C++ (Click to expand)</b></summary>

> Deep experience in C++ systems programming, Qt MOC internals, memory benchmarks, and automotive dashboard interfaces.

- **[QtMqttDevicesEmulator](https://github.com/tackelua/QtMqttDevicesEmulator)** *(Public)*: High-throughput multi-threaded Qt5/C++ emulator simulating fleets of IoT devices.
- **[Qt-Containers-Compare](https://github.com/tackelua/Qt-Containers-Compare)** *(Public)*: Micro-benchmarking and memory cache locality analysis across Qt container types.
- **[Qt-PropertyHelper](https://github.com/tackelua/Qt-PropertyHelper)** *(Public)*: C++ template/macro metaprogramming helper eliminating `Q_PROPERTY` boilerplate.
- **[AnalogDigitsClock](https://github.com/tackelua/AnalogDigitsClock)** *(Public)*: Hybrid mechanical analog & digital clock engine rendered via QML Scene Graph.
- **DemoQtAutomotive & QtDashboardSample** *(Showcase)*: 60 FPS Digital Instrument Cluster for automotive systems.
</details>

<details>
<summary>⚡ <b>IoT Hardware, Microcontrollers & Industrial Automation (Click to expand)</b></summary>

> Designing custom schematics, hardware watchdog timers, relay power controllers, and RTOS firmware since 2016.

- **[AutoMiner Series (V1 – V3.1)](https://autominer-archived.githsoft.com)** ([GitHub](https://github.com/tackelua/autominer-web)): Hardware watchdog timer & multi-relay power recovery controller for mining rigs.
- **Smart Agriculture Systems (Mushroom, AgriSystem, SmartGardenHub_DUE)**: Micro-climate automation with Arduino Due (ARM Cortex-M3), ESP8266, SHT3x sensors, and RS485.
- **PZEM-004T Industrial PowerMeter**: Opto-isolated AC 220V voltage, current, and active power telemetry monitor.
- **[BlynkMegaRelays](https://github.com/tackelua/BlynkMegaRelays)** *(Public)*: W5100 wired industrial Ethernet controller driving 54 I/O pins with zero latency.
- **[Den_cau_thang](https://github.com/tackelua/Den_cau_thang)** *(Public)*: Bi-directional smart staircase cascading light with smooth PWM dimming transitions.
- **Motorcycle Quick-Shifter**: Microsecond-precision ignition spark cut controller for clutchless racing upshifts.
</details>

<details>
<summary>🛠️ <b>Reverse Engineering, Bot Automation & Fintech Systems (Click to expand)</b></summary>

> Protocol inspection, headless automation, anti-fingerprinting, and algorithmic computer vision.

- **VCB Digibank Banking Suite** ([Demo on YouTube](https://www.youtube.com/@buigiathinh)): Reverse engineering encrypted banking API protocols, AES/RSA payload parsing, and automated OCR CAPTCHA solver. *(Private Core)*
- **[auto-close-chrome-if-door-open](https://github.com/tackelua/auto-close-chrome-if-door-open)** *(Public)*: Physical reed switch sensor integration with OS hooks for automated workspace privacy.
- **[ImageAutoClicker-py](https://github.com/tackelua/ImageAutoClicker-py)** *(Public)*: Computer vision GUI automation using OpenCV multi-scale template matching.
- **Binance USD-M Quantitative Bots**: High-frequency orderbook depth streaming and cross-pair arbitrage modeling.
</details>

<details>
<summary>☁️ <b>Modern Systems, Cloudflare Edge & DevTools (Click to expand)</b></summary>

> High-performance Rust CLI tools, distributed edge platforms, and developer tooling.

- **[portctl](https://github.com/GithSoft/portctl)** *(Public, Rust)*: Local-first port manager, zombie process hunter, and automated Cloudflare Tunnel ingress.
- **Torvin** *(Private Alpha, Active Dev)*: Zero-knowledge secrets vault and token broker for developers & AI agents (preventing token leaks).
- **[WordRadar](https://wordradar.githsoft.com)**: NLP vocabulary frequency analyzer and spaced-repetition flashcard generator.
- **[YouTube Mindmap](https://mindmap.githsoft.com)**: Automated transcript distillation into interactive mindmaps.
- **[SOS Platform](https://sosline.org)**: 100% Serverless Edge humanitarian rescue platform on Cloudflare Pages, Workers, and D1 SQLite.
- **[GithSoft Image Lab](https://imagelab.githsoft.com)**: In-browser GPU image processing with WebGL shaders and on-device neural upscaling.
</details>

---

### 🧬 Engineering Evolution

| Domain & Timeline | Scope & Evolution | Core Competencies | Representative Systems & Credentials |
| :---: | :--- | :--- | :--- |
| **Embedded Leadership & PM**<br/>`2016 – Present` | **Engineering Lead & Project Manager**<br/>Guiding embedded teams (Qt/C++, Embedded Linux), driving technical architecture, sprint lifecycles, and cross-functional delivery. | Embedded architecture, automotive cockpit displays, team mentorship, project governance. | **Active Lead & PM** · **PMP® Practitioner**, **PSM™ Scrum Master** |
| **PM Tooling & Productivity**<br/>`2024 – Present` | **Developer Tooling for Team & PM**<br/>Building custom automation tools, productivity scripts, and AI-assisted workflows engineered specifically to streamline Project Management and maximize team output. | Custom developer tooling, CI/CD automation, AI-assisted team workflows. | **Active PM Multiplier** · Internal Team Tooling |
| **Systems Tooling & Lab**<br/>`Personal Lab (GithSoft)` | **Zero-Daemon DevTools & Edge**<br/>Architecting high-speed developer utilities, local socket management, and edge platforms under [GithSoft](https://githsoft.com). | Systems design, POSIX socket probing, `fd-lock`, Cloudflare Pages/Workers/D1, Docker. | [portctl](https://portctl.pages.dev) (Rust CLI), [WordRadar](https://wordradar.githsoft.com), [YouTube Mindmap](https://mindmap.githsoft.com), [SOS Platform](https://sosline.org) |
| **Protocol & FinTech Systems**<br/>`Core Experience` | **Reverse Engineering & Security**<br/>Inspecting proprietary banking protocols, AES/RSA decryption, OCR CAPTCHA automation, market depth streaming. | Cryptographic payload parsing, headless automation, OpenCV template matching. | VCB Digibank Suite, ImageAutoClicker-py |
| **IoT Hardware Heritage**<br/>`2016 – 2018` | **Industrial Rig Automation**<br/>Bare-metal firmware, physical relay power control, and hardware watchdog timers deployed to 24-rig mining clusters. | Schematics design, hardware watchdog timers, microsecond ignition controllers. | [AutoMiner](https://autominer-archived.githsoft.com) (Archived Heritage), Quick-Shifter, BlynkMegaRelays |

---

### 🛠️ Core Stack & Methodology

* **Core Systems & Embedded**: C++17/20, Qt / QML, Embedded Linux, STM32, Arduino, ESP8266, FreeRTOS, CMake
* **DevTools & Automation**: Python, Shell scripting, POSIX socket probing, ADB automation, AI-assisted workflows
* **Edge & Cloud**: Docker, Cloudflare Pages, Workers, D1 (SQLite at the Edge), KV, Zero Trust Tunnels, CI/CD, PWA (Offline-First)
* **Methodology & Certifications**: PMP® Practitioner · PSM™ (Professional Scrum Master) · Hybrid Agile/Waterfall

---

### 📬 Connect

* **YouTube**: [youtube.com/@buigiathinh](https://www.youtube.com/@buigiathinh) *(Engineering & Project Management)*
* **Studio**: [githsoft.com](https://githsoft.com)
* **Email**: [tackelua@gmail.com](mailto:tackelua@gmail.com)
* **Organizations**: [@tackelua](https://github.com/tackelua) · [@GithSoft](https://github.com/GithSoft) · [@sosline-org](https://github.com/sosline-org)

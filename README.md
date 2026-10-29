<!-- Profile README · github.com/fuuyuki -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,50:6366f1,100:a855f7&height=210&section=header&text=Muhammad%20Fikra%20Adzaky&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=Product%20Development%20Engineer%20%28Electronics%29%20%E2%80%A2%20Tech%20Educator&descAlignY=58&descSize=16&animation=fadeIn" alt="Muhammad Fikra Adzaky" width="100%" />

<a href="https://github.com/fuuyuki">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&pause=1200&color=38BDF8&center=true&vCenter=true&width=700&lines=Embedded+product+development%2C+bench+to+deployment;Teaching+robots+to+listen+%E2%80%94+and+students+to+build;Sensor+%E2%86%92+MQTT+%E2%86%92+REST+%E2%86%92+App;Studying+M.Sc.+Electrical+Engineering+at+UGM" alt="What I do" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=fuuyuki&style=flat-square&color=6366f1&label=profile+views" alt="Profile views" />
<img src="https://img.shields.io/badge/based%20in-Yogyakarta%2C%20Indonesia-6366f1?style=flat-square" alt="Location" />
<img src="https://img.shields.io/badge/open%20to%20work-onsite%20%C2%B7%20hybrid%20%C2%B7%20remote-22c55e?style=flat-square" alt="Open to work" />

</div>

---

## 👋 A little context

I'm an electronics engineer in Yogyakarta, and I like the unglamorous half of the job: making the pieces actually fit together, then writing it down so the next person doesn't have to guess. Most of my work lives where **hardware meets software** — firmware on a bench, a broker in the middle, a clean API in front of it.

These days I split my time between **freelance embedded product development** and **mentoring robotics teams**, while doing a master's at UGM.

## 🧩 What I do

| 💻 Product Development Engineer | 🤖 Robotics Mentor | 🎓 Tech Educator |
| :--- | :--- | :--- |
| I take embedded products from bench prototype to something deployable — firmware, device–software integration, deployment, and the documentation that keeps it maintainable. | I mentor robotics teams from first principles to competition runs: mechanics, electronics, control logic, and the debugging habits that survive a bad match. | I teach across the whole ladder — Scratch and block-based logic with primary-school kids, electronics and embedded C/C++ with older students, ML fundamentals for beginners. |

## 💼 Experience

| When | Role | Organisation |
| :--- | :--- | :--- |
| Jun 2026 – now | Robotics Mentor | CROG International · *freelance* |
| Jun 2025 – now | Product Development Engineer | Protofy Labs · *freelance* |
| Jun 2025 – Jan 2026 | Implementation Engineer | PT Protechno Edukasi Indonesia · *full-time* |
| Jul 2024 – Jun 2025 | Robotics Mentor | Al Irsyad Al Islamiyyah Boarding School · *contract* |
| Mar 2023 – Jun 2025 | Robotics Mentor | Hompimpaa.id · *part-time* |

<sub>At Hompimpaa.id the work was curriculum design as much as teaching; at PT Protechno it was embedded software plus technical training for clients.</sub>

## 🎓 Education & certifications

| Degree | Institution | Years |
| :--- | :--- | :--- |
| Magister Teknik (M.Eng.), Electrical & Electronics Engineering | Universitas Gadjah Mada | 2026 – 2027 · *in progress* |
| Sarjana Teknik (B.Eng.), Electrical & Electronics Engineering · GPA 3.69/4.00 | Universitas Jenderal Soedirman | 2019 – 2023 |

- **Machine Learning Pipelines with Azure ML Studio** — Coursera, 2023
- **Belajar Machine Learning untuk Pemula** — Dicoding, 2023
- Two more on [LinkedIn](https://www.linkedin.com/in/muhammad-fikra-adzaky-9782941b2/details/certifications/).

## ⚙️ How I work

- **Empirical over assumed** — benchmark hardware and firmware under load, stress-test with dummy datasets, ship reproducible builds.
- **Modular troubleshooting** — isolate the layer, verify the assumption, then automate the fix.
- **Docs as a deliverable** — if someone else can't rebuild it from the notes, it isn't finished.

## 🏗️ The shape of an IoT system

```mermaid
flowchart LR
    subgraph E["01 · Edge"]
        direction TB
        S["🔌 Sensors<br/>adherence · environment"] --> M["🧠 ESP32 firmware"]
    end
    subgraph T["02 · Transport"]
        direction TB
        Q["📡 MQTT broker"]
    end
    subgraph V["03 · Service"]
        direction TB
        R["⚙️ REST API"] --> D[("🗄️ Data store")]
    end
    subgraph X["04 · Experience"]
        direction TB
        A["📱 App + dashboard"]
    end

    M --> Q
    Q --> R
    R --> A
    A -. "🔐 signed requests" .-> R
```

<sub>My default blueprint: each stage is independently testable, so a failure at the edge never becomes a mystery in the app.</sub>

## 🔬 Selected work

- **[Smart Adherence Pillbox (SAP)](https://github.com/fuuyuki/sap-fastapi)** — one product split into cooperating layers: [C/C++ firmware](https://github.com/fuuyuki/sap-pillbox) and a [C++ smartwatch](https://github.com/fuuyuki/sap-watch) at the edge, a [Kotlin Android app](https://github.com/fuuyuki/sapp-android) for patients, and a [FastAPI backend](https://github.com/fuuyuki/sap-fastapi) holding it together.
- **[WRO Museum Guide Robot](https://github.com/fuuyuki/wro-wisanggeni)** — Python control stack for the *Marvel* and *Karuna* guide robots we fielded for WRO.
- **[ESP32-CAM note verification](https://github.com/fuuyuki/esp32-cam-fakemoney)** — on-device machine learning telling real banknotes from counterfeits, with no cloud round-trip.
- **[proto-folio](https://github.com/fuuyuki/proto-folio)** — Svelte market and admin app; **[talenta-app](https://github.com/fuuyuki/talenta-app)** and **[siab-dashboard](https://github.com/fuuyuki/siab-dashboard)** round out the web side in TypeScript and Laravel.

## 🧰 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,python,kotlin,svelte,typescript,fastapi,laravel,arduino,raspberrypi,linux,bash,git,vscode&perline=7" alt="Languages and tools" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MQTT-3C5280?style=flat-square&logo=mqtt&logoColor=white" alt="MQTT" />
  <img src="https://img.shields.io/badge/REST%20APIs-005571?style=flat-square&logo=fastapi&logoColor=white" alt="REST APIs" />
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32" />
  <img src="https://img.shields.io/badge/Machine%20Learning-FF6F00?style=flat-square" alt="Machine Learning" />
  <img src="https://img.shields.io/badge/Electronics-1F9E3F?style=flat-square" alt="Electronics" />
  <img src="https://img.shields.io/badge/PCB%20design-1F9E3F?style=flat-square&logo=kicad&logoColor=white" alt="PCB design" />
</p>

## 📈 By the numbers

<sub>Pulled from the public GitHub API on 30 Oct 2026 — repos grouped by primary language, commits by author date on default branches (private work not included, 2026 is year-to-date).</sub>

```text
Repos by primary language    Public commits, by year
─────────────────────────    ───────────────────────────────
Python            ███  3     2022  █                      16
Jupyter Notebook  ██   2     2023  █                       6
C / C++           ██   2     2024  █                       9
JavaScript        ██   2     2025  ██                     44
TypeScript        █    1     2026  ████████████████████  392
Svelte            █    1
Kotlin            █    1
PHP / Blade       █    1
```

<details>
<summary><b>✨ Beyond the code</b></summary>
<br/>

- Building reproducible, modular systems — technical and personal.
- Exploring ethical investing and how wealth circulation touches the real economy.
- Fifteen public repositories of my own, spanning firmware, mobile, backend, and web.
- Currently studying alongside freelancing, which is its own kind of systems problem.

</details>

## 🤝 Let's talk

<p align="center">
  <a href="https://www.linkedin.com/in/muhammad-fikra-adzaky-9782941b2/">
    <img src="https://img.shields.io/badge/LinkedIn-Muhammad%20Fikra%20Adzaky-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://www.instagram.com/fikra_fa">
    <img src="https://img.shields.io/badge/Instagram-@fikra__fa-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
</p>

<p align="center"><i>Always up for a conversation about robots, sensors, or clean deployment.</i></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:a855f7,50:6366f1,100:0ea5e9&height=120&section=footer" alt="" width="100%" />

<!-- Profile README · github.com/fuuyuki -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,50:6366f1,100:a855f7&height=210&section=header&text=Muhammad%20Fikra%20Adzaky&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=Implementation%20Engineer%20%E2%80%A2%20Robotics%20Instructor%20%E2%80%A2%20IoT%20Builder&descAlignY=58&descSize=16&animation=fadeIn" alt="Muhammad Fikra Adzaky" width="100%" />

<a href="https://github.com/fuuyuki">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&pause=1200&color=38BDF8&center=true&vCenter=true&width=700&lines=Translating+business+needs+into+shipped+systems;Teaching+robots+to+listen+%E2%80%94+and+students+to+build;Sensor+%E2%86%92+MQTT+%E2%86%92+REST+%E2%86%92+App;Benchmark+it.+Stress+it.+Document+it." alt="What I do" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=fuuyuki&style=flat-square&color=6366f1&label=profile+views" alt="Profile views" />
<img src="https://img.shields.io/badge/status-building%20%26%20teaching-22c55e?style=flat-square" alt="Status" />
<img src="https://img.shields.io/badge/focus-IoT%20%26%20robotics-0ea5e9?style=flat-square" alt="Focus" />

</div>

---

## 👋 A little context

I'm an implementation engineer who likes the unglamorous half of engineering: making the pieces actually fit together, then writing it down so the next person doesn't have to guess. Most of my work lives where **hardware meets software** — firmware on a bench, a broker in the middle, a clean API in front of it.

## 🧩 What I do

| 💻 Implementation Engineer | 🤖 Robotics Instructor | 📡 IoT Architect |
| :--- | :--- | :--- |
| I turn business requirements into **scalable technical solutions**, then own the integration, deployment, and documentation that keep them working in the real world. | I teach robotics, AI, and embedded systems through **hands-on, scaffolded labs** — small steps, real hardware, immediate feedback. | I design **staged IoT pipelines** (MQTT → REST → app) with security and observability built in, aimed at healthcare and biometric use cases. |

## ⚙️ How I work

- **Empirical over assumed** — benchmark hardware and firmware under load, stress-test with dummy datasets, ship reproducible builds.
- **Modular troubleshooting** — isolate the layer, verify the assumption, then automate the fix.
- **Docs as a deliverable** — if someone else can't rebuild it from the notes, it isn't finished.

## 🏗️ The shape of an IoT system

```mermaid
flowchart LR
    subgraph E["01 · Edge"]
        direction TB
        S["🔌 Sensors<br/>biometric · environment"] --> M["🧠 ESP32 firmware"]
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

## 🧰 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,python,java,arduino,raspberrypi,linux,bash,git,github,vscode&perline=11" alt="Languages and tools" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MQTT-3C5280?style=flat-square&logo=mqtt&logoColor=white" alt="MQTT" />
  <img src="https://img.shields.io/badge/REST%20APIs-005571?style=flat-square&logo=fastapi&logoColor=white" alt="REST APIs" />
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32" />
  <img src="https://img.shields.io/badge/PCB%20design-1F9E3F?style=flat-square&logo=kicad&logoColor=white" alt="PCB design" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Jekyll-CC0000?style=flat-square&logo=jekyll&logoColor=white" alt="Jekyll" />
</p>

## 📈 By the numbers

```text
Language mix                 Contribution trend
──────────────────────       ─────────────────────────────
Python  ████████  40%        2023  █████░░░░░░░░░░░░░░░  120
C++     ███████   35%        2024  █████████████░░░░░░░  300
Java    █████     25%        2025  ████████████████████  450
```

<details>
<summary><b>✨ Beyond the code</b></summary>
<br/>

- Building reproducible, modular systems — technical and personal.
- Exploring ethical investing and how wealth circulation touches the real economy.
- Designing secure IoT platforms with biometric security for healthcare applications.
- 25 public repositories and counting.

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

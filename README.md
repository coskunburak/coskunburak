<h1 align="center">Hi there, I'm Burak Coşkun 👋</h1>

<p align="center">
  <strong>iOS & Mobile Platform Engineer</strong><br>
  <i>Swift · TypeScript · Java/Spring Boot · Flutter · Python/FastAPI</i><br>
  📍 İstanbul, Turkey | 🎓 Sakarya University CS (Class of 2026)
</p>

<p align="center">
  I design and ship full-stack mobile products end-to-end — from custom on-device ML inference pipelines and GPU-accelerated serverless compute to Android kiosk systems running in corporate production environments. I care deeply about explicit architecture boundaries, deterministic system behaviour, observable failure modes, and long-term maintainability.
</p>

<p align="center">
  <a href="https://coskunburak.github.io" target="_blank">
    <img src="https://img.shields.io/badge/View_Interactive_Portfolio-0a0e1a?style=for-the-badge&logo=html5&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/csknburak/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

<hr>

## 🚀 Featured Production Systems

### 1. [MocapExpo](https://github.com/coskunburak/mocap) (⭐ Graduation Thesis)
End-to-end motion capture pipeline. A **React Native** app uploads raw video directly to **S3**, triggering a **Node/Fastify** backend to dispatch a GPU job to **RunPod Serverless**. A Python worker runs **WHAM/SMPL** pose estimation and multi-camera DLT triangulation to produce BVH animation artifacts with strict *no-fake-success* quality gates.

### 2. [Verified AI](https://github.com/coskunburak/verified_ai) (Production Platform)
iOS-first AI mathematics learning platform. **SwiftUI** client backed by a **Java 21 Spring Boot** modular monolith. Converts student math problems, orchestrates provider-neutral LLMs, and independently verifies every AI answer using a deterministic **SymPy (Python)** infrastructure layer. Includes 45+ technical docs and 4 formal ADRs.

### 3. [GlowStudio AI](https://github.com/coskunburak/glowStudioAi) (On-Device ML)
Offline-first **iOS** photo editing app. A custom **PyTorch** face parsing model exported to **Core ML** runs on-device, feeding segmentation masks to custom **Metal** shaders and **Core Image** filters. Built with Clean Architecture, **StoreKit 2** gating, and an automated visual regression test suite.

### 4. [Seyir Kiosk](https://github.com/coskunburak/seyirkiosk) (🟢 Live in Corporate Production)
Enterprise Android kiosk system running on physical fleets. A **React Native (TypeScript)** app using a custom Java Native Module to engage Android Screen Pinning (`startLockTask()`). Overrides the HOME button, embeds a bidirectional WebView bridge, and allows remote config deployment without OTA updates.

### 5. [Block Blast](https://github.com/coskunburak/blockblast) (iOS Game)
Production block puzzle game. Driven by a deterministic, pure-function state reducer `(State, Action) -> State`. Includes 5 game modes, a meta-game economy, **Game Center** leaderboards, **StoreKit 2** IAPs, and a complete **Fastlane + GitHub Actions** CI/CD pipeline.

### 6. [FitGen AI](https://github.com/coskunburak/fitgen-ai) & [TabKnockout](https://github.com/coskunburak/tabknockout)
* **FitGen AI:** Flutter/Dart fitness app with **Gemini**-powered plan generation, Firebase backend, and secure proxying for API keys (zero secrets in binary).
* **TabKnockout:** Cross-platform C# game demonstrating core game logic outside native frameworks.

---

## 🛠 Tech Stack

| Domain | Technologies |
|---|---|
| **Apple Native** | Swift, SwiftUI, UIKit, SpriteKit, Core ML, Metal, Vision, StoreKit 2, SwiftData |
| **Cross-Platform** | TypeScript, React Native, Expo, Flutter, Dart, Bloc |
| **Backend (JVM & Node)** | Java 21, Spring Boot 3, Modular Monolith, Node.js, Fastify, PostgreSQL, Redis |
| **AI & Infra** | PyTorch, WHAM/SMPL, SymPy, Gemini, RunPod Serverless, S3, Docker, Firebase, ADB |

---

## 🏗 Engineering Principles I Follow
1. **AI Output is Untrusted Input:** Independent verification is mandatory (e.g., SymPy checking LLM math).
2. **Deterministic State:** Pure reducers make complex games and logic unit-testable.
3. **No Fake Success:** Fail loudly and explicitly with reason codes.
4. **Architecture is Written Down:** Decisions live in ADRs, not just in code.
5. **Secrets Never in Source:** Always injected via CI, `.env`, or secure backends.

<br>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=coskunburak&show_icons=true&theme=nord" alt="Burak's GitHub Stats" />
</p>

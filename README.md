<div align="center">
  <img src="assets/hero.svg" width="100%" alt="PLAYER 1: Ahmad Hassan, Applied AI Engineer working on autonomous flight systems and edge inference">
  <img src="assets/ticker.svg" width="100%" alt="Applied AI · UAV autonomy · edge inference · computer vision · PX4 · PyTorch · Kotlin">
</div>

> 🕹️ **Player bio:** I build the bridge between heavy models and real hardware: autonomous flight, on-device vision,
> decentralized comms, and the intelligence pipelines that keep them alive when the Wi-Fi doesn't.

## ⚔️ Main Quests

<a href="https://github.com/AhmadHasssan9181/Waffle"><img src="assets/quest-waffle.svg" width="100%" alt="Main Quest 01: W.A.F.F.L.E., Wireless Autonomous Flying Fleet for Life Emergencies"></a>

**🛩️ Avionics:** an Android phone as the companion computer, running flight logic over PX4 and the DJI SDK.
**🧭 Pathing:** a PPO reinforcement-learning agent for obstacle avoidance and route planning.
**🗺️ Ops:** MapLibre vector maps + OpenRouteService and GraphHopper for offline disaster-zone navigation.
<br><sub><i>🚁 <a href="https://github.com/AhmadHasssan9181/Waffle">github.com/AhmadHasssan9181/Waffle</a> • Jetpack Compose & Offline Routing.</i></sub>

<a href="https://github.com/AhmadHasssan9181/PYRO"><img src="assets/quest-pyro.svg" width="100%" alt="Main Quest 02: PYRO, real-time fire segmentation for UAV aerial imagery"></a>

**🧠 Architecture:** MobileNetV3-Small encoder, ASPP bottleneck, 5-stage U-Net decoder with SE attention on the skips.
**🎯 Constraints:** full 384×384 masks from aerial frames, trained on FLAME, built to cope with fire pixels being under 1% of an image.
<br><sub><i>🔥 <a href="https://github.com/AhmadHasssan9181/PYRO">github.com/AhmadHasssan9181/PYRO</a> • PyTorch trained checkpoint included.</i></sub>

<a href="https://github.com/AhmadHasssan9181/MoistMachine"><img src="assets/quest-hydroguard.svg" width="100%" alt="Main Quest 03: HydroGuard / MoistViT, multi-head flood detection for low-power hardware"></a>

**🧬 Model:** custom MoistViT & MobileNet + U-Net multi-head architectures (teacher-student & semi-supervised) adapted on Pakistan flood aerial imagery.
**🌊 Edge exports:** 512×512 and 768×768 checkpoints exported to ONNX and TorchScript Lite (`.ptl`) for low-power field deployment.
<br><sub><i>🧪 <a href="https://github.com/AhmadHasssan9181/MoistMachine">github.com/AhmadHasssan9181/MoistMachine</a> • Vision Transformer flood segmentation.</i></sub>

<a href="https://github.com/AhmadHasssan9181/QuakeSentinel"><img src="assets/quest-quakevit.svg" width="100%" alt="Main Quest 04: QuakeViT / QuakeSentinel, aerial earthquake structural damage triage"></a>

**🏚️ Architecture:** EfficientViT-B2 + Multi-Scale FPN (plus a lightweight MobileNetV4 variant) with a 3-class triage head: *Background*, *Intact* (Green), and *Damaged/Rubble* (Red).
**⚡ Field-ready:** trained on xBD earthquake subsets and validated on unseen UAV disaster surveys; exported to ONNX and `.ptl` (3.5–6.5 MB mobile builds).
<br><sub><i>📉 <a href="https://github.com/AhmadHasssan9181/QuakeSentinel">github.com/AhmadHasssan9181/QuakeSentinel</a> • Real-world earthquake evaluation & models.</i></sub>

<a href="https://orbitweb.tech"><img src="assets/quest-orbit.svg" width="100%" alt="Main Quest 05: Orbit, sovereign Matrix messaging with E2EE and WebRTC"></a>

**🔐 Privacy:** end-to-end encryption, SQLCipher local storage and zero telemetry.
**📞 Calls:** WebRTC audio and video, wire-compatible with Element.
**🧩 Clients:** Android (`orbitx` in Jetpack Compose), Kotlin Multiplatform desktop (`orbit`), and a TypeScript web client (`orbit-web`).
<br><sub><i>🔒 Source is private. Landing page at <a href="https://orbitweb.tech">orbitweb.tech</a>.</i></sub>

<img src="assets/quest-intelhub.svg" width="100%" alt="Main Quest 06: IntelHub, unified OSINT and intelligence fusion platform">

**🕵️ Fusion engine:** React + Vite command palette (`Ctrl+K`), Express proxy, FastAPI orchestration backend, PostgreSQL and Redis/Arq task queues.
**🔎 Recon pipelines:** parallel execution and aggregation across email, username, phone, domain and social intelligence tools (`maigret`, `holehe`, `blackbird`, `phoneinfoga`, `ghunt`, Playwright stealth) plus a companion Kotlin Android app (`osintapp`).
<br><sub><i>🔒 Private suite (`intelhub` · `osintapp` · `osint-lover-ui`).</i></sub>

## 🗺️ Side Quests

| Quest | Objective | Loot |
| :-- | :-- | :-- |
| 🧭 **[Ziggy](https://github.com/AhmadHasssan9181/Ziggy)** | Android exploration guide with Gemini answers, monument data and live routing. | `Kotlin` `Gemini` `ORS` |
| 📷 **[Mml](https://github.com/AhmadHasssan9181/Mml)** | On-device moiré detection straight off the camera feed. | `Kotlin` `PyTorch Mobile` |
| 📚 **[NUML Exam Buddy](https://github.com/AhmadHasssan9181/numl-exam-buddy)** | Crowdsourced study hub with notes, slides and past papers by department. | `Kotlin` `Android` |
| 🚕 **[Lily suite](https://github.com/AhmadHasssan9181/nlillycaptain)** | Flutter ride-hailing stack: captain app, driver app, admin console. | `Dart` `Firebase` `Maps` |
| 🕶️ **[Noobdevs](https://github.com/AhmadHasssan9181/Noobdevs)** | Studio site with a boot sequence, classified dossier and OSINT pipeline views. | `React` `Vite` `CSS` |
| 🎵 **[Tunes](https://github.com/AhmadHasssan9181/tunes)** | Music app that downloads and streams tracks. | `Kotlin` `Android` |
| 💪 **[FitFusion](https://github.com/AhmadHasssan9181/FitFusion)** | Fitness companion with AI rep counting and form feedback. | `Android` `Vision` |
| 🎥 **[UAV Person Dataset](https://github.com/AhmadHasssan9181/Manipal-UAV-Person-Dataset)** | Large-scale aerial person-detection dataset: 33 videos, 13k frames. | `Dataset` `CV` |

## 🎒 Inventory

<img src="assets/inventory.svg" width="100%" alt="Inventory: Python, PyTorch, OpenCV, NumPy, Gemini, PX4, DJI SDK, Android, Kotlin, Flutter, Linux, Git, Docker, Selenium, Unity">

## 🏆 Achievements

<img src="assets/achievements.svg" width="100%" alt="Achievements: First Flight, Data Hoarder, Edge Lord, Ship It">

## 📡 Multiplayer

Source, architecture notes, or a hard problem worth arguing about? My inbox is open. Press start.

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-AhmadHasssan9181-ff3d7f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AhmadHasssan9181)
[![Orbit](https://img.shields.io/badge/Orbit-orbitweb.tech-3d5afe?style=for-the-badge&logo=matrix&logoColor=white)](https://orbitweb.tech)

<img src="assets/footer.svg" width="100%" alt="Continue? Insert coin to collaborate">

</div>

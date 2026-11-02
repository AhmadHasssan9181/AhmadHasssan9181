<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg">
    <img src="assets/hero-dark.svg" width="100%" alt="Ahmad Hassan — Applied AI Engineer, autonomous flight systems and edge inference">
  </picture>
</div>

<div align="center">
  <img src="assets/marquee.svg" width="100%" alt="Applied AI · UAV autonomy · edge inference · computer vision · PX4 · PyTorch · Kotlin">
</div>

> I build the bridge between heavy models and real hardware — autonomous flight, on-device vision,
> and the data pipelines that keep them alive when the Wi-Fi doesn't.

## `01` · Systems in flight

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/waffle.svg">
  <img src="assets/waffle.svg" width="100%" alt="W.A.F.F.L.E. — Wireless Autonomous Flying Fleet for Life Emergencies">
</picture>

**Avionics** — Android phone as the companion computer, running flight logic over PX4 and the DJI SDK.
**Pathing** — a PPO reinforcement-learning agent for obstacle avoidance and route planning.
**Ops** — MapLibre vector maps + OpenRouteService for live disaster-zone monitoring from the ground.
<br><sub><i>Private build — architecture walkthrough available on request.</i></sub>

<a href="https://github.com/AhmadHasssan9181/PYRO"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/pyro.svg">
  <img src="assets/pyro.svg" width="100%" alt="PYRO — real-time fire segmentation for UAV aerial imagery">
</picture></a>

**Architecture** — MobileNetV3-Small encoder, ASPP bottleneck, 5-stage U-Net decoder with SE attention on the skips.
**Constraints** — full 384×384 masks from aerial frames, trained on FLAME, built to survive fire pixels being under 1% of an image.
<br><sub><i>PyTorch · trained checkpoint included.</i></sub>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hydroguard.svg">
  <img src="assets/hydroguard.svg" width="100%" alt="HydroGuard — multi-head flood detection for low-power hardware">
</picture>

**Model** — a custom multi-head network for real-time flood detection and disaster mitigation.
**Why it matters** — accuracy that still holds on low-power hardware, because the places that flood first rarely have a GPU.
<br><sub><i>Research build — details on request.</i></sub>

## `02` · Field notes

| Project | What it does | Stack |
| :-- | :-- | :-- |
| **[Ziggy](https://github.com/AhmadHasssan9181/Ziggy)** | Android exploration guide — Gemini answers, monument data, live routing. | `Kotlin` `Gemini` `ORS` |
| **[Mml](https://github.com/AhmadHasssan9181/Mml)** | On-device moiré detection straight off the camera feed. | `Kotlin` `PyTorch Mobile` |
| **[NUML Exam Buddy](https://github.com/AhmadHasssan9181/numl-exam-buddy)** | Crowdsourced study hub — notes, slides and past papers by department. | `Kotlin` `Android` |
| **[Lily suite](https://github.com/AhmadHasssan9181/nlillycaptain)** | Flutter ride-hailing stack: captain app, driver app, admin console. | `Dart` `Firebase` `Maps` |
| **[Orbit](https://orbitweb.tech)** | Landing + portal for a Matrix-based E2EE communications ecosystem. | `HTML` `CSS` `JS` `Pages` |
| **[Noobdevs](https://github.com/AhmadHasssan9181/Noobdevs)** | Studio site with a boot sequence, classified dossier and OSINT pipeline views. | `React` `Vite` `CSS` |
| **[FitFusion](https://github.com/AhmadHasssan9181/FitFusion)** | Fitness companion with AI rep counting and form feedback. | `Android` `Vision` |
| **[UAV Person Dataset](https://github.com/AhmadHasssan9181/Manipal-UAV-Person-Dataset)** | Large-scale aerial person-detection dataset — 33 videos, 13k frames. | `Dataset` `CV` |

## `03` · Loadout

<table>
<tr>
<td valign="top" width="50%">

**Intelligence**
<br>
![Python](https://img.shields.io/badge/Python-0A0F1B?style=flat-square&logo=python&logoColor=22D3EE)
![PyTorch](https://img.shields.io/badge/PyTorch-0A0F1B?style=flat-square&logo=pytorch&logoColor=FF9F45)
![OpenCV](https://img.shields.io/badge/OpenCV-0A0F1B?style=flat-square&logo=opencv&logoColor=C3D2E6)
![NumPy](https://img.shields.io/badge/NumPy-0A0F1B?style=flat-square&logo=numpy&logoColor=8B5CF6)
![Gemini](https://img.shields.io/badge/Gemini-0A0F1B?style=flat-square&logo=googlegemini&logoColor=8B5CF6)

</td>
<td valign="top" width="50%">

**Flight & hardware**
<br>
![PX4](https://img.shields.io/badge/PX4-0A0F1B?style=flat-square&logo=px4&logoColor=22D3EE)
![DJI](https://img.shields.io/badge/DJI_SDK-0A0F1B?style=flat-square&logo=dji&logoColor=C3D2E6)
![Android](https://img.shields.io/badge/Android-0A0F1B?style=flat-square&logo=android&logoColor=3DDC84)
![Kotlin](https://img.shields.io/badge/Kotlin-0A0F1B?style=flat-square&logo=kotlin&logoColor=8B5CF6)
![Flutter](https://img.shields.io/badge/Flutter-0A0F1B?style=flat-square&logo=flutter&logoColor=38BDF8)

</td>
</tr>
<tr>
<td valign="top">

**Systems & automation**
<br>
![Linux](https://img.shields.io/badge/Linux-0A0F1B?style=flat-square&logo=linux&logoColor=C3D2E6)
![Git](https://img.shields.io/badge/Git-0A0F1B?style=flat-square&logo=git&logoColor=FF9F45)
![Docker](https://img.shields.io/badge/Docker-0A0F1B?style=flat-square&logo=docker&logoColor=38BDF8)
![Selenium](https://img.shields.io/badge/Selenium-0A0F1B?style=flat-square&logo=selenium&logoColor=3DDC84)
![Unity](https://img.shields.io/badge/Unity-0A0F1B?style=flat-square&logo=unity&logoColor=C3D2E6)

</td>
<td valign="top">

**Currently exploring**
<br>
`edge inference` · `multi-agent sims` · `RL for flight` · `dataset pipelines`

</td>
</tr>
</table>

## `04` · Get in touch

Source, architecture notes, or a hard problem worth arguing about — my inbox is open.

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-AhmadHasssan9181-0A0F1B?style=for-the-badge&logo=github&logoColor=22D3EE)](https://github.com/AhmadHasssan9181)
[![Orbit](https://img.shields.io/badge/Orbit-orbitweb.tech-0A0F1B?style=for-the-badge&logo=matrix&logoColor=8B5CF6)](https://orbitweb.tech)

</div>

<div align="center">
  <img src="assets/footer.svg" width="100%" alt="Let's build something that flies.">
</div>

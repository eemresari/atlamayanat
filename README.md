<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F0C29,50:6C63FF,100:302B63&height=220&section=header&text=Emre%20Sar%C4%B1&fontSize=64&fontColor=FFFFFF&animation=fadeIn&fontAlignY=32&desc=AI%20%C2%B7%20Computer%20Vision%20%C2%B7%20Interactive%20Experiences&descSize=18&descAlignY=52" width="100%" alt="header"/>

<a href="https://github.com/atlamayanat">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=620&lines=AI+%26+Computer+Vision+Engineer;Interactive+Exhibit+Developer;Full-Stack+%2B+Embedded+Maker;Unity+Game+Developer" alt="Typing SVG"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/Focus-AI%20%2F%20Computer%20Vision-8B5CF6?style=flat-square&labelColor=0D1117" alt="focus"/>
<img src="https://img.shields.io/badge/%F0%9F%93%8D%20Base-T%C3%BCrkiye-6C63FF?style=flat-square&labelColor=0D1117" alt="location"/>
<img src="https://img.shields.io/badge/Mindset-Product%20Engineering-7C3AED?style=flat-square&labelColor=0D1117" alt="mindset"/>

<br/><br/>

<a href="mailto:isgelistirme.kbm@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact%20Me-4F46E5?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="email"/>
</a>
<a href="https://github.com/atlamayanat">
  <img src="https://img.shields.io/badge/GitHub-atlamayanat-6C63FF?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" alt="github"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=atlamayanat&style=flat-square&color=8B5CF6&label=PROFILE+VIEWS" alt="profile views"/>
<img src="https://img.shields.io/github/followers/atlamayanat?style=flat-square&color=6C63FF&labelColor=0D1117&label=FOLLOWERS" alt="followers"/>
<img src="https://img.shields.io/github/stars/atlamayanat?style=flat-square&color=7C3AED&labelColor=0D1117&label=STARS" alt="stars"/>

</div>

---

## 🧭 About

Engineer building **interactive, AI-powered physical experiences** — science-center exhibits where computer vision, local LLMs and projection-mapped games meet real visitors in real time.

- 🎯 **Computer Vision in production** — real-time hand & gesture tracking installations (MediaPipe, OpenCV), projector–camera homography and lens calibration, multi-player lock-on logic
- 🧠 **Local-first AI** — offline conversational exhibits running 4B-parameter LLMs on constrained VRAM, emotion-driven Turkish TTS pipelines with layered fallbacks
- 📱 **Full-stack & mobile** — WebSocket-driven web games, React Native + Expo apps, Python backends
- 📈 **Applied deep learning** — LSTM time-series forecasting deployed to the edge with TensorFlow Lite
- 🎮 **Game development** — Unity 6 / URP 2D, gameplay systems, tooling with editor automation

**Open to:** collaborations on interactive installations, computer-vision products, and AI-powered experiences.

---

## 🛠️ Tech Stack

<div align="center">

### Languages

<img src="https://skillicons.dev/icons?i=python,cs,cpp,ts,js&theme=dark" alt="languages"/>

### Frontend & Mobile

<img src="https://skillicons.dev/icons?i=react,html,css&theme=dark" alt="frontend"/>

### AI / ML & Computer Vision

<img src="https://skillicons.dev/icons?i=tensorflow,opencv&theme=dark" alt="ai-ml"/>

<br/>

<img src="https://img.shields.io/badge/MediaPipe-8B5CF6?style=flat-square&labelColor=0D1117" alt="mediapipe"/>
<img src="https://img.shields.io/badge/TensorFlow%20Lite-6C63FF?style=flat-square&labelColor=0D1117" alt="tflite"/>
<img src="https://img.shields.io/badge/Ollama-7C3AED?style=flat-square&labelColor=0D1117" alt="ollama"/>
<img src="https://img.shields.io/badge/Whisper-4F46E5?style=flat-square&labelColor=0D1117" alt="whisper"/>
<img src="https://img.shields.io/badge/WebSockets-6366F1?style=flat-square&labelColor=0D1117" alt="websockets"/>

### Game Dev & Embedded

<img src="https://skillicons.dev/icons?i=unity,arduino&theme=dark" alt="gamedev"/>

### Cloud, DevOps & Tooling

<img src="https://skillicons.dev/icons?i=git,github,githubactions,nodejs,vscode&theme=dark" alt="tooling"/>

</div>

---

## 🧠 AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|:---|:---:|:---|
| **Computer Vision** | Production | Real-time hand & gesture tracking (MediaPipe), OpenCV pipelines, closed-loop homography & lens-distortion calibration for projector–camera systems |
| **Local LLMs** | Production | Offline conversational agents on low-VRAM hardware (Ollama · Gemma / Qwen 4B), prompt engineering, config-driven sampling profiles |
| **Deep Learning** | Applied | LSTM time-series forecasting for blood-glucose prediction, Clarke Error Grid evaluation, TFLite edge deployment |
| **Speech & Audio** | Applied | Whisper STT with voice-activity detection, emotion-driven TTS (valence/arousal → prosody) with multi-engine fallback |

</div>

---

## 🚀 Featured Projects

<details>
<summary><b>🤖 AICan — AI Science-Center Exhibit</b></summary>
<br/>

Conversational AI exhibit: visitors type a message, a fully local LLM picks an emotional gesture, and a 96×96 software LED matrix plays the matching animation — no cloud, no external hardware.

| | |
|:---|:---|
| **Stack** | Python · Ollama (Gemma 3 4B) · Tkinter · custom LED-matrix renderer |
| **Scale** | Runs continuously as an unattended kiosk in a science center |
| **Performance** | Fully offline on a 4 GB VRAM laptop GPU — model choice and sampling tuned per hardware profile |
| **Security** | Local-first by design: no visitor data leaves the machine; sessions logged locally |
| **Impact** | Turns abstract "AI" into something visitors can talk to and *see* respond |
| **Repository** | [atlamayanat/AICan](https://github.com/atlamayanat/AICan) |

Built as a single Python process with pluggable gesture/emoji pipelines, session logging and hardware-profile configs (laptop vs. exhibition rig).

</details>

<details>
<summary><b>🖐️ Matematik Avı — Gesture-Controlled Exhibit Game</b></summary>
<br/>

Interactive wall-projection game: a webcam tracks the player's hand, a spotlight follows it across the projected scene, and a fist gesture drops a net to catch the hidden mouse.

| | |
|:---|:---|
| **Stack** | Python (MediaPipe hand tracking) · WebSocket bridge · web/Unity front end |
| **Scale** | Multi-player scenes with active-player lock-on |
| **Performance** | Real-time tracking with 9-point closed-loop homography calibration for accurate hand-to-projection mapping |
| **Security** | Camera frames processed locally in real time — nothing stored or uploaded |
| **Impact** | Kiosk-ready exhibit teaching kids through full-body play |
| **Repository** | [atlamayanat/Matematik_Avi](https://github.com/atlamayanat/Matematik_Avi) |

The detection layer is isolated behind a clean input seam, so the tracking backend (GestureRecognizer → HandLandmarker) can be swapped without touching game logic.

</details>

<details>
<summary><b>🩺 HonyAI — Diabetes Companion & Glucose Prediction</b></summary>
<br/>

Mobile companion for diabetes management, paired with an LSTM model that forecasts blood-glucose trajectories.

| | |
|:---|:---|
| **Stack** | React Native + Expo (TypeScript) · TensorFlow LSTM · TensorFlow Lite |
| **Scale** | App and model developed as separate modules with a gated integration pipeline |
| **Performance** | Model validated with Clarke Error Grid analysis; 4-gate automated test pipeline guards regressions |
| **Security** | On-device inference via TFLite — health data stays on the phone |
| **Impact** | Personal health tooling built end-to-end: data preprocessing → training → mobile deployment |
| **Repository** | [atlamayanat/HonyAI](https://github.com/atlamayanat/HonyAI) |

</details>

<details>
<summary><b>⚔️ ULAK — Unity 2D Action Game</b></summary>
<br/>

Side-scrolling pixel-art action game: a mounted courier rides village to village, fighting monsters and uniting people around a common cause — a short, focused action-narrative experience rooted in Anatolian themes.

| | |
|:---|:---|
| **Stack** | Unity 6 (6000.4.x) · URP 2D · Unity Input System · C# |
| **Scale** | Full gameplay loop: combat, traversal, NPC dialogue, quest thread |
| **Performance** | URP 2D renderer with pixel-perfect presentation |
| **Security** | — |
| **Impact** | First full Unity title; developed with an AI-assisted editor-automation workflow (MCP for Unity) |
| **Repository** | [atlamayanat/ULAK](https://github.com/atlamayanat/ULAK) |

</details>

<details>
<summary><b>💥 ELEMENT-BLAST — Extensible Turn-Based Combat Engine</b></summary>
<br/>

3v3 turn-based elemental combat mini-engine: four elements, seven reaction rules, character abilities and enemy AI — all structured around software design patterns for clean extensibility.

| | |
|:---|:---|
| **Stack** | Python · GoF design patterns · GitHub Actions CI |
| **Scale** | 4 elements · 7 elemental reactions · 4 abilities · pluggable enemy AI |
| **Performance** | Deterministic rule engine with automated test coverage in CI |
| **Security** | — |
| **Impact** | Demonstrates pattern-driven architecture evolved over three project phases |
| **Repository** | [atlamayanat/ELEMENT-BLAST](https://github.com/atlamayanat/ELEMENT-BLAST) |

</details>

---

## 📊 GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=atlamayanat&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=C9D1D9&rank_icon=github" alt="stats"/>
<img height="170" src="https://streak-stats.demolab.com?user=atlamayanat&hide_border=true&background=0D1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA&currStreakNum=C9D1D9&sideNums=C9D1D9&sideLabels=8B5CF6&dates=6E7681&stroke=30363D" alt="streak"/>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=atlamayanat&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9" alt="top languages"/>

</div>

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=atlamayanat&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" alt="trophies"/>

</div>

---

## 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=atlamayanat&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=FFFFFF&area=true&hide_border=true" alt="activity graph" width="95%"/>

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atlamayanat/atlamayanat/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/atlamayanat/atlamayanat/output/github-contribution-grid-snake.svg"/>
  <img alt="contribution snake" src="https://raw.githubusercontent.com/atlamayanat/atlamayanat/output/github-contribution-grid-snake.svg"/>
</picture>

</div>

---

## 🎯 Current Focus

```yaml
learning:   [Unity game development, projector-camera calibration at scale]
building:   [AI-powered science-center exhibits, gesture-controlled games]
exploring:  [local LLMs on low-VRAM hardware, emotion-driven Turkish TTS]
open_to:    [interactive installation collaborations, AI/CV product work]
```

---

## 🤝 Connect

<div align="center">

<a href="mailto:isgelistirme.kbm@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-isgelistirme.kbm-4F46E5?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="gmail"/>
</a>
<a href="https://github.com/atlamayanat">
  <img src="https://img.shields.io/badge/GitHub-atlamayanat-6C63FF?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" alt="github"/>
</a>

</div>

---

<div align="center">

*Build things people can touch — then make them intelligent.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:302B63,50:6C63FF,100:0F0C29&height=140&section=footer" width="100%" alt="footer"/>

</div>

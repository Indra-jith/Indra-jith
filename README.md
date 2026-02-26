<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3500&pause=1200&color=00D9FF&center=true&vCenter=true&multiline=true&width=700&height=80&lines=Building+Intelligent+Systems+from+First+Principles;AI+Architecture+·+Reliability+·+Autonomous+Agents)](https://git.io/typing-svg)

</div>

<div align="center">

![divider](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

</div>

## `> whoami`

4th-year Computer Science student with a minor in Machine Learning and a 9+ CGPA — focused on building AI systems that hold up under real-world conditions. My work sits at the intersection of **perception pipelines**, **LLM orchestration**, and **reliability-aware inference**. I think in terms of failure modes, state machines, and trust propagation — not just model accuracy. Currently targeting MS in ML and next-generation AI systems roles where correctness and fault-tolerance matter as much as raw capability.

---

## `> domains`

```
├── AI Systems Architecture        — perception pipelines, safety state machines, trust modeling
├── ML Engineering                 — confidence calibration, anomaly scoring, temporal decay models
├── Real-Time Computer Vision      — frame-level analysis, gesture recognition, 30Hz inference
├── LLM Orchestration              — multi-stage prompt pipelines, failover routing, quality scoring
└── Backend & Cloud Infrastructure — FastAPI, serverless workers, WebSocket telemetry, async systems
```

---

## `> tech_stack`

**AI / ML**

![Python](https://img.shields.io/badge/Python-0a0a0a?style=flat-square&logo=python&logoColor=00D9FF)
![PyTorch](https://img.shields.io/badge/PyTorch-0a0a0a?style=flat-square&logo=pytorch&logoColor=00D9FF)
![OpenCV](https://img.shields.io/badge/OpenCV-0a0a0a?style=flat-square&logo=opencv&logoColor=00D9FF)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0a0a0a?style=flat-square&logo=google&logoColor=00D9FF)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0a0a0a?style=flat-square&logo=scikit-learn&logoColor=00D9FF)
![Stable Diffusion](https://img.shields.io/badge/Stable_Diffusion-0a0a0a?style=flat-square&logo=stability-ai&logoColor=00D9FF)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-0a0a0a?style=flat-square&logo=fastapi&logoColor=00D9FF)
![TypeScript](https://img.shields.io/badge/TypeScript-0a0a0a?style=flat-square&logo=typescript&logoColor=00D9FF)
![Java](https://img.shields.io/badge/Java-0a0a0a?style=flat-square&logo=openjdk&logoColor=00D9FF)
![WebSockets](https://img.shields.io/badge/WebSockets-0a0a0a?style=flat-square&logo=socket.io&logoColor=00D9FF)
![REST](https://img.shields.io/badge/REST_APIs-0a0a0a?style=flat-square&logo=fastapi&logoColor=00D9FF)

**Cloud & Infra**

![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-0a0a0a?style=flat-square&logo=cloudflare&logoColor=00D9FF)
![Render](https://img.shields.io/badge/Render-0a0a0a?style=flat-square&logo=render&logoColor=00D9FF)
![Docker](https://img.shields.io/badge/Docker-0a0a0a?style=flat-square&logo=docker&logoColor=00D9FF)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0a0a0a?style=flat-square&logo=githubactions&logoColor=00D9FF)

**Systems / Robotics**

![ROS](https://img.shields.io/badge/ROS-0a0a0a?style=flat-square&logo=ros&logoColor=00D9FF)
![Linux](https://img.shields.io/badge/Linux-0a0a0a?style=flat-square&logo=linux&logoColor=00D9FF)
![C++](https://img.shields.io/badge/C++-0a0a0a?style=flat-square&logo=cplusplus&logoColor=00D9FF)

---

## `> projects --featured`

<details open>
<summary><b>[ 01 ] &nbsp; Failure-Aware Vision — ML Perception Engine</b></summary>

<br>

> A production-grade perception reliability system that continuously scores incoming video frames for corruption, models confidence over time, and enforces deterministic safety gating before resuming autonomous operation.

- **Frame-level anomaly scoring at 30Hz** across 5 corruption types: blur, brightness shift, entropy drop, freeze detection — with asymmetric temporal decay for continuous confidence modeling
- **Trust-based safety state machine** with deterministic policy gating — achieved zero false-safe resumptions across all 5 simulated corruption scenarios
- Refactored from ROS prototype to **FastAPI + WebSocket deployment** on Render; includes live telemetry streaming and CSV diagnostics export

`FastAPI` `ROS` `OpenCV` `WebSockets` `Python`

[![Repo](https://img.shields.io/badge/GitHub-Repo-0a0a0a?style=flat-square&logo=github&logoColor=00D9FF)](https://github.com/Indra-jith/failure-aware-vision)
[![Live Demo](https://img.shields.io/badge/Live-Demo-0a0a0a?style=flat-square&logo=render&logoColor=00D9FF)](https://failure-aware-vision.onrender.com/)

</details>

---

<details open>
<summary><b>[ 02 ] &nbsp; Intentra — AI Prompt Optimization Platform</b></summary>

<br>

> A multi-stage LLM orchestration platform that transforms raw prompts through a quality scoring pipeline, routes intelligently between model providers, and maintains sub-100ms latency at 99.9% uptime via quota-aware load balancing.

- **67% improvement in LLM output reliability** through multi-stage prompt transformation and automated quality scoring
- **Automatic failover** between Gemini 1.5 and Groq Llama 3.1 with quota-aware load balancing — 99.9% uptime, <100ms median latency
- Serverless architecture on **Cloudflare Workers** with session tracking and request-level rate limiting

`TypeScript` `LLM Orchestration` `Cloudflare Workers` `Gemini` `Llama 3.1`

[![Repo](https://img.shields.io/badge/GitHub-Repo-0a0a0a?style=flat-square&logo=github&logoColor=00D9FF)](https://github.com/Indra-jith/Intentra)
[![Live Demo](https://img.shields.io/badge/Live-Demo-0a0a0a?style=flat-square&logo=cloudflare&logoColor=00D9FF)](https://promptforge-8tb.pages.dev/)

</details>

---

<details open>
<summary><b>[ 03 ] &nbsp; Gesture-Controlled Human-Machine Interface</b></summary>

<br>

> A real-time gesture recognition system with Kalman-filtered landmark tracking, achieving high-accuracy control across 8 gesture classes — designed for modular deployment in HMI and robotics contexts.

- **95% classification accuracy** across 8 gesture classes at 30 FPS using MediaPipe + OpenCV; Kalman filtering reduced false positives by **34%**
- Integrated **Stable Diffusion API** with <2s inference latency, handling 100+ image generation cycles in testing
- Modular gesture-to-action mapping layer designed for drop-in deployment in **robotic control pipelines**

`Python` `OpenCV` `MediaPipe` `Stable Diffusion` `Kalman Filtering`

[![Repo](https://img.shields.io/badge/GitHub-Repo-0a0a0a?style=flat-square&logo=github&logoColor=00D9FF)](https://github.com/Indra-jith/Gesture-Control-System)

</details>

---

## `> currently_building`

```python
active_research = {
    "autonomous_agents"  : "Designing evaluation frameworks for multi-step agent reliability",
    "agent_evals"        : "Benchmarking decision consistency and failure recovery in LLM agents",
    "ml_infra"           : "Scalable inference pipelines with fault-tolerance and observability",
    "reliability_systems": "Confidence-calibrated AI with graceful degradation under distribution shift"
}
```

---

## `> github --stats`

<div align="center">

<!-- 
  STATS CARDS: Replace YOUR_GITHUB_USERNAME below with your exact GitHub username (case-sensitive).
  These cards are served by a public Vercel deployment of github-readme-stats.
  If cards still fail, self-host: https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own
-->

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Indra-jith&show_icons=true&theme=github_dark&bg_color=0d1117&border_color=00D9FF&title_color=00D9FF&icon_color=00D9FF&text_color=c9d1d9&count_private=true&include_all_commits=true&rank_icon=github&hide_border=false" />
&nbsp;&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Indra-jith&layout=compact&theme=github_dark&bg_color=0d1117&border_color=00D9FF&title_color=00D9FF&text_color=c9d1d9&langs_count=6&hide_border=false&exclude_repo=github-readme-stats" />

</div>

<br>

<div align="center">

<!-- Streak stats — reliable, no self-hosting needed -->
<img src="https://streak-stats.demolab.com?user=Indra-jith&theme=dark&background=0d1117&border=00D9FF&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF&sideLabels=c9d1d9&dates=8b949e&hide_border=false" width="55%" />

</div>

<br>

<div align="center">

<!-- 
  SNAKE ANIMATION: Requires a one-time GitHub Actions setup in your profile repo (Indra-jith/Indra-jith).
  Setup steps (takes ~2 minutes):
    1. In your profile repo, create file: .github/workflows/snake.yml  (see instructions below)
    2. Run the workflow manually once from the Actions tab
    3. The SVG will appear at the path below automatically on every push thereafter

  ── snake.yml content ──────────────────────────────────────────────────────
  name: Generate Snake
  on:
    schedule: [{ cron: "0 0 * * *" }]
    workflow_dispatch:
  jobs:
    generate:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk/svg-only@v3
          with:
            github_user_name: Indra-jith
            outputs: |
              dist/github-contribution-grid-snake.svg
              dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        - uses: crazy-max/ghaction-github-pages@v3
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  ────────────────────────────────────────────────────────────────────────────
-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Indra-jith/Indra-jith/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Indra-jith/Indra-jith/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/Indra-jith/Indra-jith/output/github-contribution-grid-snake-dark.svg" width="90%" />
</picture>

</div>

---

## `> contact`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0a0a0a?style=for-the-badge&logo=linkedin&logoColor=00D9FF)](https://linkedin.com/in/indra-jith)
&nbsp;
[![Email](https://img.shields.io/badge/Email-Reach_Out-0a0a0a?style=for-the-badge&logo=gmail&logoColor=00D9FF)](mailto:indrajith.dev@gmail.com)

</div>

---

<div align="center">

<sub><sup>
Systems that fail gracefully are built by engineers who think carefully about failure.<br>
<code>// architecting the next layer</code>
</sup></sub>

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1a1a,100:2b1a10&height=90&section=header&text=awais%40devmind%3A~%24&fontSize=34&fontColor=FFB347&fontAlign=18&fontAlignY=55&animation=fadeIn" width="100%" alt="Header" />

<a href="https://my-portfolio-six-tan-45.vercel.app/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2800&pause=1000&color=FFB347&background=00000000&center=true&vCenter=true&width=760&lines=%24+whoami+%E2%86%92+Muhammad+Awais+Afzal;%24+role+%E2%86%92+AI%2FML+Engineer;%24+building+%E2%86%92+DevMind%2C+an+autonomous+AI+IDE;%24+status+%E2%86%92+open_to_work+%3D+True" alt="Typing" />
</a>

<br>

[![Portfolio](https://img.shields.io/badge/portfolio-FF7A18?style=flat-square&logo=vercel&logoColor=white)](https://my-portfolio-six-tan-45.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/linkedin-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/m-awais-097a39306)
[![GitHub](https://img.shields.io/badge/github-E4405F?style=flat-square&logo=github&logoColor=white)](https://github.com/M-Awais-11)
![Open to work](https://img.shields.io/badge/open_to_work-FFB347?style=flat-square)
![Remote](https://img.shields.io/badge/remote-global-FF7A18?style=flat-square)
![Views](https://komarev.com/ghpvc/?username=M-Awais-11&color=FF7A18&style=flat-square&label=views)

</div>

&nbsp;

### `$ whoami`

```python
class Engineer:
    name       = "Muhammad Awais Afzal"
    education  = "BS Computer Science @ GCUF, Faisalabad"
    location   = "Faisalabad, Pakistan 🇵🇰  (open to global remote)"
    flagship   = "DevMind — autonomous AI-driven IDE & workflow orchestrator"
    focus      = ["Agentic Workflows", "Multimodal AI", "Production Backends", "LLM Tooling"]
    philosophy = "Ship models, not notebooks."
    seeking    = "High-impact AI/ML & Python engineering roles"
```

> *"Models are easy to train. Systems are hard to ship. I like the hard part."*

&nbsp;

### `$ cat now.md`

| | |
|:--|:--|
| 🔭 **building** | DevMind — AST-validated edits, self-debugging loops, multi-agent orchestration |
| 🌱 **exploring** | Tool-calling reliability in LLM agents · LLM evaluation & guardrails |
| ⚙️ **optimizing** | YOLOv8 latency (ONNX / TensorRT) · async FastAPI pipelines under load |
| 🤝 **seeking** | AI/ML Engineer · Python backend · LLM application work |

&nbsp;

### `$ ls ./stack`

```text
ai/        pytorch  tensorflow  opencv  yolov8  scikit-learn  pandas  numpy
llm/       openai  langchain  huggingface  onnx
backend/   fastapi  django-rest  postgresql  mysql  redis  nginx
devops/    docker  git  github-actions  linux
tools/     vscode  jupyter  streamlit  postman
```

<div align="center">
<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv,fastapi,django,postgres,docker,redis,linux,git&theme=dark" />
</div>

<details>
<summary><code>$ ./proficiency --show</code></summary>
<br>

```text
CORE      ████████████  Python · PyTorch · FastAPI · OpenCV · YOLOv8 · Pandas · NumPy · Git
WORKING   ████████░░░░  Django REST · PostgreSQL · Docker · Scikit-Learn · Streamlit · LLM APIs
LEARNING  ████░░░░░░░░  LangChain agents · ONNX/TensorRT · Redis · CI/CD · MLOps · eval tooling
```

</details>

&nbsp;

### `$ ./projects --list`

| # | Project | What it does | Stack |
|:-:|:--|:--|:--|
| 01 | **🧠 DevMind** | Reads file trees, plans workflows, edits code with AST validation, self-debugs via feedback loops | `Python` `Agents` `AST` `LLMs` |
| 02 | **🐄 Clinipaws** | Livestock health AI: symptom classifier + CV lesion diagnosis + tele-vet reports | `PyTorch` `FastAPI` `Streamlit` |
| 03 | **📊 DataPilot AI** | Ingests raw data, runs auto-EDA, hypothesizes correlations, generates executable charts | `Pandas` `Matplotlib` `OpenAI API` |
| 04 | **👁️ Pure-Sight** | High-FPS YOLOv8 tracking with bounding alerts and live inference telemetry | `YOLOv8` `OpenCV` `Streamlit` |

👉 [Live demos](https://my-portfolio-six-tan-45.vercel.app/) · [All repositories](https://github.com/M-Awais-11?tab=repositories)

&nbsp;

### `$ tree ./architecture`

<details open>
<summary><b>DevMind — agent loop</b></summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#2b1a10','primaryTextColor':'#FFE8CC','primaryBorderColor':'#FF7A18','lineColor':'#FFB347'}}}%%
flowchart LR
    A([User Task]) --> B[Read File Tree]
    B --> C[LLM Planner]
    C --> D[Generate Patch]
    D --> E{AST Valid?}
    E -- No --> F[Self-Debug]
    F --> C
    E -- Yes --> G[Run Tests]
    G -- Fail --> F
    G -- Pass --> H([Apply Changes])
```

</details>

<details>
<summary><b>Pure-Sight — vision pipeline</b></summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#2b1a10','primaryTextColor':'#FFE8CC','primaryBorderColor':'#FF7A18','lineColor':'#FFB347'}}}%%
flowchart LR
    A[Camera Stream] --> B[Frame Capture]
    B --> C[Pre-process]
    C --> D[YOLOv8]
    D --> E[Tracking]
    E --> F[Alerts]
    E --> G[Telemetry]
    F --> H[Dashboard]
    G --> H
```

</details>

<details>
<summary><b>Clinipaws — diagnosis flow</b></summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#2b1a10','primaryTextColor':'#FFE8CC','primaryBorderColor':'#FF7A18','lineColor':'#FFB347'}}}%%
flowchart TB
    U([Farmer / Vet]) --> S[Symptoms]
    U --> I[Lesion Image]
    S --> C1[Symptom Classifier]
    I --> C2[CV Model]
    C1 --> M[Result Fusion]
    C2 --> M
    M --> R[Diagnosis Report]
    R --> T[Tele-vet Review]
```

</details>

<details>
<summary><b>DataPilot AI — analysis loop</b></summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#2b1a10','primaryTextColor':'#FFE8CC','primaryBorderColor':'#FF7A18','lineColor':'#FFB347'}}}%%
flowchart LR
    A[Raw Dataset] --> B[Auto EDA]
    B --> C[Hypotheses]
    C --> D[Generate Code]
    D --> E{Success?}
    E -- No --> F[Fix Code]
    F --> D
    E -- Yes --> G[Insights & Charts]
```

</details>

&nbsp;

### `$ cat principles.txt`

```text
1. Evaluate before scaling      → every agent/model gets a benchmark first
2. Never trust raw LLM output   → AST checks, schema validation, guardrails
3. Latency is a feature         → async I/O, batching, caching, optimized inference
4. Reproducible by default      → Docker, pinned deps, environment parity
5. Observable systems           → logs, telemetry, traces for debuggable failures
```

&nbsp;

### `$ git log --stats`

<div align="center">

<img src="https://raw.githubusercontent.com/M-Awais-11/M-Awais-11/main/profile-summary-card-output/gruvbox/0-profile-details.svg" alt="Profile details" />

<img src="https://raw.githubusercontent.com/M-Awais-11/M-Awais-11/main/profile-summary-card-output/gruvbox/3-stats.svg" alt="Stats" width="49%" />
<img src="https://raw.githubusercontent.com/M-Awais-11/M-Awais-11/main/profile-summary-card-output/gruvbox/2-most-commit-language.svg" alt="Top languages" width="49%" />

<img src="https://streak-stats.demolab.com?user=M-Awais-11&theme=gruvbox&hide_border=true&fire=FF7A18&ring=FFB347&currStreakNum=FFB347&background=282828" alt="Streak" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/M-Awais-11/M-Awais-11/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/M-Awais-11/M-Awais-11/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/M-Awais-11/M-Awais-11/output/github-snake.svg" />
</picture>

</div>

&nbsp;

### `$ cat roadmap-2026.md`

- [x] Ship DevMind v1 with AST-validated edits
- [x] Deploy Clinipaws CV pipeline
- [ ] Multi-agent orchestration inside DevMind
- [ ] ONNX / TensorRT optimization for Pure-Sight
- [ ] Open-source an LLM evaluation toolkit
- [ ] Publish technical deep-dives on agent reliability

&nbsp;

### `$ ./hire --me`

| 🧠 AI Agents & LLM Apps | 👁️ Computer Vision | ⚡ Python Backends |
|:--|:--|:--|
| Agentic workflows, RAG, tool-calling, code-synthesis tools | Detection, tracking, real-time inference, deployment | FastAPI / Django APIs, PostgreSQL, Docker, async services |

<details>
<summary><code>$ cat faq.md</code></summary>
<br>

**Open to remote?** Yes — globally remote, flexible with time zones.
**Best-fit roles?** AI/ML Engineer · LLM Applications Engineer · Python Backend Engineer · Computer Vision Engineer.
**Fastest way to reach me?** LinkedIn message or the portfolio contact section.

</details>

&nbsp;

<div align="center">

```text
$ echo "Let's build something."
```

[![Portfolio](https://img.shields.io/badge/visit_portfolio-FF7A18?style=for-the-badge&logo=google-chrome&logoColor=white)](https://my-portfolio-six-tan-45.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/connect_on_linkedin-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/m-awais-097a39306)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2b1a10,100:1a1a1a&height=50&section=footer" width="100%" alt="Footer" />

</div>

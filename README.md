<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=0,3,6,10&height=230&section=header&text=Hi%2C%20I'm%20Awais&fontSize=58&fontColor=1e1e2e&fontAlignY=42&desc=I%20build%20AI%20that%20actually%20ships.&descSize=20&descColor=313244&descAlignY=64" width="100%" alt="Header" />

<h3>
  AI/ML Engineer &nbsp;·&nbsp; Agents &nbsp;·&nbsp; Computer Vision &nbsp;·&nbsp; Python Backends
</h3>

<a href="https://my-portfolio-six-tan-45.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-cba6f7?style=for-the-badge&logo=vercel&logoColor=1e1e2e" /></a>
<a href="https://www.linkedin.com/in/m-awais-097a39306"><img src="https://img.shields.io/badge/LinkedIn-89b4fa?style=for-the-badge&logo=linkedin&logoColor=1e1e2e" /></a>
<a href="https://github.com/M-Awais-11"><img src="https://img.shields.io/badge/GitHub-f5c2e7?style=for-the-badge&logo=github&logoColor=1e1e2e" /></a>
<img src="https://img.shields.io/badge/Open_to_work-a6e3a1?style=for-the-badge&logoColor=1e1e2e" />

</div>

<br>

## ✦ A little about me

I'm **Muhammad Awais Afzal**, a Computer Science student at **GCUF Faisalabad**, based in Pakistan and open to **remote work anywhere**.

I'm happiest in the gap between a working notebook and a working product. My flagship project, **DevMind**, is an autonomous AI IDE that plans, edits and debugs code on its own. Around it I build computer vision systems and async Python backends that hold up under load.

> *Models are easy to train. Systems are hard to ship. I like the hard part.*

<br>

## ✦ What I do

<table>
<tr>
<td width="33%" valign="top" align="center">

### 🧠
**AI Agents & LLM Apps**

Agentic workflows, RAG, tool-calling and code-synthesis tools, with guardrails around every model call.

</td>
<td width="33%" valign="top" align="center">

### 👁️
**Computer Vision**

Detection, tracking and real-time inference with YOLOv8 and OpenCV, built for low latency.

</td>
<td width="33%" valign="top" align="center">

### ⚡
**Python Backends**

FastAPI and Django REST services, PostgreSQL and Docker, designed to be async and observable.

</td>
</tr>
</table>

<br>

## ✦ Selected work

<table>
<tr>
<td width="50%" valign="top">

#### 🧠 DevMind
*Autonomous AI IDE*

**Problem:** LLM code edits break things silently.
**Approach:** read the file tree, plan the task, validate every patch with an AST check, then self-debug in a loop.

<img src="https://img.shields.io/badge/Python-cba6f7?style=flat-square" />
<img src="https://img.shields.io/badge/Agents-f5c2e7?style=flat-square" />
<img src="https://img.shields.io/badge/AST-89b4fa?style=flat-square" />
<img src="https://img.shields.io/badge/LLMs-a6e3a1?style=flat-square" />

</td>
<td width="50%" valign="top">

#### 🐄 Clinipaws
*Livestock health AI*

**Problem:** farmers often can't reach a vet quickly.
**Approach:** combine a symptom classifier with a custom CV model for lesions, then hand the report to a tele-vet.

<img src="https://img.shields.io/badge/PyTorch-fab387?style=flat-square" />
<img src="https://img.shields.io/badge/FastAPI-a6e3a1?style=flat-square" />
<img src="https://img.shields.io/badge/Streamlit-f38ba8?style=flat-square" />
<img src="https://img.shields.io/badge/CV-89b4fa?style=flat-square" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📊 DataPilot AI
*Autonomous data-science agent*

**Problem:** EDA is repetitive and slow.
**Approach:** ingest raw data, run automated EDA, hypothesize correlations and generate executable charts.

<img src="https://img.shields.io/badge/Pandas-89b4fa?style=flat-square" />
<img src="https://img.shields.io/badge/Matplotlib-f9e2af?style=flat-square" />
<img src="https://img.shields.io/badge/OpenAI_API-cba6f7?style=flat-square" />

</td>
<td width="50%" valign="top">

#### 👁️ Pure-Sight
*High-FPS vision engine*

**Problem:** real-time tracking needs tight latency.
**Approach:** custom YOLOv8 pipeline with multi-class tracking, bounding alerts and live inference telemetry.

<img src="https://img.shields.io/badge/YOLOv8-f5c2e7?style=flat-square" />
<img src="https://img.shields.io/badge/OpenCV-a6e3a1?style=flat-square" />
<img src="https://img.shields.io/badge/Streamlit-f38ba8?style=flat-square" />

</td>
</tr>
</table>

<p align="center"><i>More demos and code → <a href="https://my-portfolio-six-tan-45.vercel.app/">portfolio</a> · <a href="https://github.com/M-Awais-11?tab=repositories">all repositories</a></i></p>

<details>
<summary><b>How DevMind works (diagram)</b></summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#313244','primaryTextColor':'#cdd6f4','primaryBorderColor':'#cba6f7','lineColor':'#89b4fa','secondaryColor':'#45475a','tertiaryColor':'#1e1e2e'}}}%%
flowchart LR
    A([Task]) --> B[Read file tree]
    B --> C[Plan]
    C --> D[Generate patch]
    D --> E{AST valid?}
    E -- no --> F[Self-debug]
    F --> C
    E -- yes --> G[Run tests]
    G -- fail --> F
    G -- pass --> H([Apply])
```

</details>

<br>

## ✦ Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv,fastapi,django,postgres,mysql,redis,docker,nginx,linux,git,githubactions,streamlit,jupyter&theme=dark&perline=8" />

<br><br>

<img src="https://img.shields.io/badge/scikit--learn-fab387?style=flat-square&logo=scikitlearn&logoColor=1e1e2e" />
<img src="https://img.shields.io/badge/Pandas-89b4fa?style=flat-square&logo=pandas&logoColor=1e1e2e" />
<img src="https://img.shields.io/badge/NumPy-74c7ec?style=flat-square&logo=numpy&logoColor=1e1e2e" />
<img src="https://img.shields.io/badge/HuggingFace-f9e2af?style=flat-square&logo=huggingface&logoColor=1e1e2e" />
<img src="https://img.shields.io/badge/OpenAI-a6e3a1?style=flat-square&logo=openai&logoColor=1e1e2e" />
<img src="https://img.shields.io/badge/LangChain-94e2d5?style=flat-square&logo=langchain&logoColor=1e1e2e" />
<img src="https://img.shields.io/badge/ONNX-cba6f7?style=flat-square&logo=onnx&logoColor=1e1e2e" />
<img src="https://img.shields.io/badge/YOLOv8-f5c2e7?style=flat-square&logo=ultralytics&logoColor=1e1e2e" />

</div>

<br>

## ✦ How I work

<table>
<tr>
<td width="20%" align="center"><b>📏<br>Measure</b><br><sub>benchmark before scaling</sub></td>
<td width="20%" align="center"><b>🛡️<br>Verify</b><br><sub>never trust raw LLM output</sub></td>
<td width="20%" align="center"><b>⚡<br>Speed up</b><br><sub>latency is a feature</sub></td>
<td width="20%" align="center"><b>🐳<br>Reproduce</b><br><sub>Docker and pinned deps</sub></td>
<td width="20%" align="center"><b>🔭<br>Observe</b><br><sub>logs, telemetry, traces</sub></td>
</tr>
</table>

<br>

## ✦ Right now

- 🔭 **Building** multi-agent orchestration inside DevMind
- 🌱 **Exploring** tool-calling reliability and LLM evaluation
- ⚙️ **Optimizing** YOLOv8 latency with ONNX / TensorRT
- 🤝 **Looking for** AI/ML, LLM application and Python backend roles

<details>
<summary><b>2026 roadmap</b></summary>
<br>

- [x] Ship DevMind v1 with AST-validated edits
- [x] Deploy Clinipaws CV pipeline
- [ ] Multi-agent orchestration inside DevMind
- [ ] ONNX / TensorRT optimization for Pure-Sight
- [ ] Open-source an LLM evaluation toolkit
- [ ] Publish technical deep-dives on agent reliability

</details>

<br>

## ✦ GitHub at a glance

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=M-Awais-11&show_icons=true&theme=catppuccin_mocha&hide_border=true&rank_icon=github" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=M-Awais-11&layout=compact&theme=catppuccin_mocha&hide_border=true" />

<br>

<img src="https://streak-stats.demolab.com?user=M-Awais-11&theme=catppuccin-mocha&hide_border=true&background=1e1e2e&ring=cba6f7&fire=f38ba8&currStreakNum=cdd6f4&sideNums=cdd6f4&currStreakLabel=f5c2e7&sideLabels=bac2de&dates=a6adc8" />

</div>

<br>

## ✦ Say hello

Open to **AI/ML Engineer**, **LLM Applications**, **Python Backend** and **Computer Vision** roles, fully remote and flexible with time zones. The fastest way to reach me is a LinkedIn message.

<div align="center">

<a href="https://www.linkedin.com/in/m-awais-097a39306"><img src="https://img.shields.io/badge/Message_me_on_LinkedIn-89b4fa?style=for-the-badge&logo=linkedin&logoColor=1e1e2e" /></a>
<a href="https://my-portfolio-six-tan-45.vercel.app/"><img src="https://img.shields.io/badge/See_my_portfolio-cba6f7?style=for-the-badge&logo=vercel&logoColor=1e1e2e" /></a>

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=10,6,3,0&height=90&section=footer" width="100%" alt="Footer" />

</div>

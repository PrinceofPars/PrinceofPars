<!-- ========================================================================= -->
<!--                   PRINCE KOSHTHI | GITHUB PROFILE README                  -->
<!-- ========================================================================= -->

<div align="center">

  <!-- Dynamic Typing SVG Header -->
  <a href="https://princekoshthi.vercel.app/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&duration=3200&pause=1000&color=6366F1&center=true&vCenter=true&multiline=false&width=650&height=50&lines=Hi%2C+I'm+Prince+Koshthi+%F0%9F%91%8B;AI+%2F+ML+%26+Systems+Engineer;Accelerating+Inference+%7C+Edge+Vision;\Building+High-Performance+AI+Infrastructure" alt="Prince Koshthi - Dynamic Typing Headline" />
  </a>

  <p align="center">
    <strong>Computer Science Engineering @ Vellore Institute of Technology (VIT), Vellore</strong><br />
    <em>Working at the intersection of AI/ML, Edge Computer Vision, and Hardware-Aware Systems Engineering.</em>
  </p>

  <!-- Connect & Social Badges -->
  <p align="center">
    <a href="https://princekoshthi.vercel.app/" target="_blank">
      <img src="https://img.shields.io/badge/Portfolio-6366F1?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
    </a>
    <a href="https://linkedin.com/in/princekoshthi" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://leetcode.com/u/PrinceofPars/" target="_blank">
      <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
    </a>
    <a href="https://github.com/PrinceofPars" target="_blank">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="mailto:princekoshthi@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>

  <!-- Profile Visitor Counter Badge -->
  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=PrinceofPars&label=Profile%20Views&color=6366F1&style=flat-square" alt="Profile Views" />
  </p>

</div>

---

### 🚀 About Me & Engineering Focus

```yaml
Name: Prince Koshthi
Institution: Vellore Institute of Technology (VIT), Vellore
Degree: B.Tech in Computer Science & Engineering
Core_Focus:
  - Systems & Hardware-Aware AI (Flash Tiering, KV Cache Offloading, Sparse Attention)
  - Sub-millisecond Computer Vision & Edge Acceleration (TensorRT, DeepStream, ONNX)
  - Generative AI & Retrieval Systems (LangChain, LangGraph, RAG)
  - High-Concurrency Backend Architecture (FastAPI, Flask, MongoDB, Docker)
Status: "Profiling memory bottlenecks & scaling intelligent full-stack systems"
```

---

### 🛠️ Tech Stack & Tooling

<div align="center">
  <!-- Skillicons Visual Grid -->
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,cpp,c,js,pytorch,tensorflow,opencv,fastapi,flask,react,tailwind,mongodb,mysql,docker,linux,git,postman,vercel&theme=dark" alt="Prince's Tech Stack" />
  </a>
</div>

<br />

| Domain | Core Technologies & Frameworks |
| :--- | :--- |
| **Languages** | `Python`, `C++`, `C`, `JavaScript (ES6+)`, `SQL`, `Bash` |
| **AI / Machine Learning** | `PyTorch`, `TensorFlow`, `Keras`, `Scikit-Learn`, `XGBoost`, `NumPy`, `Pandas` |
| **Vision & Edge Inference** | `OpenCV`, `YOLOv8 / YOLOX`, `ByteTrack`, `NVIDIA TensorRT`, `ONNX Runtime`, `DeepStream` |
| **Generative AI & LLMs** | `LangChain`, `LangGraph`, `RAG Architectures`, `KV Cache Optimization`, `Vector Embeddings` |
| **Web & Backend** | `FastAPI`, `Flask`, `Node.js`, `React`, `TailwindCSS`, `RESTful APIs` |
| **Databases & DevOps** | `MongoDB`, `MySQL`, `Docker`, `Linux / SSH`, `Git / GitHub`, `Postman`, `Vercel` |

---

### 🏆 Featured Engineering Projects

#### 1. [AI-SSD — Co-Designed KV Cache & Storage Simulator](https://github.com/PrinceofPars/ai-ssd)
> *Hardware-aware architectural simulator mitigating the LLM "memory wall" during extreme context inference (32K–128K tokens).*

[![Simulator](https://img.shields.io/badge/System-LLM%20Storage%20Co--Design-blueviolet?style=flat-square)](https://github.com/PrinceofPars/ai-ssd)
[![Tech](https://img.shields.io/badge/Tech-Python%20%7C%20FTL%20Modeling%20%7C%20Sparse%20Attention-informational?style=flat-square)](https://github.com/PrinceofPars/ai-ssd)

- **Key Highlights:**
  - Modeled multi-channel flash tiering, speculative prefetching, and Top-$k$ sparse KV token retrieval.
  - Achieved up to **80% host RAM reduction** and **90% PCIe bus traffic reduction** in simulated 32K context benchmarks.
- **Links:** [Repository](https://github.com/PrinceofPars/ai-ssd) • [Architecture Deep-Dive](https://github.com/PrinceofPars/ai-ssd/blob/main/docs/DEEP_DIVE_EXPLANATION.md)

<details>
  <summary>🔍 <b>Click to expand: AI-SSD Technical Deep-Dive & Mechanics</b></summary>
  <br />

  ```
  [LLM Attention Engine]
         │
         ▼
  ┌──────────────────────────────────────────────────────────┐
  │ Host Memory Manager (Top-K Sparse Token Cache)            │
  └────────┬─────────────────────────────────────────────────┘
           │ Speculative Prefetch & Tile Requests
           ▼
  ┌──────────────────────────────────────────────────────────┐
  │ Multi-Channel FTL Simulator (Wear-Leveling & Parallel IO) │
  └────────┬─────────────────────────────────────────────────┘
           │ NVMe Channel Parallelism
           ▼
  ┌──────────────────────────────────────────────────────────┐
  │ Tensor-Aware Flash Storage Arrays                         │
  └──────────────────────────────────────────────────────────┘
  ```
  - **Memory Wall Mitigation:** Offloads inactive KV layers to high-speed NVMe flash channels while dynamically caching hot attention heads in host RAM.
  - **Latency Masking:** Overlaps prompt prefill execution with speculative asynchronous page fetches.
</details>

<br />

#### 2. [BatchSwap — Algorithmic Student Exchange Automation](https://github.com/PrinceofPars/batch-swap-frontend)
> *Automated academic exchange platform resolving lab and class batch swaps with fairness guarantees.*

[![Full-Stack](https://img.shields.io/badge/Full--Stack-React%20%7C%20FastAPI%20%7C%20MongoDB-success?style=flat-square)](https://github.com/PrinceofPars/batch-swap-frontend)
[![Status](https://img.shields.io/badge/Live-Demo%20Active-brightgreen?style=flat-square)](https://batch-swap-frontend.vercel.app)

- **Key Highlights:**
  - Designed an automated **CGPA-balanced bipartite pairing algorithm** preventing administrative and academic scheduling conflicts.
  - Full administrator dashboard featuring live exchange approvals, cohort analytics, and dynamic PDF exports via `jsPDF-autotable`.
- **Links:** [Frontend Repo](https://github.com/PrinceofPars/batch-swap-frontend) • [Backend Repo](https://github.com/PrinceofPars/batch-swap-backend) • [Live App](https://batch-swap-frontend.vercel.app)

<br />

#### 3. [AGRIWISE — Precision Agriculture & Edge Vision System](https://github.com/PrinceofPars/AGRIWISE)
> *Decision-support platform fusing ensemble machine learning with real-time edge vision for crop disease detection.*

[![Edge AI](https://img.shields.io/badge/ML-XGBoost%20%2B%20ANN%20Ensemble-orange?style=flat-square)](https://github.com/PrinceofPars/AGRIWISE)
[![Vision](https://img.shields.io/badge/Vision-YOLOv8%20ONNX-blue?style=flat-square)](https://github.com/PrinceofPars/AGRIWISE)

- **Key Highlights:**
  - Hybrid ensemble (XGBoost + ANN) predicting optimal crop rotations from soil N-P-K nutrients, weather conditions, and terrain profiles.
  - Deployed lightweight YOLOv8 ONNX model for rapid edge inference of leaf diseases.
- **Links:** [Repository](https://github.com/PrinceofPars/AGRIWISE) • [ML Documentation](https://github.com/PrinceofPars/AGRIWISE/tree/main/ML)

<br />

#### 4. [Dhadkan — Real-Time ECG Arrhythmia Diagnostics](https://github.com/PrinceofPars/Dhadkan)
> *Deep learning biosignal pipeline for automated cardiac classification and clinical risk assessment.*

[![Deep Learning](https://img.shields.io/badge/Deep%20Learning-1D%20CNN-red?style=flat-square)](https://github.com/PrinceofPars/Dhadkan)
[![Signal Processing](https://img.shields.io/badge/Biosignal-125%20Hz%20R--Peak-yellow?style=flat-square)](https://github.com/PrinceofPars/Dhadkan)

- **Key Highlights:**
  - 1D Convolutional Neural Network trained to classify cardiac rhythms across 5 morphological arrhythmia classes.
  - Real-time 125 Hz R-peak detection pipeline with automated clinical diagnostic reporting.
- **Links:** [Repository](https://github.com/PrinceofPars/Dhadkan)

---

### 📊 GitHub & Problem Solving Performance

<div align="center">

  <!-- LeetCode Real-Time Performance Card with Submission Streak Heatmap (Zero Acceptance Rate Shown) -->
  <a href="https://leetcode.com/u/PrinceofPars/" target="_blank">
    <img src="https://leetcard.jacoblin.cool/PrinceofPars?theme=dark&font=baloo&ext=heatmap" alt="PrinceofPars LeetCode Stats & Submission Streak Heatmap" width="48%" />
  </a>
  <!-- GitHub Streak Stats (Using stable Heroku mirror) -->
  <!-- <a href="https://github.com/PrinceofPars" target="_blank">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=PrinceofPars&theme=tokyonight&hide_border=true&background=0D1117&ring=6366F1&fire=FFA116&currStreakLabel=6366F1" alt="GitHub Streak" width="48%" />
  </a> -->

  <br /><br />

  <!-- GitHub Main Stats and Top Languages (Using high-speed verified mirror) -->
  <a href="https://github.com/PrinceofPars" target="_blank">
    <img src="https://github-readme-stats-fast.vercel.app/api?username=PrinceofPars&show_icons=true&theme=tokyonight&hide_border=true&title_color=6366F1&icon_color=38BDF8&text_color=94A3B8&bg_color=0D1117" alt="Prince Koshthi's GitHub Stats" height="150" />
    <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=PrinceofPars&layout=compact&theme=tokyonight&hide_border=true&title_color=6366F1&text_color=94A3B8&bg_color=0D1117" alt="Top Languages" height="150" />
  </a>

</div>

---

### 🐍 Contribution Activity Snake

<div align="center">
  <!-- Note: The snake SVG will display once the GitHub Actions workflow runs on GitHub -->
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PrinceofPars/PrinceofPars/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PrinceofPars/PrinceofPars/output/github-contribution-grid-snake.svg">
    <img alt="Contribution Grid Snake" src="https://raw.githubusercontent.com/PrinceofPars/PrinceofPars/output/github-contribution-grid-snake.svg">
  </picture>
  <p><sub>⚡ Daily automated contribution graph snake powered by GitHub Actions</sub></p>
</div>

---

### 🎵 Coding Soundtrack & Music Activity

<div align="center">

  <a href="https://open.spotify.com" target="_blank">
    <img src="https://img.shields.io/badge/Spotify-Deep%20Focus%20%7C%20Coding%20Flow-1DB954?style=for-the-badge&logo=spotify&logoColor=white" alt="Spotify Status" />
  </a>

  <br /><br />

  <!-- 
    Tip: To enable real-time dynamic track listening:
    1. Visit https://spotify-github-profile.kittinanx.com
    2. Click 'Login with Spotify' to get your UID
    3. Replace below with: https://spotify-github-profile.kittinanx.com/api/view?uid=YOUR_UID&cover_image=true&theme=novatorem
  -->
  <a href="https://spotify-github-profile.kittinanx.com/api/view?uid=pqh8xe3h85x1qhde3khqa5kkr&redirect=true">
    <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=pqh8xe3h85x1qhde3khqa5kkr&cover_image=true&theme=novatorem&show_offline=false&background_color=0d1117&interchange=true&profanity=false&hide_remaster=true&bar_color=53b14f&bar_color_cover=true">
  </a>

  <p>
    <sub>🎧 Real-time music activity streaming via Spotify API • Keeping the flow state locked in</sub>
  </p>

</div>

---

### 💬 Let's Connect & Collaborate

<div align="center">
  <p>
    I am always open to discussing <b>AI systems research</b>, <b>edge computer vision deployments</b>, and <b>backend engineering challenges</b>.
  </p>
  <a href="https://princekoshthi.vercel.app/">
    <img src="https://img.shields.io/badge/Explore%20Full%20Portfolio-6366F1?style=for-the-badge&logo=rocket&logoColor=white" alt="Portfolio Link" />
  </a>
  &nbsp;
  <a href="mailto:princekoshthi@gmail.com">
    <img src="https://img.shields.io/badge/Send%20An%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Link" />
  </a>
</div>

<br />

<div align="center">
  <sub>Designed with precision by <b><a href="https://github.com/PrinceofPars">Prince Koshthi</a></b> • 2026</sub>
</div>

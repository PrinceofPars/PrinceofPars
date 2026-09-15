# Hi, I'm Prince Koshthi 👋

I am a Computer Science Engineering student at Vellore Institute of Technology (VIT), Vellore, working at the intersection of Artificial Intelligence, Machine Learning, and Software Engineering. My work focuses on building practical, performance-driven systems—ranging from edge computer vision pipelines and LLM inference storage simulators to full-stack automation platforms.

---

### 🌐 Connect & Links

- **Portfolio:** [princekoshthi.vercel.app](https://princekoshthi.vercel.app/)
- **GitHub:** [github.com/PrinceofPars](https://github.com/PrinceofPars)
- **LinkedIn:** [linkedin.com/in/princekoshthi](https://www.linkedin.com/in/princekoshthi/)
- **Email:** [princekoshthi@gmail.com](mailto:princekoshthi@gmail.com)

---

### 🛠️ What I Build

- **AI / ML & Computer Vision:** Edge vision pipelines with sub-millisecond inference optimizations (TensorRT, NVIDIA DeepStream, ONNX Runtime), object detection/tracking (YOLOv8, YOLOX, ByteTrack), and multimodal semantic representations (CLIP, CLAP, BART).
- **Generative AI & LLM Systems:** Retrieval-Augmented Generation (RAG) architectures with LangChain and LangGraph, agentic workflows, and KV cache memory optimization for long-context LLM inference.
- **Software Engineering & Backends:** Asynchronous RESTful APIs with FastAPI and Flask, robust data schemas in MongoDB and MySQL, and full-stack React applications.
- **Systems & AI Infrastructure:** Hardware-aware simulation, multi-channel storage co-design, and deployment pipelines optimized for GPU/edge resource constraints.

---

### 📌 Featured Projects

#### [AI-SSD — Co-Designed KV Cache & Storage Simulator](https://github.com/PrinceofPars/ai-ssd)
An architectural simulator co-designing LLM Key-Value (KV) cache offloading with tensor-aware Solid-State Drives (SSDs) to mitigate the memory wall in long-context inference (32K–128K tokens).
- **Tech:** Python, NumPy, Systems Simulation, Multi-Channel FTL Modeling, Sparse Attention Algorithms
- **Highlights:**
  - Modeled multi-channel flash tiering, speculative prefetching, and sparse Top-$k$ KV retrieval to reduce host memory pressure.
  - Achieved up to 80% host RAM footprint reduction and 90% PCIe traffic reduction in simulated 32K context benchmarks with minimal latency overhead.
- **Links:** [Repository](https://github.com/PrinceofPars/ai-ssd) | [Architecture Deep-Dive](https://github.com/PrinceofPars/ai-ssd/blob/main/docs/DEEP_DIVE_EXPLANATION.md)

#### [BatchSwap — Smart Student Batch Swap Automation](https://github.com/PrinceofPars/batch-swap-frontend)
A full-stack algorithmic platform designed to automate and resolve academic lab/class batch swaps fairly between students.
- **Tech:** React, TailwindCSS, FastAPI, Python, MongoDB, jsPDF, Axios
- **Highlights:**
  - Implemented an automated CGPA-balanced pairing algorithm to guarantee fair academic exchange matching without administrative conflict.
  - Built an administrative dashboard featuring live pairing approval, CGPA impact analysis, and dynamic client-side PDF export with `jsPDF-autotable`.
- **Links:** [Frontend Repo](https://github.com/PrinceofPars/batch-swap-frontend) | [Backend Repo](https://github.com/PrinceofPars/batch-swap-backend) | [Live Demo](https://batch-swap-frontend.vercel.app)

#### [AGRIWISE — Precision Agriculture & Crop Recommendation Model](https://github.com/PrinceofPars/AGRIWISE)
An intelligent decision-support system integrating hybrid machine learning models and edge vision for agricultural yield optimization.
- **Tech:** Python, Flask, XGBoost, Scikit-learn, TensorFlow, YOLOv8 (ONNX Runtime), React, TailwindCSS
- **Highlights:**
  - Developed a hybrid ensemble (XGBoost + ANN) predicting optimal crop rotations based on soil N-P-K nutrients, climatic metrics, terrain, and market economics.
  - Integrated a lightweight YOLOv8 ONNX model for real-time leaf disease and pest classification.
- **Links:** [Repository](https://github.com/PrinceofPars/AGRIWISE) | [ML Module Documentation](https://github.com/PrinceofPars/AGRIWISE/tree/main/ML)

#### [Dhadkan — Real-Time ECG Arrhythmia Diagnostics](https://github.com/PrinceofPars/Dhadkan)
A deep-learning-powered biosignal diagnostic tool for continuous ECG monitoring, peak detection, and automated patient risk assessment.
- **Tech:** Python, TensorFlow, Keras, NeuroKit2, Pandas, NumPy, Matplotlib
- **Highlights:**
  - Designed a 1D Convolutional Neural Network (CNN) trained to classify cardiac arrhythmias across 5 distinct morphological arrhythmia classes.
  - Built real-time R-peak signal processing pipelines (125 Hz) with automated alert thresholds and clinical diagnostic PDF report generation.
- **Links:** [Repository](https://github.com/PrinceofPars/Dhadkan)

---

### ⚡ Currently Building

- **AI-SSD Extensions:** Expanding tensor-aware flash controller simulation to investigate FlashAttention tile streaming and NVMe computational storage integration for multi-gigabyte context windows.

---

### 💻 Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | Python, C++, C, JavaScript |
| **AI / Machine Learning** | PyTorch, TensorFlow, Keras, Scikit-learn, XGBoost, NumPy, Pandas |
| **Computer Vision & Inference** | OpenCV, YOLOv8, YOLOX, TensorRT, ONNX Runtime, NVIDIA DeepStream |
| **Generative AI & LLMs** | LangChain, LangGraph, RAG Architectures, Vector Embeddings |
| **Web & Backend** | FastAPI, Flask, Node.js, React, TailwindCSS, REST APIs |
| **Databases & Tools** | MongoDB, MySQL, Git, Docker, Linux / SSH Environments |

---

### 🔬 Engineering Interests

- **AI Systems & Hardware Co-Design:** Optimizing memory hierarchies, KV cache offloading, and kernel execution for large generative models.
- **Edge Vision Inference:** Maximizing throughput and minimizing latency on resource-constrained embedded GPUs and edge accelerators.
- **Backend Architecture & Systems:** High-concurrency API design, algorithmic resource allocation, and robust data modeling.

---

### 📊 GitHub Overview

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=PrinceofPars&show_icons=true&theme=transparent&hide_border=true&title_color=0969da&icon_color=0969da&text_color=57606a" alt="Prince Koshthi's GitHub Stats" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PrinceofPars&layout=compact&theme=transparent&hide_border=true&title_color=0969da&text_color=57606a" alt="Top Languages" height="150" />
</div>

---

### 🎯 Current Focus

- Profiling memory bottlenecks and I/O tiering strategies in LLM decoding stages.
- Developing modular agentic workflows using LangGraph and vector search pipelines.
- Designing resilient full-stack systems with Python and modern web technologies.

---

Building, learning, and shipping — one project at a time.

🔗 [Prince Koshthi — Portfolio](https://princekoshthi.vercel.app/)

<div align="center">

  <h1>Hey <img src="https://raw.githubusercontent.com/SP-XD/SP-XD/refs/heads/main/images/Developer.gif" height="30px" width="30px"> I'm Tanay Kumar</h1>
  <p>
    <strong>AI Engineer · LLM Evaluation & Benchmarking · Agentic Systems · Research-to-Production ML</strong>
  </p>
  <p>
    <em>MSc Computer Science Engineering @ Politecnico di Milano &nbsp;|&nbsp; BTech CSE @ BIT Mesra</em>
  </p>

  <p>
    <a href="https://arxiv.org/abs/2310.05030">
      <img src="https://img.shields.io/badge/EMNLP%202023-Outstanding%20Paper%20Award%20%F0%9F%8F%86-ffd700?style=for-the-badge&labelColor=1a1a1a" alt="EMNLP 2023 Outstanding Paper Award" />
    </a>
    <a href="https://www.polimi.it/">
      <img src="https://img.shields.io/badge/Politecnico%20di%20Milano-MSc%20CS%20Eng-003366?style=for-the-badge&labelColor=1a1a1a" alt="Politecnico di Milano" />
    </a>
    <a href="https://linkedin.com/in/krtanay">
      <img src="https://img.shields.io/badge/LinkedIn-krtanay-0077b5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1a1a1a" alt="LinkedIn" />
    </a>
    <a href="mailto:tanay.kumar@mail.polimi.it">
      <img src="https://img.shields.io/badge/Email-tanay.kumar@mail.polimi.it-ea4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1a1a1a" alt="Email" />
    </a>
  </p>

</div>

<p align="center">
  <img src="https://i.pinimg.com/originals/42/b4/22/42b4229a9ec3145edaa895b2415dd720.gif" alt="Banner" width="100%" />
</p>

---

## 📌 Executive Summary

> **AI Engineer and NLP/LLM Researcher** specializing in **LLM evaluation, bias & hallucination auditing, and distributed agentic frameworks**.  
> Recipient of the **EMNLP 2023 Outstanding Paper Award** for foundational research on AI-generated text detection (*Counter Turing Test*).  
> Extensive track record bridging rigorous empirical benchmarks (**HEXBENCH**, **ADI**) with cloud-native, production MLOps systems (**MedRAG-Assist**, **MultiMinds**) deployed across AWS, Docker, and CI/CD pipelines.

- 🎓 **MSc in Computer Science Engineering** at **Politecnico di Milano**, Italy (Thesis at *The Data Science Lab*).
- 🔬 **Research Focus:** Personality-conditioned bias in multilingual LLMs, AI detectability metrics, and hallucination reduction at the architecture level.
- ⚙️ **Engineering Focus:** Grounded Retrieval-Augmented Generation (RAG), multi-agent state machines with LangGraph, and sub-second inference optimization.
- 📍 Based in **Milan, Italy** · Open to high-impact AI Engineering, Research Science, and Applied LLM roles.

---

## 🏆 Publications & Scientific Honors

<table>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Venue / Award</th>
      <th>Key Contribution</th>
      <th>Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Counter Turing Test (CT2): AI-Generated Text Detection is Not as Easy as You May Think</strong></td>
      <td>
        <span style="color:#e3b341; font-weight:bold;">🏆 Outstanding Paper Award</span><br>
        <strong>EMNLP 2023</strong>
      </td>
      <td>
        Benchmarked 6 transformer architectures (GPT-2, RoBERTa, DeBERTa variants). Pioneered the <em>AI Detectability Index (ADI)</em> and threshold calibration via ROC curves (+12% accuracy gain).
      </td>
      <td>
        <a href="https://arxiv.org/abs/2310.05030">
          <img src="https://img.shields.io/badge/arXiv-2310.05030-B31B1B?style=flat-square&logo=arxiv&logoColor=white" alt="arXiv">
        </a>
      </td>
    </tr>
    <tr>
      <td><strong>ML-based IoT Framework for Diabetes Detection</strong></td>
      <td>
        <strong>Springer WPC 2023</strong><br>
        <em>Wireless Personal Communications</em>
      </td>
      <td>
        Predictive healthcare modeling utilizing ensemble ML classifiers on edge IoT physiological sensor data streams.
      </td>
      <td>
        <a href="https://www.researchsquare.com/">
          <img src="https://img.shields.io/badge/Springer-Research%20Square-00558F?style=flat-square" alt="Springer">
        </a>
      </td>
    </tr>
    <tr>
      <td><strong>IoT-Enabled Heart Disease Detection System Using KNN</strong></td>
      <td>
        <strong>IEEE ICCNT 2022</strong><br>
        <em>IEEE Xplore</em>
      </td>
      <td>
        High-sensitivity early cardiac anomaly detection model with real-time biometric telemetry processing.
      </td>
      <td>
        <a href="https://ieeexplore.ieee.org/">
          <img src="https://img.shields.io/badge/IEEE-Xplore-00629B?style=flat-square&logo=ieee&logoColor=white" alt="IEEE">
        </a>
      </td>
    </tr>
  </tbody>
</table>

---

## 🔬 Benchmark & Research Highlights

### 🧪 HEXBENCH — Multilingual LLM Bias Benchmark
*The Data Science Lab, Politecnico di Milano (Jul 2025 – Mar 2026)*
- **Scale:** Created the first-of-its-kind benchmark of **23,400+ LLM narratives across 50 occupations** evaluating personality-conditioned gender bias in Hindi-English code-mixed settings.
- **Key Empirical Finding:** Dark personality traits (Dark Triads) amplify occupational gender stereotyping by up to **27%** across evaluated models (**Llama 3, Mistral, Gemma, DeepSeek R1, GPT 5.2, FalconMamba**), while Honesty-Humility and Agreeableness consistently curb biased outputs.
- **Fairness & Fluency Assurance:** Tracked **BERTScore** simultaneously with parity metrics to guarantee that prompt debiasing interventions preserved generation fluency and coherence.

### 🔍 AI Detectability Index & Hallucination Auditing
*Artificial Intelligence Institute, University of South Carolina (Sep 2022 – Jul 2023)*
- Built modular evaluation harnesses analyzing perplexity, entropy, and n-gram artifacts across 5+ LLM families.
- Formulated embedding-space distance metrics to detect latent representation drift and token-level distribution collapses.

---

## 🛠️ Technical Arsenal

<div align="center">

### 🧠 Deep Learning, LLMs & Evaluation
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="HuggingFace" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-2C3E50?style=flat-square&logo=diagram-next&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/FAISS-00599C?style=flat-square&logo=meta&logoColor=white" alt="FAISS" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/BERTScore-4B8BBE?style=flat-square" alt="BERTScore" />
</p>

### ☁️ MLOps, Cloud & Production Deployment
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/AWS_(ECS_/_ECR_/_AppRunner)-232F3E?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/Jenkins_CI/CD-D24939?style=flat-square&logo=jenkins&logoColor=white" alt="Jenkins" />
  <img src="https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white" alt="Railway" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
</p>

### 💻 Programming Languages & Foundations
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/SQL_(PostgreSQL_/_MySQL)-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Bash_/_Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
</p>

### 🔬 Research Competencies
<p>
  <code>LLM Evaluation & Benchmarking</code> · 
  <code>Bias & Fairness Auditing</code> · 
  <code>Hallucination Detection</code> · 
  <code>Perplexity & Entropy Metrics</code> · 
  <code>Statistical Testing</code> · 
  <code>Experiment Design</code>
</p>

</div>

---

## 🤝 Connect & Collaborate

<div align="center">

  <p>
    I am actively engaging in discussions surrounding <strong>LLM evaluation, multimodal agentic frameworks, and reliable AI systems</strong>.
  </p>

  <p>
    <a href="https://linkedin.com/in/krtanay" target="_blank">
      <img src="https://raw.githubusercontent.com/gauravghongde/social-icons/9d939e1c5b7ea4a24ac39c3e4631970c0aa1b920/SVG/Color/LinkedIN.svg" alt="LinkedIn" width="38" height="38" style="margin: 0 10px;"/>
    </a>
    <a href="mailto:tanay.kumar@mail.polimi.it" target="_blank">
      <img src="https://raw.githubusercontent.com/gauravghongde/social-icons/9d939e1c5b7ea4a24ac39c3e4631970c0aa1b920/SVG/Color/Gmail.svg" alt="Polimi Email" width="38" height="38" style="margin: 0 10px;"/>
    </a>
    <a href="https://github.com/krtanay" target="_blank">
      <img src="https://raw.githubusercontent.com/gauravghongde/social-icons/9d939e1c5b7ea4a24ac39c3e4631970c0aa1b920/SVG/Color/Github.svg" alt="GitHub" width="38" height="38" style="margin: 0 10px;"/>
    </a>
  </p>

  <p>
    📍 <em>Milan, Italy &nbsp;|&nbsp; 📞 +39 333 787 9112</em>
  </p>

  <p>
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/krtanay/krtanay/output/github-snake-dark.svg" />
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/krtanay/krtanay/output/github-snake.svg" />
      <img alt="GitHub Contribution Snake Animation" src="https://raw.githubusercontent.com/krtanay/krtanay/output/github-snake.svg" />
    </picture>
  </p>

</div>

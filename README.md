<h1 align="center">Hey, I'm Qasim 👋 — I turn messy real-world problems into working AI systems.</h1>

<p align="center">
  <em>AI/ML Engineer · Computer Vision & Deep Learning · GenAI/RAG Systems · Building toward Agentic AI</em>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="dark_mode (1).svg" />
  <source media="(prefers-color-scheme: light)" srcset="light_mode (1).svg" />
  <img alt="qasim233's GitHub profile" src="dark_mode (1).svg" />
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/muhammad-qasim-a51a23291/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:muhammad.qasim031221@gmail.com"><img src="https://img.shields.io/badge/Email-Reach%20Out-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>

---

### 🛠️ Building
- A production-style **computer vision pipeline** for real-time parking occupancy detection (YOLOv12 + Flask), live across two physical sites.
- A full-stack **AI diagnostic platform** for intracranial aneurysm detection from 3D medical scans — PyTorch/ResNet50 model, FastAPI backend, Next.js frontend, with an integrated clinical AI chatbot.
- A **hybrid rule + LLM agent** that triages WhatsApp messages (notify/digest/mute) across text, OCR, and transcribed voice notes — built for a hackathon on AI orchestration.

### 🔬 Researching
- Robustness in **federated learning** — neuron-centric pruning and anomaly detection to defend against poisoning attacks.
- Applied **generative modeling** — VAE/GAN architectures for image synthesis, and the theory behind flow-based generative models.

### 📚 Shipping & leveling up in
- **RAG pipelines and local LLM serving** — LangChain, FAISS, Ollama (Mistral-7B) — already shipped across 3 projects (document Q&A, summarization, WhatsApp agent).
- Closing the gap between applied deep learning and production **agentic AI workflows**.

---

## ⚙️ Tech Stack

**Languages & Core**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Generative AI / LLM**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logo=gradio&logoColor=white)

**ML / Deep Learning**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

**Computer Vision**
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)

**Deployment & Data**
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**AI-Assisted Dev**
![Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)

---

## 🚀 Project Showcase

### 📲 WhatsApp Message Notification Router — Hybrid Rule + LLM Agent
**Problem solved:** Deciding which incoming messages actually need attention vs. mute/digest, across text, images, and voice notes.
Priority-ordered rule engine catches high-confidence safety cases (scam/phishing/prompt-injection) before falling back to an LLM for ambiguous decisions; TF-IDF evidence retriever justifies each call; confidence calibration blends rule–LLM agreement.
`Python` `Pandas` `scikit-learn` `EasyOCR` `faster-whisper` `Florence-2` `LLM reasoning`

### 📄 DocForge — RAG-Based Document Q&A Assistant
**Problem solved:** Natural-language Q&A over long, domain-specific PDFs without relying on external APIs.
End-to-end RAG pipeline with LangChain orchestration, FAISS semantic retrieval, and a locally-served Mistral-7B via Ollama, wrapped in a Gradio front end.
`Python` `LangChain` `FAISS` `Ollama` `Mistral-7B` `Gradio`

### 🅿️ Smart Parking Occupancy System
**Problem solved:** Drivers wasting time hunting for open spots, and lot operators flying blind on utilization.
Real-time CCTV-based vehicle detection deployed live across two parking lots, with a mobile app for drivers and an admin dashboard for operators.
`Python` `Flask` `YOLOv12` `OpenCV` `Kotlin`

### 🧠 Multi-Modal Aneurysm Detection Platform
**Problem solved:** Slow, manual review of 3D medical scans (CTA/MRA/MRI) for intracranial aneurysms.
Full-stack diagnostic web app with automated report generation, real-time heatmap streaming, and a domain-specific clinical AI chatbot.
`PyTorch` `ResNet50` `SimpleITK` `Next.js` `FastAPI` `Node.js`

### 📝 Document Summarizer — RAG-Based Summarization Tool
**Problem solved:** Turning long PDF/TXT/Markdown documents into accurate abstractive summaries.
Configurable chunking/overlap RAG pipeline with sentence-transformer embeddings for retrieval and BART for generation, plus an interactive CLI for custom models.
`Python` `FAISS` `Sentence-Transformers` `BART` `PyTorch`

### 🛡️ Federated Learning Defense
**Problem solved:** Federated learning systems are vulnerable to poisoning attacks from malicious clients.
Neuron-centric defense combining pruning and anomaly detection — improved robustness by 5%, held 96% accuracy under attack.
`Python` `PyTorch` `Federated Learning`

### 😷 Face Mask Detection System
**Problem solved:** Manual mask-compliance monitoring doesn't scale to live video at volume.
Fine-tuned MobileNetV2 for real-time inference at 24 FPS, deployed as a Flask app processing concurrent live feeds.
`TensorFlow` `MobileNetV2` `OpenCV` `Flask`

### 🎧 Spotify-Style Recommendation Engine
**Problem solved:** Static recommendations that don't adapt as user behavior changes.
Distributed collaborative + content-based filtering pipeline processing 100K+ records with sub-second real-time updates.
`PySpark` `Kafka` `MongoDB`

---

## 📜 Certifications
- Fundamentals of RAG and AI Agents — IBM
- Machine Learning Specialization — DeepLearning.AI
- TensorFlow Developer Specialization — DeepLearning.AI

---

<p align="center">
  📬 <strong>Let's connect</strong> — open to AI/ML Engineer roles (Pakistan or remote).
  <br/>
  <a href="https://www.linkedin.com/in/muhammad-qasim-a51a23291/">LinkedIn</a> · 
  <a href="mailto:muhammad.qasim031221@gmail.com">Email</a>
</p>

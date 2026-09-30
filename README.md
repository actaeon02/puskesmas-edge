# 🏥 PuskesmasEdge: Last-Mile Healthcare AI for Rural Clinics

[![World Bank Small AI Hackathon](https://shields.io)](#)
[![License: MIT](https://shields.io)](LICENSE)
[![Built with: Local SLM](https://shields.io)](#)

**PuskesmasEdge** is an offline-first, privacy-preserving Small Language Model (SLM) framework tailored for rural primary health centers (*Puskesmas*) in low-resource environments. By running entirely on local, consumer-grade hardware, it bridges the healthcare infrastructure gap for communities isolated by the digital divide.

---

## 🌍 The Problem & Impact
Rural clinics face severe internet disruptions, understaffed medical teams, and heavy administrative burdens. Traditional LLMs (like GPT-4) fail here because they require constant high-speed cloud access and expensive APIs. 

**PuskesmasEdge** solves this by squeezing high-utility medical intelligence into a lightweight model that runs locally on common desktop PCs, laptops, or tablets already found in rural clinics.

---

## ⚡ Key Features
* **100% Offline Capability:** Operates entirely without internet connectivity, ensuring uninterrupted local service.
* **Low-Resource Optimization:** Quantized to run efficiently on low-spec hardware (e.g., 4GB–8GB RAM).
* **Clinical Decision Support:** Assists frontline nurses and midwives (*Nakes*) with patient triaging and standard primary care protocols.
* **Local Language & Context:** Fine-tuned to understand medical reporting contexts and localized Indonesian healthcare terminologies.
* **Data Privacy Compliant:** Patient data never leaves the local clinic router, complying natively with data sovereignty requirements.

---

## 🛠️ Architecture & Tech Stack
* **Model Baseline:** [Specify your model base, e.g., Phi-3-mini / Llama-3-8B-Instruct / Gemma-2B]
* **Quantization:** [e.g., GGUF 4-bit / AWQ] for local deployment.
* **Inference Engine:** [e.g., Llama.cpp / Ollama / ONNX Runtime]
* **User Interface:** [e.g., Streamlit / Gradio / Lightweight HTML/JS] running over a local clinic intranet.

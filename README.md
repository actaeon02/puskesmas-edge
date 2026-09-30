# 🏥 PuskesmasEdge: Last-Mile Healthcare AI for Rural Clinics

[![World Bank Small AI Hackathon](https://img.shields.io/badge/World%20Bank-Small%20AI%20Hackathon-blue?style=flat-square)](https://www.worldbank.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![Built with Local SLM](https://img.shields.io/badge/Built%20with-Local%20SLM-2ea44f?style=flat-square)](#architecture--tech-stack)

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

* **Model Baseline:** Llama 3.2:3b
* **Quantization:** Q4_K_M for local deployment.
* **Inference Engine:** Llama.cpp
* **User Interface:** Streamlit running over a local clinic intranet.

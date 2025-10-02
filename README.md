# 🚦 LLM Guardrails: Colab Notebooks

This repository provides **Google Colab notebooks** for experimenting with different guardrail frameworks used in securing and controlling Large Language Models (LLMs).  

It covers hands-on tutorials, code samples, and comparison experiments across three widely discussed frameworks:

- **NVIDIA NeMo Guardrails**
- **Llama Guard** (Meta’s safety classifier)
- **Guardrails AI**

---

## 🛠️ Frameworks Covered

### 🔹 NVIDIA NeMo Guardrails
- Rule-based + ML-driven framework for enforcing safety, security, and compliance.  
- Supports **flow definition files (Colang)** for conversational control.  
- Integration with multiple LLM providers.  
- **Example use cases:** content filtering, data redaction, safety checks.  

---

### 🔹 Llama Guard
- Lightweight guardrail model released by **Meta**.  
- Functions as a **safety classifier** that detects policy-violating generations.  
- Can be used as a filter alongside other LLMs.  
- **Example use cases:** toxicity detection, harmful instruction blocking.  

---

### 🔹 Guardrails AI
- Open-source Python library for specifying, validating, and enforcing constraints on LLM outputs.  
- Schema-driven approach with **pydantic-like validators**.  
- Strong focus on **structured outputs (JSON/XML/YAML)** and semantic validation.  
- **Example use cases:** ensuring responses follow format, preventing hallucinations.  

---

## ▶️ Run in Google Colab

Each notebook can be opened and run directly in Google Colab:

- [NVIDIA NeMo Guardrails Notebook](#)  
- [Llama Guard Notebook](#)  
- [Guardrails AI Notebook](#)  

---

## 📌 Notes
- Ensure you have access to GPU runtime in Colab (`Runtime > Change runtime type > GPU`).  
- Some frameworks may require API keys or model downloads (instructions included in each notebook).  

---

## 📜 License
This repository is released under the MIT License. 


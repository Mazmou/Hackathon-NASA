# 🚀 Hackathon-NASA

> **A production-minded hackathon project showcasing clean architecture, reproducible setup, and real-world engineering practices.**

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 🌟 Overview

This repository contains **Hackathon-NASA**, a project built to demonstrate strong software engineering fundamentals under hackathon constraints. The focus is on **clarity, scalability, and correctness**, not just a working demo.

**What recruiters should notice:**

* Clean project structure
* Secure configuration (no secrets committed)
* Reproducible environment
* Readable, well-documented code

---

## 🎯 Problem Statement

> *Briefly describe the real-world problem this project addresses.*

Example:

> How can we efficiently process and analyze large-scale space or earth-observation data while keeping the system modular and extensible?

---

## 💡 Solution

This project implements:

* A **modular backend architecture**
* Clear separation of concerns
* Config-driven setup using environment variables
* Notebooks for experimentation and validation

Key ideas:

* Fail loudly when configuration is missing
* Prefer explicit code over magic
* Keep hackathon code production-aware

---

## 🧱 Project Structure

```text
Hackathon-NASA/
├── app.ipynb            # Core application logic / experiments
├── RAG.ipynb            # Retrieval-Augmented Generation experiments
├── src/                 # (Optional) reusable modules
├── .gitignore           # Prevents secrets & artifacts from being committed
├── .env.example         # Environment variable template
├── requirements.txt     # Dependencies
└── README.md            # You are here
```

---

## 🔐 Security & Configuration

This project **never commits secrets**.

Configuration is handled via environment variables:

```bash
OPENAI_API_KEY=your_api_key_here
```

* `.env` files are **ignored by Git**
* `.env.example` is provided for reference

This mirrors real-world industry practices.

---

## 🛠️ Tech Stack

* **Language:** Python
* **Environment:** Jupyter / Virtualenv
* **AI / ML:** RAG-style pipelines
* **Version Control:** Git & GitHub

---

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Mazmou/Hackathon-NASA.git
cd Hackathon-NASA
```

### 2. Set up virtual environment

```bash
python -m venv .venv
source .venv/bin/activate  # macOS/Linux
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment

```bash
cp .env.example .env
```


Disclaimer : you must add your own OpenAI key to an .env file and name it in this format : OPENAI_API_KEY=your_api_key_here
---

## 🧪 Experiments & Notebooks

* `app.ipynb` → core logic & pipeline
* `RAG.ipynb` → retrieval + generation experiments

Notebooks are kept **clean, reproducible, and commented**.

---

## 📈 What I Learned

* Writing **secure-by-default** code
* Structuring projects under time pressure
* Bridging experimentation and production thinking
* Communicating technical work clearly
* Finding how to use AI and machine learning to answer to a problem

---

## 🧠 Future Improvements

* Possibility to add a local open-source model like Ollama
* Convert notebooks into reusable Python modules
* Add automated tests
* Add CI (GitHub Actions)
* Improve documentation and diagrams

---

## 👤 Author

**Mahmoud Maz**
Aspiring Software Engineer | AI & Backend Focus

* GitHub: [https://github.com/Mazmou](https://github.com/Mazmou)

---

## 📄 License

This project is licensed under the MIT License.



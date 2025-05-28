# 🧪 CUDIS API Mock Server

`cudis-api-mock-server` is a lightweight, developer-focused mock server that simulates the official CUDIS Wellness API. It provides realistic, customizable data for steps, sleep, heart rate, and other health metrics to help developers build and test applications without depending on live production data or credentials.

---

## 🎯 Purpose

This project supports the development of apps, dashboards, smart contracts, and AI agents that interact with the CUDIS Wellness ecosystem. It is especially useful for:

- Rapid prototyping with fake but realistic data
- Frontend development workflows
- CI testing and integration pipelines
- Educational or demo environments

---

## 🔧 Features

- RESTful endpoints that mirror the structure of CUDIS APIs
- Randomized but realistic biometric data
- Built-in mock authentication/token flow
- Predefined mock users and sessions
- Swagger UI with live documentation
- Lightweight, extensible Python codebase using FastAPI

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **FastAPI** – web framework
- **Uvicorn** – development server
- **Faker** – synthetic data generator
- **Pydantic** – data validation and schema modeling

---

## 🚀 Getting Started

### 1. Clone and Install

```bash
git clone https://github.com/your-org/cudis-api-mock-server.git
cd cudis-api-mock-server
python -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows
pip install -r requirements.txt

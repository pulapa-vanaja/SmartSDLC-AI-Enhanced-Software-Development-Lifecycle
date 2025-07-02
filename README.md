# 🤖 SmartSDLC – AI-Powered SDLC Automation Platform

## 🧩 1. Introduction

**📌 Project Title:** SmartSDLC – AI-Powered Software Development Lifecycle Automation  
**👨‍💻 Team Members:**
- 👩‍💼 **Vanaja Pulapa** – Team Leader, Full Stack & AI Integration  
- 🎨 **Lakshmidurga Sathi** – Frontend Developer (Streamlit)  
- 🧠 **Sonti Naga Tulasi** – Backend Developer (FastAPI, Model Integration)  
- 🧾 **Yalla Manasa Siri** – PDF Processing & Testing  

---

## 🚀 2. Project Overview

### 🎯 Purpose:
SmartSDLC is a Generative AI-based platform that automates multiple phases of the Software Development Lifecycle (SDLC), including:

- 📌 Requirement Classification  
- 💻 Code Generation  
- 🧪 Unit Test Generation  
- 🐞 Bug Fixing  
- 🧠 Code Summarization  

All using powerful IBM Watsonx foundation models.

### 🛠️ Features:
- 📤 Upload PDF requirements and classify into SDLC phases  
- ⚙️ AI code generation in multiple programming languages  
- 🧪 Test case generation for uploaded/generated code  
- 🔍 Bug fixing using AI-based suggestions  
- 📄 Code summarization  
- 🤖 Floating AI Chat Assistant for dev queries  
- 🔐 Secure login & user authentication  

---

## 🧱 3. Architecture

### 🌐 Frontend (Streamlit):
- 🎨 Streamlit UI with custom CSS and responsive layout  
- 📑 Separate pages for each SDLC stage  
- 🧭 Sidebar navigation  

### 🔧 Backend (FastAPI):
- 🐍 Python-based API using FastAPI  
- 📂 Routes like `/generate-code`, `/classify-pdf`, etc.  
- 🚀 Hosted using Uvicorn server  

### 🗄️ Database (SQLite):
- 👥 User login credentials and activity stored securely  
- 🧾 Persistent file-based task history  

---

## ⚙️ 4. Setup Instructions

### ✅ Prerequisites:
- Python 3.10+  
- pip  
- Streamlit  
- FastAPI  
- Uvicorn  
- SQLite3  

### 🧪 Installation:
```bash
# 📥 Clone the repository
git clone https://github.com/pulapa-vanaja/SmartSDLC-AI-Enhanced-Software-Development-Lifecycle smartsdlc
cd smartsdlc

# 🛠️ Backend Setup
cd app
pip install -r requirements.txt

# 🎨 Frontend Setup
cd ../smart_sdlc_frontend
pip install -r requirements.txt

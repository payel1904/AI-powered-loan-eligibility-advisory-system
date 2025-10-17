# 💡 AI-Powered Loan Eligibility Advisory System  

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green)](https://fastapi.tiangolo.com/)
[![OpenCV](https://img.shields.io/badge/OpenCV-OCR-red)](https://opencv.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 🏦 Overview  

The **AI-Powered Loan Eligibility Advisory System** is a **real-time credit underwriting application** built for banking environments.  
It leverages **AI-driven decision-making**, **intelligent OCR-based document analysis**, and a **voice-enabled chatbot** to automate and enhance the loan approval workflow from start to finish.  

---

## ⚙️ Key Features  

### 🧠 Bank-Grade AI Decision Engine  
- **Two-layer logic**:  
  - **Hard Rules Engine** — Instantly rejects high-risk applicants (missed EMIs, poor credit history).  
  - **Random Forest Model** — Predicts loan eligibility using multiple financial and personal features.  

### 🔄 Dynamic AI Training  
- Model automatically retrains on **server startup** using:  
  - Historical loan datasets.  
  - Real-world, live application data.  
- Continuously improves accuracy over time.  

### 🧾 Intelligent Document Analysis (OCR)  
- **OpenCV** for image pre-processing (noise removal, skew correction).  
- **Multi-pass parsing engine** to extract details from:  
  - Aadhaar Cards  
  - Bank Statements  
  - Salary Slips  
- Automatic data verification and fraud detection.  

### 🗣️ Voice-Enabled Chatbot  
- Guides customers through the loan application process.  
- Supports **speech recognition** and **text-to-speech**.  
- Real-time validation and contextual assistance at every step.  

### 📋 End-to-End Workflow  
1. Customer onboarding via chatbot.  
2. Document upload and OCR verification.  
3. AI-driven eligibility prediction.  
4. Admin review and final approval.  
5. Automatic **PDF report generation**.  

---

## 🧰 Technology Stack  

| Category | Technology | Purpose |
|-----------|-------------|----------|
| **Backend** | Python, FastAPI, Socket.IO | High-performance API with real-time capabilities |
| **AI / Data** | Scikit-learn, Pandas, OpenCV | Machine learning and document processing |
| **Database** | SQLModel, SQLite | Lightweight, Pythonic ORM for structured storage |
| **Frontend** | HTML, CSS, Vanilla JavaScript | Clean, fast, and universally compatible UI |

---



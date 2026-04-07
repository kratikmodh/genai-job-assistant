# 🚀 AI Resume Analyzer & Job Assistant (Full Stack GenAI Application)

## 🧠 Overview

This project is a **full-stack AI-powered application** that helps users analyze resumes, evaluate job descriptions, and prepare for interviews using Generative AI.

It demonstrates how to integrate **Large Language Models (LLMs)** into a real-world system with backend APIs, authentication, and document processing.

---

## 🎥 Demo Video

👉 *(https://drive.google.com/file/d/139tW-lea__10fa3t1dulYo-R0ekOn0w6/view?usp=sharing)*

Example:

```md
[Watch Demo](https://drive.google.com/file/d/139tW-lea__10fa3t1dulYo-R0ekOn0w6/view?usp=sharing)
```

---

## 🎯 Problem Statement

Job seekers often struggle with:

* ❌ Identifying skill gaps
* ❌ Preparing for interviews
* ❌ Optimizing resumes for ATS systems

This project solves these challenges using **AI-driven insights and automation**.

---

## ⚙️ Features

* 📄 Resume upload & parsing
* 🧠 AI-based resume analysis
* 📊 Skill gap detection
* 🎤 Interview question generation
* 📑 ATS-friendly resume generation
* 🔐 JWT-based authentication

---

## 🔄 Application Flow

```text
User uploads resume
        ↓
Backend processes file
        ↓
AI analyzes resume content
        ↓
Compares with job description
        ↓
Generates:
- Skill gaps
- Suggestions
- Interview questions
```

---

## 🏗 System Architecture

```text
Frontend (React)
      ↓
Node.js Backend (Express API)
      ↓
AI Layer (LLM API - Gemini / OpenAI)
      ↓
Future Extension:
RAG Pipeline (Context-aware responses)
```

---

## 🤖 AI Capabilities

* Resume evaluation using LLM
* Job description comparison
* Personalized feedback generation
* Dynamic interview question generation

---

## 🔮 Future Enhancements

* 🔍 RAG-based resume querying
* 📚 Chat with documents
* 🔗 Vector database integration (ChromaDB / FAISS)
* 🤖 Multi-model support (OpenAI, Mistral)

---

## 🛠 Tech Stack

* **Frontend:** React.js
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **AI:** Gemini API (replaceable with OpenAI/Mistral)
* **Authentication:** JWT

---

## 📂 Project Structure

```text
project-root/
 ├── frontend/
 │    ├── components/
 │    ├── pages/
 │
 ├── backend/
 │    ├── routes/
 │    ├── controllers/
 │    ├── models/
 │    ├── services/
```

---

## ⚙️ Installation & Setup

### 🔹 Backend

```bash
cd backend
npm install
npm start
```

---

### 🔹 Frontend

```bash
cd frontend
npm install
npm start
```

---

## 📌 Example Use Case

```text
User uploads resume
        ↓
System extracts skills
        ↓
AI compares with job description
        ↓
Generates:
- Skill gap report
- Suggestions
- Interview questions
```

---

## 🧪 Testing

* Use Postman for backend APIs
* Use browser for frontend UI

---

## 🧠 Key Learnings

* Built a full-stack AI application
* Integrated LLM into backend systems
* Implemented authentication & API design
* Designed scalable architecture for AI systems

---

## 🔗 Related Projects

* RAG Backend (Node): <https://github.com/kratikmodh/rag-node-backend>
* RAG Pipeline (Python): <https://github.com/kratikmodh/rag-python-pipeline>

---

## 👨‍💻 Author

Kratik Modh

---

## ⭐ Final Note

This project represents a **real-world AI system architecture**, combining backend engineering, full-stack development, and Generative AI.

It serves as a strong foundation for building **RAG-based and agentic AI systems** in production environments.

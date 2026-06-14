# 🎓 RAG-Based AI Learning System

## Full-Stack Adaptive AI Learning Platform

The RAG-Based AI Learning System is a full-stack adaptive learning and exam preparation platform designed to transform traditional study materials into an interactive and personalized learning experience using Artificial Intelligence.

This project was developed as a final-year Bachelor of Computer Applications (BCA) project and demonstrates the practical implementation of Retrieval-Augmented Generation (RAG), adaptive learning mechanisms, and educational analytics. The system is designed for academic and educational purposes and showcases the integration of Generative AI into modern learning environments.

---

## Project Information

**Project Title:** RAG-Based AI Learning System
**Developed By:** Bhavana K
**Course:** Bachelor of Computer Applications (BCA)
**Institution:** REVA University

---

## Project Objective

Traditional AI chatbots often generate inaccurate responses, lack performance tracking, and fail to provide personalized learning experiences.

The RAG-Based AI Learning System addresses these challenges by:

* Generating responses grounded in uploaded educational content.
* Providing adaptive learning recommendations based on learner performance.
* Tracking student progress through assessments and analytics.
* Enhancing learning outcomes through intelligent educational assistance.

---

## Core Features

### Learning and Assessment

* Upload PDFs, DOCX, PPTX, TXT, and image-based documents.
* AI-generated summaries with adaptive detail levels.
* Automatic MCQ and True/False quiz generation.
* Performance-based learner categorization:

  * Struggling Learner
  * Average Learner
  * Advanced Learner

### Adaptive AI System

* Retrieval-Augmented Generation (RAG) powered question answering.
* Context-aware responses generated from uploaded learning materials.
* Personalized learning recommendations based on quiz performance.
* Homework and concept assistance with guided explanations.

### Analytics Dashboard

* Topic-wise performance analysis.
* Student progress monitoring.
* Learning insights and performance visualization.
* Identification of learners requiring additional support.

### User Experience

* Modern and responsive interface.
* Light and Dark mode support.
* Interactive learning environment.

---

## Technology Stack

### Backend

* Python 3.12
* FastAPI
* Groq LLM API (LLaMA 3.1 Instant)
* ChromaDB
* Hugging Face Embeddings (all-MiniLM-L6-v2)
* SQLite
* Tesseract OCR

### Frontend

* React 18
* Vite
* React Router
* HTML
* CSS
* JavaScript

---

## Project Structure

```text
AI-Tutor-Complete-Final-Year-Project-Kit/

├── Backend/
│   ├── main.py
│   ├── rag.py
│   ├── models.py
│   ├── schemas.py
│   ├── routers/
│   ├── requirements.txt
│   └── .env.example
│
├── Frontend/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

## Local Setup Instructions

### Prerequisites

* Python 3.12+
* Node.js 18+
* Tesseract OCR

---

### Backend Setup

```bash
cd Backend
python -m venv venv
```

Activate Virtual Environment:

**Windows**

```bash
.\venv\Scripts\activate
```

**macOS/Linux**

```bash
source venv/bin/activate
```

Install Dependencies:

```bash
pip install -r requirements.txt
```

Create Environment File:

```bash
cp .env.example .env
```

Add API Key:

```ini
GROQ_API_KEY=your_api_key_here
```

Run Backend:

```bash
uvicorn main:app --reload
```

Backend URL:
http://127.0.0.1:8000

API Documentation:
http://127.0.0.1:8000/docs

---

### Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

Frontend URL:
http://localhost:5173

---

## Docker Deployment (Optional)

```bash
docker-compose up --build
```

Ensure the .env file is configured before deployment.

---

## Environment Variables

Create the following file:

```text
Backend/.env
```

Add:

```ini
GROQ_API_KEY=your_groq_api_key_here
```

Free API keys can be obtained from:
https://console.groq.com

---

## Project Outcomes

* Developed an AI-powered educational assistant using Retrieval-Augmented Generation (RAG).
* Improved response accuracy through document-grounded information retrieval.
* Implemented adaptive learning recommendations based on learner performance.
* Created a modern full-stack web application using FastAPI and React.
* Demonstrated practical application of Generative AI in education technology.

---

## Future Enhancements

* Multi-modal document understanding.
* Advanced AI reasoning capabilities.
* Personalized learning pathways.
* Enhanced analytics and reporting features.
* Mobile application support.

---

## Disclaimer

This project was developed for academic and educational purposes as part of a Bachelor of Computer Applications (BCA) final-year project at REVA University.

---

## Author

**Bhavana K**
BCA Final-Year Student
REVA University

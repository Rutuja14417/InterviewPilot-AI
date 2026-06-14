# 🎯 InterviewPilot AI — Adaptive Engineering Assessor

InterviewPilot AI is an AI-powered technical interview platform that simulates realistic engineering interviews, evaluates candidate responses using Google Gemini, analyzes uploaded resumes, and generates personalized learning roadmaps.

Built with Streamlit and Gemini 2.5 Flash, the platform helps students and aspiring engineers prepare for technical interviews across AI, Machine Learning, Data Science, SQL, and Generative AI domains.

---

## 🚀 Features

### 📄 Resume-Aware Interview Generation
Upload a PDF resume and the system automatically extracts project and skill information to generate personalized interview questions.

### 🧠 AI-Powered Interview Evaluation
Responses are analyzed using Gemini 2.5 Flash and evaluated on:

- Technical Accuracy
- Depth of Understanding
- Communication Quality
- Problem-Solving Approach

### 🎭 Multiple Interview Personas

Choose between different interviewer styles:

- Google Principal Engineer
- Fast-Growing Startup CTO
- Data Science Research Scientist

Each persona adapts question style and evaluation criteria.

### 🎯 Specialized Domain Tracks

Interview simulations are available for:

- Artificial Intelligence & Data Science
- Machine Learning Core
- Data Engineering & SQL
- Generative AI & LLMs

### 📊 Analytics Dashboard

The platform generates:

- Technical Depth Metrics
- Communication Assessment
- Domain Alignment Insights
- Detailed Answer Evaluation

### 🛣️ Personalized Learning Roadmap

After the interview, InterviewPilot AI automatically creates a 30-day improvement plan based on detected knowledge gaps and weak areas.

---

## 🏗️ System Architecture

```text
User Resume (PDF)
        │
        ▼
Resume Parsing Engine (PyPDF)
        │
        ▼
Gemini Question Generator
        │
        ▼
Adaptive Interview Session
        │
        ▼
AI Response Evaluation
        │
        ▼
Performance Analytics
        │
        ▼
30-Day Learning Roadmap
```

---

## 🛠️ Technology Stack

| Layer | Technology |
|---------|------------|
| Frontend | Streamlit |
| Backend | Python |
| AI Model | Gemini 2.5 Flash |
| PDF Processing | PyPDF |
| State Management | Streamlit Session State |

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/InterviewPilot-AI.git
cd InterviewPilot-AI
```

### Install Dependencies

```bash
pip install streamlit google-genai pypdf
```

### Run Application

```bash
streamlit run app.py
```

---

## 🔑 API Configuration

Generate a Gemini API key from:

https://aistudio.google.com/app/apikey

Enter the key in the sidebar before starting an interview session.

---

## 📈 Workflow

1. Upload Resume (Optional)
2. Select Interview Domain
3. Select Interview Persona
4. Generate AI Interview Question
5. Submit Technical Response
6. Receive AI Evaluation
7. View Analytics Dashboard
8. Generate Personalized Learning Roadmap

---

## 🎯 Future Enhancements

- Multi-round interview sessions
- Voice-based interviews
- Coding challenge evaluation
- ATS resume scoring
- Leaderboards and gamification
- Exportable interview reports
- Company-specific interview modes

---

## 👨‍💻 Project Vision

InterviewPilot AI aims to make technical interview preparation more personalized, adaptive, and accessible by combining resume-aware question generation, AI-driven evaluation, and targeted skill development recommendations in a single platform.

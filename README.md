<h1 align="center">🤖 AgentBuilder & Conversational Journey Portal</h1>

<p align="center">
  <b>Visual Workflow Builder for Voice AI Agents, Campaign Orchestration & Live Escalations</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React.js-18+-blue?style=for-the-badge&logo=react" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-Modern_UI-teal?style=for-the-badge&logo=tailwind-css" />
  <img src="https://img.shields.io/badge/FastAPI-Backend_Services-009688?style=for-the-badge&logo=fastapi" />
  <img src="https://img.shields.io/badge/WebSockets-Live_Streaming-black?style=for-the-badge&logo=socket.io" />
</p>

---

## 📌 Overview
**AgentBuilder** is an enterprise visual workflow designer and campaign management portal. It enables teams to configure multi-turn voice and chat AI agent journeys, upload campaign data, schedule intelligent best-time retry logic (+10–15% engagement), and trigger live agent handoffs with full conversation context.

## ✨ Key Features
- **Visual Flow Orchestration:** Drag-and-drop conversational nodes for intent routing, FAQ fallbacks, and multi-turn dialog.
- **Intelligent Batch Scheduling:** Optimizes dispatch based on GPU concurrency limits and best-time pickup predictions.
- **Live Agent Escalation:** Real-time transfer to human agents preserving audio transcripts, disposition history, and sentiment scores.
- **Micro-Frontend Architecture:** Modular, independently deployable components reducing bundle size and release cycles.

## 🛠️ Tech Stack
- **Frontend:** React.js, Tailwind CSS, Lucide Icons, React Flow
- **Backend:** Python, FastAPI, WebSockets, REST APIs
- **Database & Queue:** MySQL, Redis Queue / Celery
- **DevOps:** Docker, AWS ECS

## ⚡ Quick Start

### 1. Clone & Install Frontend
```bash
git clone https://github.com/Gurudass/Agentbuilder.git
cd Agentbuilder
npm install
npm run dev
```

### 2. Backend Setup (if running local API)
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

---

## 👨‍💻 Author
**Guru Das**  
Senior Full-Stack & GenAI Engineer  
- GitHub: [@Gurudass](https://github.com/Gurudass)  
- LinkedIn: [Guru Das](https://linkedin.com)

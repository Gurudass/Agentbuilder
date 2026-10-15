# AgentBuilder & Conversational Journey Portal

**Enterprise Visual Workflow Designer for AI Voice Agents & Campaign Orchestration**

---

### Overview
AgentBuilder is a visual workflow designer and campaign operations portal built for configuring multi-turn voice and chat AI agent interactions. It provides teams with visual drag-and-drop routing, campaign data ingestion, intelligent best-time retry scheduling, and seamless live-agent escalation with full conversation context.

---

### Key Capabilities

* **Visual Flow Design:** Node-based workflow configuration for intent routing, conversational branching, and fallback handling.
* **Batch Scheduling Engine:** Dynamic dispatch respecting GPU concurrency boundaries (500+ concurrent calls) with automated retry queues.
* **Contextual Agent Transfer:** Real-time transfer to human support agents preserving transcripts, sentiment history, and intent classifications.
* **Micro-Frontend Architecture:** Decoupled, independently deployable UI modules reducing bundle size and deployment cycle overhead.

---

### Technical Stack

* **Frontend:** React.js, JavaScript (ES6+), Tailwind CSS, Lucide
* **Backend Services:** Python, FastAPI, WebSockets, REST APIs
* **Database & Queuing:** MySQL, SQLite, Redis Queue
* **Infrastructure:** Docker, AWS ECS

---

### Getting Started

```bash
# Clone and install frontend
git clone https://github.com/Gurudass/Agentbuilder.git
cd Agentbuilder
npm install
npm run dev
```

---

### Author
**Guru Das**  
Senior Full-Stack & Generative AI Engineer  
[GitHub Profile](https://github.com/Gurudass)

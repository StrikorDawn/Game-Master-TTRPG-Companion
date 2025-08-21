# 🎲 Game Master TTRPG Companion
An AI‑assisted web app to help Game Masters run TTRPG sessions with less overhead and better continuity.

Status: In active MVP development

---

## 📖 Overview
The Game Master Companion Tool is a web-based application that helps Game Masters (GMs) manage tabletop role-playing game (TTRPG) sessions with ease.  
It provides AI-assisted transcription and summarization, NPC generation and management, and world organization to reduce admin work and improve continuity between sessions.

This project demonstrates full‑stack software engineering, AI integration, and cloud deployment as a portfolio capstone.

---

## ✨ Features
- AI Transcription & Summarization
  - Upload recorded session audio (live streaming planned) and generate highlights and summaries.
- NPC Generation & Management
  - Create, track, and reuse NPCs across campaigns with optional AI-assisted attributes.
- World Organization & Tracking
  - Store lore, maps, and notes in a structured format for fast retrieval.

---

## 🛠️ Tech Stack
- Frontend: React 18 + TypeScript + Vite, React Router, Tailwind CSS
- Backend: Java 21 + Spring Boot 3 (Web, Data JPA), springdoc‑openapi (Swagger UI)
- Database: PostgreSQL 16, Flyway for migrations
- AI Services: OpenAI API (Whisper for batch transcription, GPT models)
- DevOps: Docker Compose (local Postgres), GitHub Actions CI (build + test)
- Hosting: Render or Fly.io (API), Netlify or Vercel (web)

Why this: Stable, industry‑standard tools that demonstrate end‑to‑end competency without unnecessary complexity.

---

<!-- ## 🚀 Getting Started

### Prerequisites
- Java 21+
- Node.js 20+ and npm
- Docker (recommended for local Postgres)
- OpenAI API key

### Clone
```bash
git clone https://github.com/StrikorDawn/Game-Master-TTRPG-Companion.git
cd Game-Master-TTRPG-Companion
```

### Configuration
Backend (environment variables or application.properties):
```properties
SPRING_DATASOURCE_URL=jdbc:postgresql://localhost:5432/gm_companion
SPRING_DATASOURCE_USERNAME=postgres
SPRING_DATASOURCE_PASSWORD=postgres
OPENAI_API_KEY=sk-...
```

Frontend (.env):
```env
VITE_API_BASE_URL=http://localhost:8080/api
```

### Run the backend
```bash
cd backend
./mvnw spring-boot:run
# Swagger UI (if enabled): http://localhost:8080/swagger-ui.html
```

### Run the frontend
```bash
cd frontend
npm install
npm run dev
# App: http://localhost:5173
```

---

## 🧪 Running Tests
```bash
# Backend (JUnit)
cd backend
./mvnw test

# Frontend (Vitest + React Testing Library)
cd frontend
npm test
```

--- -->

## 📂 Project Structure
```
Game-Master-TTRPG-Companion/
├── backend/          # Spring Boot API
├── frontend/         # React + Vite web app
├── docs/             # Design docs & diagrams
├── .github/          # CI/CD workflows
├── README.md
└── LICENSE
```

---

## 📌 Roadmap
### Phase 1 — Backend Foundations
- [ ] Spring Boot project structure
- [ ] PostgreSQL integration + Flyway migrations
- [ ] REST API endpoints and basic CRUD
- [ ] Backend unit & integration tests

### Phase 2 — Transcription Prototype (Batch)
- [ ] Audio upload handling
- [ ] Transcription service integration (e.g., Whisper)
- [ ] Persist transcript and expose via API
- [ ] AI-generated session summaries

### Phase 3 — Frontend UI/UX
- [ ] React app structure and routing
- [ ] Clean, responsive UI for sessions/NPCs
- [ ] API integration with loading/error states
- [ ] MVP polish

### Phase 4 — Extended Features
- [ ] NPC Generation & Management (CRUD + AI assistance)
- [ ] World & Campaign Organization (maps, notes, lore tracking)
- [ ] Advanced search and AI-context integration

### Phase 5 — Deployment & Showcase
- [ ] Dockerize services
- [ ] Deploy to cloud hosting (AWS/Render/Fly.io)
- [ ] Finalize documentation and create demo video

See the ClickUp Board for detailed progress and status:
https://app.clickup.com/9013562934/v/f/901312048157/90132321355

---

## 🤝 Contributing
This is a personal portfolio project. Feedback is welcome via issues, but external PRs may not be accepted.

## 👤 Author
Taden Marston
- LinkedIn: https://www.linkedin.com/in/tadenmarston/
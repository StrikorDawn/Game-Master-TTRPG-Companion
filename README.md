# 🎲 Game Master TTRPG Companion
**An AI-Powered Assistant for Tabletop Role-Playing Game Masters**

---

## 📖 Overview
The **Game Master Companion Tool** is a web-based application designed to help Game Masters (GMs) manage tabletop role-playing game (TTRPG) sessions with ease.  
It provides **AI-assisted transcription and summarization**, **NPC generation and management**, and **world-building organization** to reduce administrative workload and improve continuity between sessions.  

This project demonstrates full-stack software engineering, AI integration, and cloud deployment, built as a portfolio capstone project.

---

## ✨ Features
- **AI Transcription & Summarization**  
  Live audio transcription of sessions with AI-generated highlights and summaries.

- **NPC Generation & Management**  
  Create, track, and reuse NPCs across campaigns with AI-assisted attributes.

- **World Organization & Tracking**  
  Store lore, maps, and notes in a structured format for fast retrieval and AI-enhanced support.

---

## 🛠️ Tech Stack
- **Frontend:** React (TypeScript), TailwindCSS  
- **Backend:** Java + Spring Boot  
- **Database:** PostgreSQL  
- **AI Services:** OpenAI API (Whisper, GPT models)  
- **Deployment:** Docker + AWS/Render/Fly.io  
- **Version Control:** GitHub (feature-branch workflow)  

---

## 🚀 Getting Started

### Prerequisites
- [Java 17+](https://adoptium.net/)  
- [Node.js & npm](https://nodejs.org/)  
- [PostgreSQL](https://www.postgresql.org/)  
- [Docker](https://www.docker.com/) (optional, for containerized setup)  

### Installation
1. Clone the repository:
   ```bash
    git clone https://github.com/YOUR_USERNAME/Game-Master-TTRPG-Companion.git
    cd Game-Master-TTRPG-Companion
    ```

2. Set up the backend:
   ```bash
    cd backend
    ./mvnw spring-boot:run
    ```

3. Set up the frontend:
   ```bash
    cd frontend
    npm install
    npm start
    ```

4. Access the app at: http://localhost:3000
---

## 🧪 Running Tests
```bash
# Backend (JUnit tests)
cd backend
./mvnw test

# Frontend (Jest tests)
cd frontend
npm test
```
---
## 📂 Project Structure

```
gm-companion-tool/
├── backend/         # Spring Boot backend
├── frontend/        # React frontend
├── docs/            # SRS, design docs, diagrams
├── docker/          # Dockerfiles / docker-compose
├── .github/         # CI/CD workflows
├── README.md        # This file
└── LICENSE
```
---
## 📌 Roadmap
### Phase 1 — Backend Foundations
- [ ] Set up Spring Boot backend project structure  
- [ ] Implement PostgreSQL database integration  
- [ ] Define REST API endpoints and basic CRUD functionality  
- [ ] Add backend unit & integration tests  

### Phase 2 — AI Transcription Prototype
- [ ] Integrate audio input handling  
- [ ] Connect to AI transcription service (e.g., OpenAI Whisper)  
- [ ] Display live transcription output from backend  
- [ ] Add AI-generated session summaries  

### Phase 3 — Frontend UI/UX
- [ ] Set up React frontend project structure  
- [ ] Create clean, responsive UI for transcription tool  
- [ ] Implement API calls to backend  
- [ ] Polish user experience for a minimum viable product (MVP)  

### Phase 4 — Extended Features
- [ ] NPC Generation & Management (CRUD + AI assistance)  
- [ ] World & Campaign Organization (maps, notes, lore tracking)  
- [ ] Advanced search & AI-context integration  

### Phase 5 — Deployment & Showcase
- [ ] Dockerize backend and frontend  
- [ ] Deploy to cloud hosting (AWS/Render/Fly.io)  
- [ ] Finalize documentation & create demo video 

See the [ClickUp Board](https://app.clickup.com/9013562934/v/f/901312048157/90132321355) for detailed progress and Status 

## 👤 Author
Taden Marston
- [LinkedIn](https://www.linkedin.com/in/tadenmarston/)
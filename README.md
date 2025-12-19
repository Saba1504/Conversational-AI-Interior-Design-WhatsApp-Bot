# Conversational-AI-Interior-Design-WhatsApp-Bot

## Features
- Human-like interior designer chatbot
- Session & context persistence
- Admin dashboard for monitoring chats
- Mock WhatsApp-style UI

## Tech Stack
- Frontend: React + Vite + Tailwind
- Backend: FastAPI (Python)
- LLM: OpenAI (configurable)
- Database: SQLite / PostgreSQL

## Session Management
- Sessions resume if inactive < 48 hours
- Context summary stored instead of full chat
- Polite re-confirmation after long gaps

## Running Locally
### Backend
uvicorn app.main:app --reload

### Frontend
npm install
npm run dev

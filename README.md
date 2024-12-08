# YouTube Video Summarizer

An application that takes YouTube videos, transcribes them, and creates AI-powered summaries.

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/admarble/youtube-summarizer.git
cd youtube-summarizer
```

2. Set up backend:
```bash
cd backend
npm install
cp .env.example .env
npm run dev
```

3. Set up frontend:
```bash
cd frontend
npm install
cp .env.example .env
npm run dev
```

4. Access the application:
- Frontend: http://localhost:5173
- Backend API: http://localhost:3000

## Requirements

- Node.js 18+
- MongoDB
- npm or yarn
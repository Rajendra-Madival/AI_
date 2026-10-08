# AIPS – AI Interview Prep Suite

A production-ready AI interview preparation platform that helps job seekers practice mock interviews, improve communication, and build professional resumes.

## Live Demo

Local demo: http://localhost:3000

## Overview

This project combines a modern frontend and a scalable backend to deliver an interactive interview preparation experience. It includes resume analysis, mock interview flow, study modules, and AI-powered Q&A generation.

## Problem

Candidates often struggle to prepare for technical interviews because they need structured guidance, realistic practice, and consistent feedback across multiple areas.

## Solution

The app provides a guided interview experience with AI-driven questions, a dashboard for tracking performance, and a study roadmap to help users improve step by step.

## Features

- AI mock interview chat
- Resume builder and dashboard
- Interview Q&A generator
- Study roadmap module
- Responsive cyber-themed UI

## Tech Stack

- Next.js
- FastAPI
- SQLite
- Gemini AI
- Tailwind CSS
- Recharts

## Architecture

Frontend UI -> API layer -> AI service -> SQLite data store

## Project Structure

```text
AI_/
├── frontend/
├── backend/
├── README.md
└── package.json / requirements.txt
```

## Getting Started

```bash
# Frontend
cd frontend
npm install
npm run dev

# Backend
cd backend
pip install -r requirements.txt
uvicorn main:app --reload --port 8000
```

## Screenshots

Add screenshots of the dashboard, mock interview flow, and resume builder here.

## Challenges

- Integrating the AI API reliably
- Designing a modern and intuitive UI
- Creating a smooth interview experience

## What I Learned

- Full-stack app structure
- Prompt engineering with AI APIs
- Frontend/backend integration and deployment preparation

## Future Improvements

- Real-time collaboration
- Interview analytics dashboard
- Better resume insights and scoring

## Author

Rajendra M Madival

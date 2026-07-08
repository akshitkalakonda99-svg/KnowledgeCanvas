# KnowledgeCanvas

> Transform scattered online content into a searchable AI-powered knowledge base.

## Overview

KnowledgeCanvas is an AI-powered personal knowledge operating system designed to help users save, organize, and learn from the educational content they consume online.

The MVP focuses on Instagram carousel images, converting them into structured notes using OCR and AI.

Long-term, the platform will support PDFs, YouTube videos, articles, research papers, LinkedIn posts, X (Twitter) threads, and more.

---

## Features (MVP)

- Upload Instagram carousel images
- OCR-based text extraction
- AI-generated summaries
- Key insights & action items
- Automatic tag generation
- Save notes to a personal knowledge library
- Search saved notes

---

## Tech Stack

### Frontend
- Next.js
- React
- TypeScript
- Tailwind CSS

### Backend
- FastAPI

### Database
- PostgreSQL
- pgvector

### AI
- OpenAI API

### Deployment
- Vercel
- Railway / Render

---

## Project Architecture

```
Frontend
    ↓
FastAPI Backend
    ↓
OCR → LLM → Embeddings
    ↓
PostgreSQL + pgvector
```

---

## Current Status

🚧 MVP in Development

Current focus:
- Upload pipeline
- OCR
- AI processing
- Note storage

---

## Future Features

- Semantic Search
- Chat with Notes (RAG)
- PDF Support
- YouTube Support
- Flashcards
- Quizzes
- Mind Maps
- Knowledge Graph

---

## Screenshots

> Screenshots will be added as development progresses.

- Landing Page
- Upload Page
- Processing Screen
- Notes Dashboard
- Search Interface

---

## Development Philosophy

- Ship fast.
- Keep the architecture clean.
- Build incrementally.
- Focus on solving a real problem.
- Prioritize maintainability over complexity.

---

## Author

Built as a portfolio project with the vision of evolving into a complete AI-powered second brain.

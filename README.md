# Cleriva

AI-powered coaching and conversational platform built with a scalable Retrieval-Augmented Generation (RAG) architecture.

## Overview

Cleriva is a full-stack AI platform designed to deliver intelligent contextual conversations using modern GenAI infrastructure.

The system combines:
- Conversational AI
- Retrieval-Augmented Generation (RAG)
- Streaming responses
- Async workflows
- Persistent chat sessions
- Semantic document retrieval

The architecture is split into independent services for scalability and maintainability.

---

# Architecture
![Cleriva Architecture](docs/cleriva_arch.jpg)
```text
User
  ↓
Frontend (React)
  ↓
Backend API (Node.js/Express)
  ↓
RAG Service (FastAPI/LangChain)
  ↓
Vector Retrieval + LLM
```

---

# Repository Structure

```text
cleriva/
│
├── frontend/       # React frontend application
├── backend/        # Express backend API
├── rag-service/    # FastAPI RAG microservice
│
└── README.md
```

---

# Core Features

## AI Coaching Conversations
- Context-aware AI chat experience
- Persistent sessions and message history
- Streaming AI responses for low latency UX

## Retrieval-Augmented Generation (RAG)
- Document upload and ingestion pipeline
- Intelligent chunking and embeddings
- Semantic retrieval with reranking
- Context injection for grounded AI responses

## Authentication & Persistence
- User authentication with Supabase
- PostgreSQL-backed chat/session storage

## Async Processing
- Event-driven workflows using Inngest
- Background processing for ingestion and AI tasks

## Scalable Service Architecture
- Independent frontend, backend, and RAG services
- Microservice-oriented design for modular scaling

---

# Tech Stack

## Frontend
- React
- Tailwind CSS

## Backend
- Node.js
- Express.js

## AI / RAG Service
- FastAPI
- LangChain
- Azure OpenAI

## Database & Infrastructure
- Supabase
- PostgreSQL
- Inngest

---

# Services

## Frontend
GitHub:
https://github.com/hhshah2809/cleriva-frontend

---

## Backend
GitHub:
https://github.com/hhshah2809/cleriva_backend

---

## RAG Service
GitHub:
https://github.com/hhshah2809/cleriva_rag_service

---

# Future Improvements

- Multi-agent orchestration
- Advanced memory systems
- Multi-document retrieval
- Hybrid search
- Dockerized deployment
- Observability and tracing
- Role-based access control

---

# Key Engineering Concepts

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Vector Embeddings
- Async Event Processing
- Streaming Architectures
- Microservices
- AI Orchestration
- Contextual AI Systems

---

# Author

HET SHAH

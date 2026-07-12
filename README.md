# AI Resume Analyzer

An AI-powered Resume Analyzer built using Spring Boot, React, PostgreSQL, GraphQL, and Local LLMs through LM Studio.

The application extracts candidate information from resumes, stores candidate profiles, generates embeddings, and matches candidates against job requirements using AI-powered semantic matching.

---

## Features

- Upload resumes in PDF and DOCX format
- AI-powered candidate information extraction
- Automatic skill and experience detection
- Job requirement creation and management
- Candidate-to-job matching using AI
- Semantic search using vector embeddings
- JWT Authentication and Role-Based Access Control (RBAC)
- Candidate profile enrichment using GitHub and LinkedIn
- GraphQL APIs for frontend communication
- Real-time upload tracking

---

## Tech Stack

### Backend
- Java 25
- Spring Boot 3
- Spring AI
- Spring Security
- GraphQL
- PostgreSQL
- JPA/Hibernate

### Frontend
- React
- TypeScript
- Redux Toolkit
- Redux Saga
- Vite

### AI Stack
- LM Studio
- Mistral 7B Instruct
- Nomic Embed Text Embedding Model
- Vector Embeddings

---

## System Architecture

```text
Resume Upload
      ↓
Text Extraction
      ↓
LLM Analysis
      ↓
Candidate Creation
      ↓
Embedding Generation
      ↓
PostgreSQL Storage
      ↓
Job Matching
      ↓
AI Match Score

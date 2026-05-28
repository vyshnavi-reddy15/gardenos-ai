# GardenOS AI

AI-powered gardening memory and advisory platform designed for Indian home gardeners.

GardenOS AI combines modern AI workflows, structured plant tracking, and RAG-ready architecture to help users manage gardening activities, monitor plant health, and access contextual gardening insights through an intelligent assistant.

The platform is built using a scalable full-stack architecture with FastAPI, Next.js, PostgreSQL, ChromaDB, and Docker-based local development.

---

# Features

* AI-powered gardening assistant
* Plant and garden activity tracking
* Event scheduling and reminders
* RAG-ready architecture for contextual gardening advice
* Modular agent and service layer design
* Dockerized full-stack environment
* REST API-based backend architecture
* ChromaDB integration for future semantic retrieval workflows

---

# Tech Stack

## Backend

* FastAPI
* Python 3.11
* SQLAlchemy
* Alembic
* PostgreSQL

## Frontend

* Next.js
* TypeScript
* Tailwind CSS

## AI & Data

* OpenAI-compatible LLM client
* ChromaDB
* Retrieval-Augmented Generation (RAG) ready structure

## DevOps

* Docker
* Docker Compose

---

# Architecture Overview

```text
Frontend (Next.js)
        ↓
FastAPI Backend
        ↓
Service Layer / Agents
        ↓
PostgreSQL + ChromaDB
        ↓
LLM & RAG Pipelines
```

---

# Repository Structure

```text
backend/
  app/
    api/
    agents/
    services/
    rag/
    models/
    schemas/
    db/
    core/

frontend/
  src/app/

data/
  gardening_knowledge/

docker-compose.yml
```

---

# Current Capabilities

Implemented:

* Plant CRUD APIs
* Garden event management APIs
* FastAPI backend architecture
* PostgreSQL integration
* ChromaDB setup
* Dockerized development environment
* AI service and agent boundaries
* Frontend dashboard foundation
* Health monitoring endpoints

Planned:

* Authentication
* Embedding pipelines
* AI memory workflows
* Personalized gardening recommendations
* Production deployment infrastructure

---

# Local Development

## Start Full Stack

```bash
docker compose up --build
```

---

# Application Services

| Service                       | Description                                      |
| ----------------------------- | ------------------------------------------------ |
| Frontend Application          | User interface and dashboard workflows           |
| Backend API Service           | FastAPI-powered backend and application logic    |
| Interactive API Documentation | OpenAPI / Swagger API interface                  |
| ChromaDB Vector Service       | Vector database for semantic retrieval workflows |

---

# Development Stack

The application runs as a containerized multi-service architecture using Docker Compose, including:

* Next.js frontend
* FastAPI backend
* PostgreSQL database
* ChromaDB vector store
* AI service layer and agent workflows

---

# Backend Architecture

The backend follows a modular service-oriented structure with dedicated layers for:

* API routing
* Business logic
* AI agent workflows
* Retrieval pipelines
* Database models
* Vector storage integration

---

# AI & RAG Foundation

GardenOS AI includes an extensible AI architecture designed for future:

* semantic search workflows
* contextual gardening memory
* intelligent recommendations
* retrieval-augmented generation (RAG)
* conversational AI experiences


---

## Garden Calendar

Interactive gardening calendar for tracking schedules, reminders, tasks, and seasonal activities.

Features:

* Task scheduling
* Reminder tracking
* Journal integration
* Seasonal gardening workflows

![Garden Calendar](images/calendar.png)

---

## Plant Management

Dedicated plant tracking system for maintaining plant details, notes, locations, and activity history.

Features:

* Plant CRUD operations
* Botanical information
* Location tracking
* Plant-specific notes
* Event association

![Plant Management](images/plants.png)

---

## Gardening Journal

Structured journaling workflow for recording plant observations, growth updates, and gardening history.

Features:

* Timeline-based journal entries
* Plant-linked observations
* Editable note history
* Growth tracking workflows

![Journal](images/journal.png)

---

## Seasonal Insights System

Context-aware seasonal gardening recommendations tailored for Indian gardening conditions.

Features:

* Seasonal crop recommendations
* Blooming guidance
* Harvest tracking
* Weather-aware workflows
* Seasonal reminders

![Seasonal Insights](images/seasonal-insights.png)

---

## AI Gardening Assistant – Sprout

Integrated AI assistant designed to provide contextual gardening recommendations using conversational workflows and future RAG-ready architecture.

Capabilities:

* Plant care recommendations
* Symptom-based guidance
* Seasonal advice
* Watering recommendations
* Context-aware gardening support

![AI Assistant](images/ai-chat.png)

---

## Contextual AI Recommendations

The assistant generates structured gardening guidance using contextual plant data, reminders, seasonal information, and gardening memory workflows.

Example capabilities:

* Plant health diagnosis
* Watering optimization
* Seasonal planning
* Soil and nutrient recommendations

![AI Recommendations](images/ai-recommendations.png)

```
```

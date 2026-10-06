<div align="center">

# Hey, I'm Amulya 👋

### Software Engineer · Python & Backend Systems · Reliability Engineering

*Building backend systems that are reliable, testable, observable, and built to handle real-world failure cases.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kokkula-amulya-8176382a5/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AmulyaK4)
[![HackerRank](https://img.shields.io/badge/HackerRank-2EC866?style=flat-square&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/amulyaakokkula)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:amulyaakokkula@gmail.com)

</div>

---

## 🧬 About Me

I'm a B.Tech Information Technology graduate from Hyderabad interested in **backend engineering, reliability, distributed systems, and infrastructure**.

My strongest experience is with **Python, FastAPI, REST APIs, PostgreSQL, Redis, Docker, SQL, and automated testing**. During my software engineering internship, I worked with application data and backend systems, built monitoring dashboards for API latency and error rates, investigated data inconsistencies, and supported debugging and resolution of software issues.

I enjoy understanding what happens when systems are under pressure — concurrent requests, race conditions, stale state, failed requests, inconsistent data, and the edge cases that don't appear in a simple happy-path test.

### Currently focused on

- Backend & API engineering
- Reliability and debugging
- Distributed and concurrent systems
- Databases and data consistency
- Linux & systems fundamentals
- Containers and deployment
- Automated testing
- Cloud-native infrastructure

---

## ⚙️ Featured Engineering Projects

### 🎟️ Real-Time Event Booking Platform

**Concurrent booking system designed around consistency, race conditions, and real-time updates.**

- Built a full-stack event booking platform using **FastAPI, PostgreSQL, Redis, React, and WebSockets**.
- Implemented **row-level database locking** to serialize competing booking requests and prevent double-booking.
- Added **Redis TTL-based seat holds** with automatic expiration to prevent stale reservations.
- Used **WebSockets** to broadcast seat availability changes in real time.
- Tested concurrent requests to identify and resolve race-condition scenarios.
- Containerized the application using **Docker Compose**.

`Python` `FastAPI` `PostgreSQL` `Redis` `WebSockets` `Docker` `React`

→ **[Code](https://github.com/AmulyaK4/Real-Time-Event-Booking-Platform)**

---

### 🛠️ OpsPilot — AI Operations Copilot

**Backend system for operational workflows, API integrations, and automated testing.**

- Built Python/FastAPI REST APIs for **customer search, order tracking, refund checks, and support workflows**.
- Implemented **JWT authentication** and persistent conversations.
- Added controlled backend tool-calling workflows for interacting with application services.
- Wrote **automated pytest tests** to detect regressions and improve backend reliability.
- Used PostgreSQL/pgvector for persistent application data.
- Dockerized the application for reproducible development and deployment.

`Python` `FastAPI` `PostgreSQL` `pytest` `REST APIs` `Docker`

→ **[Code](https://github.com/AmulyaK4/OpsPilot)**

---

### 🎯 HireMatch AI

**AI-powered resume screening system with a production-style application workflow.**

- Built an end-to-end application using **Python, Streamlit, LangChain, Groq, FAISS, and sentence-transformers**.
- Implemented document processing, embeddings, vector search, and structured resume/JD analysis.
- Containerized the application using Docker.
- Deployed the application through Hugging Face Spaces.

`Python` `LangChain` `FAISS` `Docker` `LLMs`

→ **[Live Demo](https://amulya8-hirematch-ai.hf.space)** · **[Code](https://github.com/AmulyaK4/hirematch-ai)**

---

### 📄 ResuméLens

**LLM-powered resume analysis application with structured API-style output handling.**

- Built a Next.js application for ATS-style resume analysis.
- Implemented structured LLM responses with schema validation and re-prompting for malformed output.
- Designed the application so uploaded resumes are processed in memory rather than persistently stored.

`Next.js` `LangChain` `Groq`

→ **[Live Demo](https://resumelens-eta.vercel.app)** · **[Code](https://github.com/AmulyaK4/ResumeLens)**

---

### 👁️ InsightLense

**Document intelligence and retrieval system for research documents containing text, tables, and figures.**

- Built a RAG pipeline combining **FAISS and BM25 retrieval**.
- Used Gemini Vision and LlamaParse to process figures, diagrams, and structured tables.
- Developed a FastAPI backend for document-processing workflows.

`Python` `FastAPI` `FAISS` `BM25` `LangChain`

→ **[Code](https://github.com/AmulyaK4/InsightLense-Research-Document)**

---

## 🛠️ Technical Stack

```yaml
languages:
  - Python
  - SQL
  - Java
  - JavaScript

backend:
  - FastAPI
  - REST APIs
  - SQLAlchemy
  - Pydantic

databases:
  - PostgreSQL
  - MySQL
  - Redis
  - pgvector

reliability:
  - Debugging
  - Root-Cause Analysis
  - API Monitoring
  - Error Analysis
  - Data Integrity
  - Performance Analysis
  - Concurrent Systems

testing:
  - pytest
  - Unit Testing
  - API Testing
  - Postman

systems:
  - Linux
  - Operating Systems
  - Computer Networks
  - DBMS
  - DSA
  - OOP

containers_and_tools:
  - Docker
  - Docker Compose
  - Git
  - GitHub
  - Metabase
  - VS Code

ai_ml:
  - LangChain
  - FAISS
  - sentence-transformers
  - scikit-learn
  - XGBoost



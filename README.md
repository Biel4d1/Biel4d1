Hi, I'm Gabriel Querne 👋

Data Science Student | Backend & Data Engineering | Go • Python • PostgreSQL • Linux

I build backend systems, automated data pipelines, and data-driven applications, with a focus on reliability, concurrency, asynchronous processing, and practical infrastructure.

My projects explore the intersection of Data Engineering, Backend Development, Machine Learning, and Linux automation — from real-time Go services and procedural audio DSP to multimodal recommendation pipelines and automated meteorological ETL.

Currently focused on Go, Python, PostgreSQL, Redis, Docker, Linux infrastructure, and applied AI systems.

---

🛠️ Technical Stack

Languages

- Go (Golang)
- Python
- SQL
- Bash / Zsh

Backend & Data

- REST APIs
- PostgreSQL / pgvector
- SQLite
- Redis
- ETL / ELT pipelines
- Background workers & message queues
- Semantic vector search
- Data ingestion and transformation

Infrastructure

- Linux (Arch Linux)
- Docker & Docker Compose
- systemd services & timers
- Git / GitHub
- SSH
- Automated service orchestration

Machine Learning & AI

- Scikit-learn
- CLIP multimodal embeddings
- Audio Spectrogram Transformer (AST)
- k-Nearest Neighbors
- Vector similarity search
- Recommendation systems
- Generative AI workflows

Analytics

- Power BI Desktop / Service
- DAX
- Star Schema modeling
- Data transformation

Languages

- 🇧🇷 Portuguese — Native
- 🇬🇧 English — Fluent, including technical documentation

---

🚀 Featured Engineering Projects

🔥 "FireApp / SmartVideos" (https://github.com/Biel4d1/FireApp)

Polyglot Backend & Multimodal Recommendation Pipeline

A video platform backend combining a high-throughput Go/Gin API with asynchronous Python machine-learning workers.

Architecture

- Go REST API for application and backend services
- PostgreSQL + "pgvector" for persistent vector storage
- Redis-backed asynchronous task processing
- Python ML workers for media analysis
- Docker Compose for multi-service orchestration

Machine Learning Pipeline

- Generates 512-dimensional CLIP embeddings using "clip-vit-base-patch32"
- Extracts audio information using Audio Spectrogram Transformer (AST)
- Stores semantic representations in PostgreSQL
- Performs vector similarity retrieval for recommendation and discovery

Engineering focus:
"Go" · "Python" · "PostgreSQL" · "pgvector" · "Redis" · "Docker" · "ML Pipelines" · "Vector Search"

---

🎵 "goTunes" (https://github.com/Biel4d1/goTunes)

Real-Time Procedural Audio Synthesis Engine in Go

A real-time procedural music engine written in Go, generating continuous synthesized audio without relying on prerecorded PCM samples.

Built around "ebitengine/oto/v3", the engine explores low-latency DSP, deterministic sequencing, concurrency, and long-running audio generation.

Technical highlights

- Real-time procedural audio synthesis
- Concurrent shared-state management
- HTTP control endpoints
- Multi-oscillator synthesis
- Procedural harmonic and rhythmic generation
- Bounded floating-point clocks using modulo arithmetic
- Allocation and latency benchmarking for real-time execution

Engineering focus:
"Go" · "Concurrency" · "DSP" · "Real-Time Systems" · "Performance Engineering"

---

🌦️ "Localized Meteorological ETL Pipeline" (https://github.com/Biel4d1/Weather-Pipeline)

Automated Weather Data Ingestion & Transformation

A lightweight ETL pipeline for continuously collecting, validating, transforming, and storing meteorological telemetry from external REST APIs.

Rather than relying on a large orchestration framework, execution is handled directly by Linux systemd services and timers.

Pipeline

External REST API
        │
        ▼
 JSON Telemetry
        │
        ▼
Python / Pandas
        │
   Validation
   Cleaning
   Transformation
        │
        ▼
     SQLite
        │
  Idempotent Writes
        │
        ▼
 Historical Dataset

Technical highlights

- Automated API ingestion
- Structured JSON transformation
- Idempotent persistence with "INSERT OR IGNORE"
- Persistent historical datasets
- systemd-based scheduling and orchestration
- Lightweight deployment without external workflow engines

Engineering focus:
"Python" · "Pandas" · "SQLite" · "REST APIs" · "ETL" · "Linux" · "systemd"

---

📐 "Music Emotion Engine" (https://github.com/Biel4d1/music-recommendation-pipeline)

Emotion-Aware Recommendation & Spatial Inference Pipeline

A machine-learning pipeline that represents music in a multidimensional emotional space based on the Russell Circumplex Model of Affect.

Audio characteristics are normalized and mapped into a three-dimensional feature space, where k-Nearest Neighbors and Euclidean distance are used for similarity-based classification and recommendation.

Audio Features
      │
      ▼
Data Transformation
      │
      ▼
 MinMaxScaler
      │
      ▼
3D Emotional Vector Space
      │
      ▼
 Euclidean Distance
      │
      ▼
     k-NN
      │
      ▼
Emotion / Similarity Results

Engineering focus:
"Python" · "Scikit-learn" · "Feature Engineering" · "k-NN" · "Data Pipelines"

---

💼 "Family Finance Ledger" (https://github.com/Biel4d1/family-finance)

Local-First Desktop Financial Management System

A full-stack financial tracking application built around a Go business-logic layer and relational PostgreSQL persistence.

The application uses Wails v2 to expose Go backend functionality through a native desktop interface.

Technical highlights

- Go application/service layer
- PostgreSQL relational persistence
- Income and expense tracking
- Financial aggregation and calculations
- Local-first architecture
- Native desktop integration with Wails

Engineering focus:
"Go" · "PostgreSQL" · "Wails" · "SQL" · "Desktop Applications"

---

🏗️ Engineering Ecosystem

                    ┌──────────────────────────┐
                    │   DATA & BACKEND SYSTEMS │
                    └────────────┬─────────────┘
                                 │
          ┌──────────────────────┼──────────────────────┐
          │                      │                      │
          ▼                      ▼                      ▼
 ┌────────────────┐    ┌─────────────────┐    ┌─────────────────┐
 │ DATA PIPELINES │    │ AI & ANALYTICS  │    │ BACKEND SYSTEMS │
 └───────┬────────┘    └────────┬────────┘    └────────┬────────┘
         │                      │                      │
         ▼                      ▼                      ▼
 Weather Pipeline           FireApp                goTunes
 Python / Pandas        CLIP / AST / pgvector     Go / DSP
 systemd / SQLite       Redis / PostgreSQL        Concurrency

         │                      │                      │
         └──────────────────────┼──────────────────────┘
                                ▼
                     ┌────────────────────┐
                     │ APPLIED SYSTEMS    │
                     └─────────┬──────────┘
                               │
                    ┌──────────┴──────────┐
                    ▼                     ▼
            Music Emotion Engine    Family Finance
              ML / k-NN / Math      Go / PostgreSQL

---

🎯 What I'm Looking For

I'm currently interested in opportunities involving:

- Data Engineering
- Backend Development
- Data Science / Applied Machine Learning
- Infrastructure & Automation
- AI-assisted workflow automation

I particularly enjoy engineering problems involving data movement, concurrency, automation, system architecture, recommendation systems, and performance optimization.

📍 Available for hybrid or on-site opportunities in Rio das Ostras, Macaé, and nearby regions in Rio de Janeiro, Brazil.

---

📫 Connect

LinkedIn: "linkedin.com/in/gabriel-querne-a9363941b" (https://www.linkedin.com/in/gabriel-querne-a9363941b/)
GitHub: "github.com/Biel4d1" (https://github.com/Biel4d1)

---

«Building systems is how I learn: design the architecture, implement it, measure it, break it, and improve it.»
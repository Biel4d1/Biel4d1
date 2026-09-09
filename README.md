# Hi, I'm Gabriel Querne! 👋

### Data Science Student & Backend Infrastructure / Data Engineer
I specialize in designing low-latency backend architectures, building production-grade data pipelines (ETL), and deploying asynchronous automated systems utilizing custom Generative AI frameworks, Vector Databases, and microservices.

---

## 🛠️ Technical Stack & Ecosystem

* **Languages:** Go (Golang), Python, SQL (PostgreSQL, SQLite3), Bash/Zsh
* **Data Engineering:** Ingestion Pipelines, REST APIs, Semantic Vector Search, Event Synchronization
* **Infrastructure & Automation:** Linux (Arch), Native Orchestration (systemd Services/Timers), Docker & Compose, Git/SSH
* **Asynchronous Architectures:** Message queues, background workers, and atomic caching via Redis
* **Data Analytics:** Power BI (Desktop/Services), Advanced DAX Functions, Star Schema Modeling
* **Languages:** Fluent English (Proficient in technical documentation) | Portuguese (Native)

---

## 🚀 Architectural Breakdown & Ecosystem Hub

My public repositories act as an integrated, multi-tier software ecosystem demonstrating end-to-end data systems engineering:

---

┌─────────────────────────────────────────┐│        DATA SYSTEMS ECOSYSTEM           │└────────────────────┬────────────────────┘│┌─────────────────────────────┼─────────────────────────────┐▼                             ▼                             ▼┌───────────────┐             ┌───────────────┐             ┌───────────────┐│   INGESTION   │             │   ANALYTICS   │             │ CONCURRENCY & ││  & TELEMETRIA │             │  & SE-MANTICS │             │  CORE BACKEND │└───────┬───────┘             └───────┬───────┘             └───────┬───────┘│                             │                             │[Weather-ETL]               [FireApp / ML Engine]             [goTunes Engine]• REST API Payloads         • Multimodal Embeddings           • Real-Time Audio DSP• systemd Orchestration     • pgvector DB Spatial Search      • Bounded Floating Clocks• Idempotent SQLite         • 3D Vector Space (k-NN)          • Zero-Heap Benchmarks
---

## 📁 Pinned Production-Ready Repositories

### 🔥 [FireApp (SmartVideos) — Polyglot Microservices & AI Pipeline](https://github.com/Biel4d1/FireApp)
* **The System:** A polyglot backend combining a high-throughput **Go (Gin)** API engine with asynchronous **Python** deep learning workers.
* **The AI Stack:** Processes raw media assets to generate 512-dimensional multimodal **CLIP embeddings** (`clip-vit-base-patch32`) and Audio Spectrogram Transformer (AST) tags, utilizing **PostgreSQL (`pgvector`)** for semantic recommendations.
* **The Architecture:** Leverages **Redis (RQ Engine)** background queues to ensure non-blocking threads, alongside custom containerization layers built with **Docker Compose**.

### 🎵 [goTunes — Real-Time Procedural Synthesis Engine](https://github.com/Biel4d1/goTunes)
* **The System:** A low-latency, real-time procedural audio synthesis backend written natively in **Go** using ebitengine/oto/v3.
* **The Engineering:** Implements strict multi-threaded concurrent state management over custom HTTP REST endpoints, utilizing bounded modulo arithmetic (`math.Mod`) to eliminate floating-point counter drift during long-running streaming cycles. Focuses heavily on optimized **zero-heap allocation** benchmarks to avoid Garbage Collector spikes.

### 🌦️ [Localized Meteorological ETL Pipeline](https://github.com/Biel4d1/Weather-Pipeline)
* **The System:** An automated, production-grade data pipeline designed to pull, sanitize, and transform real-time JSON telemetry payloads from external REST APIs.
* **The Automation:** Bypasses heavy framework layers by implementing lightweight **Python (Pandas)** ingestion modules handled entirely through native **Linux `systemd` timers** and persistent, idempotent **SQLite3** engines (`INSERT OR IGNORE`).

### 📐 [Music Emotion Engine & Recommendation Pipeline](https://github.com/Biel4d1/music-recommendation-pipeline)
* **The System:** An end-to-end Machine Learning data engine implementing spatial inference math.
* **The Mathematics:** Maps audio data onto the Russell Circumplex Model of Affect, applying `MinMaxScaler` normalization to execute **k-Nearest Neighbors (k-NN)** spatial classification using geometric Euclidean distances inside a 3D vector space.

### 💼 [Family Finance Ledger — Desktop & Local-First Full-Stack](https://github.com/Biel4d1/family-finance)
* **The System:** A full-stack application bundling desktop client layers and web server logic.
* **The Architecture:** Built with a **Go** business logic layer connected to a **PostgreSQL** relational database engine, exposed as a native Linux/desktop GUI utilizing the **Wails v2** framework shell.

---

## 🎯 Current Target & Availability
* **Core Focus:** Scaling automated corporate workflows through structured **Generative AI & Advanced Prompt Engineering**.
* **Availability:** Full flexibility for hybrid or on-site routines in Rio das Ostras, Macaé, and neighboring operations right away.

📬 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/gabriel-querne-a9363941b)
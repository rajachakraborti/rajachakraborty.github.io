# Hi there, I'm Raja Chakraborty 👋 

### Senior Systems & Backend Engineer | IEEE Senior Member

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raja-chakraborty-203b3a115/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rajachakraborti)
[![IEEE](https://img.shields.io/badge/IEEE-Senior_Member-00629B?style=for-the-badge&logo=ieee&logoColor=white)](https://www.ieee.org/)

---

## 🚀 About Me

I am a **Senior Systems Architect and Tech Lead** with 10 years of production experience designing, constructing, and scaling high-throughput distributed systems, real-time streaming engines, and AI developer infrastructure. 

I focus on turning complex, inexplicable distributed systems into transparent, metrics-driven production platforms. My work leverages fine-grained developer telemetry and business metrics to provide operational clarity, defend architectural choices with empirical data, and align engineering execution directly with business outcomes.

* 🎓 **M.S. in Data Science** (In Progress) — Grand Canyon University | **B.Tech in IT** — JGEC
* 🏆 **IEEE Senior Member** | Technical Judge — Globee Awards 2025 & Codie Awards 2025 | Peer Reviewer — EDAS / DESE2025
* ⚡ **Core Strengths**: Distributed Architecture, Event-Driven Pipelines, PySpark Lakehouse Pipelines, Vector DB Search, Model Context Protocol (MCP) Servers, LLM Request Routing, Low-Uniform Latency SLA Defense, and TDD

---

## 🛠️ Technical Stack & Tooling

| Category | Technologies |
| :--- | :--- |
| **Languages** | `Java` `Python` `TypeScript` `JavaScript` `SQL` `HTML5/CSS3` |
| **Frameworks & Runtimes** | `Node.js` `FastAPI` `Spring Boot` `Express` `React` `Next.js` |
| **Distributed Data & AI** | `PySpark DataFrames` `PyTorch Embeddings` `ChromaDB` `Apache Kafka` `Kafka Streams` `AWS Step Functions` `WebSockets` `WASM` |
| **Cloud & IaC** | `GCP (Cloud Run v2, Vertex AI, Firestore, GCS)` `AWS (Lambda, ECS, EKS, CloudWatch, S3, SQS, SNS)` `Pulumi (Python)` `Docker` `Terraform` |
| **Databases & Warehouses** | `PostgreSQL` `GCP Firestore` `Snowflake` `Redis` `Oracle` `DynamoDB` `RocksDB` `Cassandra` |
| **Observability & Metrics** | `New Relic` `Datadog` `Prometheus` `Grafana` `OpenTelemetry` `TDD` `Slack Webhook Alerts` |

---

## 💻 Featured Open-Source & Portfolio Projects

### 🚀 [RAG-Lakehouse — Distributed Data Pipeline & GCP LLM Engine](https://github.com/rajachakraborti/rag-lakehouse)
**Enterprise RAG Platform & Serverless GCP AI Infrastructure** *(PySpark, PyTorch, ChromaDB, GCP Cloud Run v2, GCP Vertex AI / Gemini 1.5, Pulumi IaC, MCP 2.x)*
* **Distributed Lakehouse Pipeline**: Uses PySpark DataFrames for multi-document chunking and native PyTorch 384-dim dense vector embedding generation.
* **Multi-Tier Distributed Idempotency Cache**: Built a 4-layer SHA-256 checksum deduplication cache (RAM, GCP Firestore, Redis, SQLite) ensuring sub-millisecond duplicate rejection ($O(1)$) across container recycles.
* **Honest RAG Zero-Hallucination Guard**: Implements strict vector match filtering and chunk deduplication (`rag_engine.py`) to eliminate pre-canned fallback hallucinations.
* **Heuristic Model Router & Anti-Burst Protection**: Dynamically routes complex queries to **Gemini 1.5 Pro** vs low-latency queries to **Gemini 1.5 Flash** with dual-threshold sliding window rate limiting.
* 🌐 **Live Web UI**: [rajachakraborti.github.io/rag-lakehouse](https://rajachakraborti.github.io/rag-lakehouse/)
* ⚡ **Live API Gateway**: [rag-lakehouse-1089897614691.us-central1.run.app](https://rag-lakehouse-1089897614691.us-central1.run.app)
* 📂 **Source Code**: [rajachakraborti/rag-lakehouse](https://github.com/rajachakraborti/rag-lakehouse)

---

### 🩺 [Telehealth Hypertension Analytics](https://telehealth-hypertension-analytics-v.vercel.app/login)
**Remote Patient Monitoring & Telemetry Platform** *(FastAPI, React, Python Data Analytics)*
* Ingests, cleans, and analyzes patient health telemetry data to calculate real-time trend indicators and risk classifications.
* Built a high-performance FastAPI backend and responsive React frontend dashboard deployed on Vercel.
* 🌐 **Live Demo**: [telehealth-hypertension-analytics-v.vercel.app](https://telehealth-hypertension-analytics-v.vercel.app/login) (Credentials: `admin` / `admin123`)
* 📂 **Source Code**: [rajachakraborti/telehealth-hypertension-analytics-vercel](https://github.com/rajachakraborti/telehealth-hypertension-analytics-vercel)

---

### 🤖 Custom Model Context Protocol (MCP) Load Test Analytics Server
**AI Developer Tooling & Telemetry Bridge** *(Python, TypeScript, MCP SDK)*
* Built a custom MCP server to surface load testing metrics directly to engineering and business stakeholders.
* Enabled non-technical teams to query cross-account benchmark results and verify platform performance gains under peak load.

---

### 🔀 AWS Bedrock LLM Request Router & Legacy Safeguards
**Pragmatic AI Request Routing & Defensive Webhooks** *(Python, AWS Bedrock, Slack Webhooks)*
* Engineered a pragmatic request router passing incoming feature profiles to a small LLM in AWS Bedrock to dynamically allocate payloads between legacy and modernized stacks.
* Constructed defensive mapping validation with real-time Slack webhook alerts to prevent silent failures in production.

---

## 📈 GitHub Activity & Metrics

<p align="center">
  <img src="https://img.shields.io/github/followers/rajachakraborti?label=Followers&style=for-the-badge&logo=github&color=0F766E" alt="Followers" />
  <img src="https://img.shields.io/github/stars/rajachakraborti?label=Stars&style=for-the-badge&logo=github&color=D97706" alt="Stars" />
  <img src="https://img.shields.io/badge/Public_Repositories-13-blue?style=for-the-badge&logo=github&color=1E1B4B" alt="Repositories" />
</p>

### 🛠️ Primary Language Distribution
- **Java**: `Spring Boot` `Microservices` `High-Concurrency Engine Design` `Memory Optimization`
- **Python**: `PySpark` `PyTorch` `FastAPI` `Data Analytics` `Vertex AI / Bedrock`
- **TypeScript / JavaScript**: `Node.js` `React` `Next.js` `WebAssembly (WASM) SDKs`
- **SQL**: `PostgreSQL Schema Design` `Query Optimization` `Data Warehouse Modeling`

---

## 📫 Connect with Me

- 💼 **LinkedIn**: [linkedin.com/in/raja-chakraborty-203b3a115](https://www.linkedin.com/in/raja-chakraborty-203b3a115/)
- 📧 **Email**: rajachakraborti@gmail.com
- 🌐 **Portfolio Repo**: [github.com/rajachakraborti](https://github.com/rajachakraborti)

<h1 align="center">Hi, I'm Dileep Reddy Battu 👋</h1>

<p align="center">
  <strong>Full-Stack Software Engineer</strong> · Backend Systems · Cloud &amp; AI/ML Integration
</p>

<p align="center">
  <a href="https://dileepreddybattu.com/">Portfolio</a> &nbsp;•&nbsp;
  <a href="https://dileepreddybattu.com/DileepCV_AZ082026.pdf">Latest Resume</a> &nbsp;•&nbsp;
  <a href="https://www.linkedin.com/in/dileepreddy27">LinkedIn</a> &nbsp;•&nbsp;
  <a href="mailto:dileep151015@gmail.com">Email</a>
</p>

---

I am a Full-Stack Software Engineer with 4+ years of experience building web applications,
backend services, cloud data workflows, and AI-enabled systems across healthcare and business
domains. I work across the stack from responsive React interfaces and secure APIs to relational
data models, event-driven workflows, automated tests, containers, and CI/CD.

- 💼 Software Engineer at **Vesta Teleradiology**, working on healthcare applications, data services, reporting, and workflow automation
- 🎓 Pursuing an **M.S. in Data Science and Artificial Intelligence** at Campbellsville University
- 🎓 **M.S. in Computer Science**, Northern Arizona University
- 📍 Based in Sanford, Florida

## Recruiter highlights

1. **[Portfolio](https://dileepreddybattu.com/)** — Full-stack engineering work, professional experience, and selected projects.
2. **[Latest Resume](https://dileepreddybattu.com/DileepCV_AZ082026.pdf)** — Current Full-Stack Software Engineer résumé in PDF format.
3. **[OrderFlow](https://github.com/dileepreddy27/Orderflow)** — Event-driven order, inventory, and fulfillment platform built with Java 21, Spring Boot, React, PostgreSQL, Redis, and Kafka.
4. **[CareOps](https://github.com/dileepreddy27/CareOps)** — Provider credentialing, compliance, and coverage platform built with C#, .NET 10, ASP.NET Core, React, PostgreSQL, and SignalR.
5. **[TelemetryX](https://github.com/dileepreddy27/TelemetryX)** — Bounded telemetry ingestion, sliding-window analytics, and anomaly alerting built with C++20, Drogon, Boost.Asio, PostgreSQL, and React.
6. **[RAG-Assistant](https://github.com/dileepreddy27/RAG-Assistant)** — Python document Q&A service with FastAPI, LlamaIndex, SentenceTransformers, hybrid pgvector retrieval, reranking, and source-grounded answers.
7. **[SmartLeads on the portfolio](https://dileepreddybattu.com/#work)** — CRM for lead management, customer interactions, dashboards, and sales-pipeline workflows built with Next.js, React, TypeScript, Node.js, Express, PostgreSQL, and Highcharts.
8. **[GitHub profile](https://github.com/dileepreddy27)** — Public repositories, source code, documentation, and ongoing engineering work.

## Core skills

**Languages:** Python · JavaScript · TypeScript · Java · C++ · C · SQL · PL/pgSQL

**Frontend:** React.js · Next.js · HTML5 · CSS3 · Tailwind CSS · DaisyUI · Highcharts · Responsive Web Design

**Backend & APIs:** Node.js · Express.js · FastAPI · Flask · REST APIs · JSON · API Integration · Microservices · Apache Kafka

**Databases & Search:** PostgreSQL · BigQuery · Supabase · pgvector · MySQL · MongoDB · DynamoDB · Snowflake · Relational Data Modeling · NoSQL · Vector Search

**AI/ML & LLM:** LangChain · LlamaIndex · RAG · Agentic Workflows · OpenAI API · SentenceTransformers · Scikit-learn · PyTorch · Neural Networks · MLflow · Airflow · Prompt Engineering · LLM Evaluation · Anomaly Detection

**Cloud & DevOps:** GCP · Cloud Run · Cloud Scheduler · Cloud Storage · AWS · Azure · Docker · CI/CD · GitHub Actions · Linux · Vercel · Render

**Testing & Tools:** Unit Testing · Integration Testing · API Testing · pytest · Jest · Debugging · Validation · Monitoring · Git · GitHub · GitLab familiarity · Visual Studio Code · Jira · n8n · Agile · SDLC

## Projects

### 1. [OrderFlow](https://github.com/dileepreddy27/Orderflow)

An event-driven commerce platform for customer ordering, inventory control, fulfillment, and operations.

**How it works:**

1. A customer browses the React storefront and submits an order with an idempotency key.
2. Spring Boot validates the request and records the order and inventory reservation in PostgreSQL.
3. A transactional outbox publishes versioned events to Kafka without making Kafka the source of truth.
4. Inventory, payment simulation, cancellation, and fulfillment workflows consume events and update the order lifecycle.
5. The operations interface exposes order timelines, inventory alerts, audit history, and failed-event recovery controls.

**Stack:** Java 21 · Spring Boot · React · TypeScript · PostgreSQL · Redis · Kafka · Docker

### 2. [CareOps](https://github.com/dileepreddy27/CareOps)

A healthcare operations platform for provider credentialing, compliance monitoring, and coverage coordination.

**How it works:**

1. Providers and operations users authenticate through role-based ASP.NET Core APIs.
2. Provider profiles, credential metadata, checklists, comments, and workflow states are stored in PostgreSQL.
3. Credentialing specialists review submissions, request information, and move providers through guarded approval states.
4. Background compliance processing monitors expirations and SLA risk while SignalR sends workflow updates to the React interface.
5. Scheduling, notifications, and audit history give managers a consolidated view of credentialing and coverage activity.

**Stack:** C# · .NET 10 · ASP.NET Core · React · TypeScript · PostgreSQL · SignalR · Docker

### 3. [TelemetryX](https://github.com/dileepreddy27/TelemetryX)

A telemetry ingestion and anomaly-alerting platform with bounded concurrency and an operations dashboard.

**How it works:**

1. Producers submit validated telemetry events to the asynchronous Drogon HTTP API.
2. Accepted events enter a bounded queue; saturated requests receive an explicit backpressure response.
3. A fixed Boost.Asio worker pool processes events, updates live aggregates, and persists operational history to PostgreSQL.
4. Sliding-window metrics evaluate configurable rules and manage alert opening, acknowledgement, and recovery.
5. The React console displays service health, charts, incidents, alert details, and recent telemetry events.

**Stack:** C++20 · Drogon · Boost.Asio · PostgreSQL · React · TypeScript · Docker

These repositories include architecture and operations documentation, automated tests, containerized
local environments, and CI workflows. Each README documents the project's scope and known boundaries.

### 4. [AIapply.ai](https://github.com/dileepreddy27/AIapply.ai)

An AI-assisted job platform for role discovery, resume matching, document tailoring, and application tracking.

**How it works:**

1. A user signs in through Supabase, builds a profile, and uploads a resume.
2. The platform searches configured job sources and creates a reusable feed of role matches.
3. A RAG-style retrieval layer compares resume content with job requirements and returns matching results.
4. The assistant supports resume and cover-letter tailoring, saved application answers, and application status tracking.
5. Stripe checkout and webhooks manage Basic and Pro feature entitlements.

**Stack:** Python · FastAPI · Next.js · Supabase · Stripe · RAG · Anthropic Claude

### 5. [MLOps-Pipeline](https://github.com/dileepreddy27/MLOps-Pipeline)

An end-to-end machine-learning lifecycle for training, deployment, monitoring, and retraining.

**How it works:**

1. The pipeline ingests data, cleans it, and creates model-ready features.
2. It trains and tunes candidate models, then evaluates their quality before promotion.
3. MLflow records experiments, parameters, metrics, artifacts, and model versions.
4. FastAPI serves predictions and routes live requests between model variants for A/B evaluation.
5. Feedback and drift monitoring can trigger retraining workflows orchestrated through Airflow and checked in CI.

**Stack:** Python · FastAPI · Scikit-learn · MLflow · Airflow · pytest · GitHub Actions

### 6. [AI-Powered-Threat](https://github.com/dileepreddy27/AI-Powered-Threat)

A threat-detection platform for analyzing web-traffic logs and reviewing anomaly alerts.

**How it works:**

1. Users upload CSV logs or send JSON events through the ingestion API.
2. The Node.js gateway normalizes each record and forwards it to the FastAPI ML service.
3. The service engineers behavioral features and scores events with Isolation Forest, One-Class SVM, and a PyTorch autoencoder.
4. Raw events, detection results, and high-severity alerts are stored in PostgreSQL.
5. The Next.js dashboard presents detections, alert acknowledgement, timeline trends, and model comparisons.

**Stack:** FastAPI · Scikit-learn · PyTorch · Node.js · Express · Next.js · PostgreSQL · Docker

### 7. [RAG-Assistant](https://github.com/dileepreddy27/RAG-Assistant)

A document question-answering backend that retrieves relevant source material before generating an answer.

**How it works:**

1. A user uploads a PDF, DOCX, TXT, or Markdown document through FastAPI.
2. LlamaIndex parses and splits the text into searchable chunks.
3. SentenceTransformers creates embeddings stored with metadata in PostgreSQL and pgvector.
4. A question triggers hybrid vector and keyword retrieval with optional reranking.
5. LangChain sends the retrieved context and recent conversation history to the LLM and returns an answer with source references.

**Stack:** Python · FastAPI · LangChain · LlamaIndex · SentenceTransformers · PostgreSQL · Supabase · pgvector

### 8. [Jarvis](https://github.com/dileepreddy27/Jarvis)

A voice-first assistant for conversation, personal productivity, web research, and development tasks.

**How it works:**

1. The browser captures speech and sends the request to the Python assistant backend.
2. The language model interprets the request and selects an available tool or integration.
3. Tools can read calendar, email, and notes; browse the web; manage tasks; or start supported development workflows.
4. Persistent preferences and recent context help the assistant personalize later interactions and daily plans.
5. The response is spoken back while the Three.js interface renders an audio-reactive visualization.

**Stack:** Python · TypeScript · Web Speech API · WebSockets · Three.js · Anthropic Claude · AppleScript

---

<p align="center"><i>Building reliable full-stack software, event-driven workflows, and intelligent applications that solve real operational problems.</i></p>

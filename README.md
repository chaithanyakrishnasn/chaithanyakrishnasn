# Hi, I'm Krishna

## Building AI Systems That Think, Reason, and Ship

Engineer at the intersection of **Generative AI**, **full-stack development**, and **intelligent systems** —
from production RAG pipelines and multi-agent workflows to real-time ML systems and scalable APIs.

---

## About Me

- Computer Science & Design undergraduate, graduating 2026
- Building **production-grade AI systems** — RAG, LLM agents, GenAI apps, vector search
- Full-stack engineer: **Python · FastAPI · PostgreSQL · Vector DBs**
- Exploring **hybrid retrieval**, autonomous agents, and multilingual LLM pipelines
- Published patent on AI-collaborative workspaces
- KSCST SPP 2025–26 Research Sponsorship Recipient

---

## What I Build

### Generative AI & LLM Systems
- **Production RAG pipelines** — semantic chunking, vector retrieval, source attribution, conversational memory
- **Multi-agent systems** — tool use, multi-step reasoning, self-reflection, orchestration workflows
- **Structured LLM output** — Instructor + Pydantic for guaranteed schema-valid responses from LLMs
- **SSE streaming** — progressive result delivery for long-running LLM inference

### Full-Stack & Backend Engineering
- **FastAPI microservices** — async PostgreSQL, Redis Streams, WebSockets, SSE, REST APIs
- **Full-stack applications** — Next.js + React with real-time dashboards and responsive UI
- **Data pipelines & automation** — ETL workflows, scheduled jobs, retry logic, execution monitoring
- **Production deployments** — Docker, GitHub Actions CI/CD, Vercel, Render, Supabase

### ML & Data Systems
- **Anomaly detection** — IsolationForest trained and benchmarked on real public IDS datasets
- **Vector search** — pgvector + ChromaDB with hybrid SQL + semantic retrieval pipelines
- **Data analytics** — structured query design, KPI dashboards, exploratory analysis
- **LLM evaluation** — red teaming, adversarial prompting, LLM-as-judge benchmarking

---

## Tech Stack

**Languages**
- Python · SQL · JavaScript · Bash

**Backend & APIs**
- FastAPI · REST APIs · WebSockets · SQLAlchemy · Pydantic · APScheduler

**Databases**
- PostgreSQL · MongoDB · Redis · SQLite · ChromaDB

**Cloud & DevOps**
- AWS · Docker · GitHub Actions · CI/CD · Git · Linux

**Tools**
- VS Code · Jupyter Notebook · Postman · Google AI Studio · Claude-Code/Codex

**AI / ML / LLM**
- LLMs (Claude, Gemini, GPT) · RAG Pipelines · LangChain · LangGraph
- Scikit-learn · Gemini text-embedding-004 · Instructor · Hugging Face
- Prompt Engineering · LLM Evaluation · pgvector · ChromaDB · Vector Databases

---

## Featured Projects

### [AI-Powered Government Schemes Advisor](https://github.com/chaithanyakrishnasn/ai-powered-govt-schemes-advisor)
> Multilingual AI platform matching 334+ Indian government welfare schemes to citizen profiles

**Stack:** Next.js 15 · FastAPI · PostgreSQL + pgvector · Gemini 2.5 Flash · Instructor

- **3-stage hybrid retrieval pipeline**: SQL eligibility filter (~50ms, eliminates 75%+ candidates) → pgvector cosine similarity (768-dim embeddings) → Gemini 2.5 Flash reasoning over raw eligibility text
- **LLM-powered eligibility extractor** (Gemini + Instructor): converts unstructured bureaucratic prose into 1,763 typed eligibility rules with AND/OR logic, operators, and confidence scores
- **Multilingual pipeline** (EN / HI / KN): Unicode detection → English translation for retrieval → respond in user's language. Zero extra API calls for English users

---

### [Agentic Security Operations Platform](https://github.com/chaithanyakrishnasn/agentic-driven-soc)
> Full-stack AI platform with autonomous LLM agents, real-time ML detection, and a live SOC dashboard

**Stack:** Python · FastAPI · Next.js 14 · Claude API · Scikit-learn · ChromaDB · Redis Streams · PostgreSQL · Docker · GitHub Actions

- **Multi-agent architecture**: Red Agent (attack simulation), Blue Agent (AI-powered incident analysis and playbook generation), Playbook Agent (multi-step remediation orchestration) — each powered by Claude API
- **9-step ML detection pipeline**: IsolationForest + 12 rule-based classifiers trained on NSL-KDD (86.6% accuracy) and UNSW-NB15 (91.9% accuracy) with a dataset replay engine
- **SHA-256 hash-chained audit log** for immutable, tamper-proof traceability across all agent actions and API activity

---

### [Smart Study Notes — Full-Stack RAG Application](https://github.com/chaithanyakrishnasn/smart-study-notes)
> PDF upload → semantic chunking → Claude-powered Q&A and structured summaries

**Stack:** React 18 · Vite · FastAPI · PyMuPDF · ChromaDB · Claude Sonnet API · Python

- End-to-end RAG pipeline: PDF text extraction → 500-word overlapping chunks → all-MiniLM-L6-v2 embeddings → top-5 retrieval → Claude Sonnet for contextual Q&A
- One-click structured summary (Overview / Key Topics / Important Points) using Claude with a strict grounding prompt
- Persistent ChromaDB vector store survives server restarts — no re-indexing on re-upload

---

### [Intelligent Workflow Automation Engine](https://github.com/chaithanyakrishnasn/intelligent-workflow-automation-engine)
> End-to-end automation platform with timer, webhook, and event-driven execution

**Stack:** Python · FastAPI · PostgreSQL · SQLAlchemy · APScheduler · Pydantic

- Factory-pattern pluggable action engine with timer and webhook triggers, retry logic, and failure handling
- Fully documented REST APIs with Pydantic schema validation and structured execution logging

---

### [LLM Security Lab — Adversarial Prompt Benchmark](https://github.com/chaithanyakrishnasn/llm-security-lab)
> Systematic prompt injection testing with LLM-as-judge evaluation pipeline

**Stack:** Python · OpenAI-compatible API · Rule-based + LLM-Judge Evaluator

- Adversarial attack generation across easy/medium/hard difficulty: jailbreaks, instruction-override, policy-bypass
- Dual evaluation: rule-based keyword detection + LLM-as-judge returning structured JSON verdicts
- Metrics: compromise rate, defense effectiveness, judge disagreement across two defense strategies

---

## Certifications

- Google Professional Cybersecurity Certificate — December 2024
- Google Cloud Cybersecurity Certificate — February 2025
- Google Generative AI Leader Certification — May 2026

---

## Current Focus

- Hybrid retrieval systems (SQL + vector + LLM reasoning)
- Autonomous multi-agent architectures and orchestration
- LLM evaluation, benchmarking, and structured output pipelines
- Production AI deployment patterns (streaming, async, edge)

---

## Connect

- 📧 chaithanyakrishnasn@gmail.com
- 💼 [linkedin.com/in/krrishnachaithanya](https://www.linkedin.com/in/krrishnachaithanya)
- 🐙 GitHub: You're already here!

---

> *"To build truly secure systems, you must understand how they break."*

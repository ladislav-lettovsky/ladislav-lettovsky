# Hi, I'm Ladislav Lettovsky

**PhD, Industrial Engineering** · Georgia Institute of Technology |
**MBA** · Cornell Johnson Graduate School of Management |
**Agentic AI Specialization** · UT Austin Postgraduate Program in AI/ML

Strategic executive leader turned AI/ML practitioner — 15 years at Sabre Corporation (Airline IT solutions), VP of Technical Sales, Director of M&A ($40M+ portfolio), Research & Development (holder of 2 US patents in airline network optimization).

[![Ask Ladislav's AI](ai_career_agent.png "Ask Ladislav's AI")](https://ai-career-agent-n4oo.onrender.com/)

---

## 🚀 AI Engineer | Agentic Systems | RAG | Tooling

> Building structured, local-first AI systems — from agents to RAG to developer tooling.

I focus on designing and building:

- Agent architectures (tool use, memory, routing)
- Retrieval-Augmented Generation (RAG) systems
- Local-first AI development workflows
- Evaluation and observability for LLM applications

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-5A31F4?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-121212?style=for-the-badge)
![LangSmith](https://img.shields.io/badge/LangSmith-111111?style=for-the-badge)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge)
![PyMuPDF](https://img.shields.io/badge/PyMuPDF-2C2C2C?style=for-the-badge)
![BM25](https://img.shields.io/badge/BM25-4B5563?style=for-the-badge)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

## AI Portfolio & Tooling

### [ai-toolkit](https://github.com/ladislav-lettovsky/ai-toolkit)

A local-first AI CLI toolkit for creating, running, evaluating, and managing agent and RAG projects with reproducible structure and metadata-aware lifecycle management.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

- Built a local-first CLI platform for scaffolding and managing AI agent and RAG projects
- Added project lifecycle commands including inspect, eval, doctor, clean, run, and upgrade
- Implemented agent features such as memory, logs, typed tools, safe file writing, and config layering
- Added RAG project generation with ingestion, chunk indexing, retrieval, and evaluation support

---

### [ai-delivery-exception-system](https://github.com/ladislav-lettovsky/ai-delivery-exception-system)

A multi-agent system that detects, triages, resolves, and communicates last-mile delivery exceptions using LangGraph orchestration.

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![GPT-4o](https://img.shields.io/badge/GPT--4o-412991?style=flat-square) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square)

- Multi-agent orchestration with supervisor pattern and specialized worker agents
- Vector similarity search (Chroma + HuggingFace embeddings) for resolution matching
- End-to-end pipeline: detection → triage → resolution → customer notification
- LangSmith observability for tracing and debugging agent behavior

---

### [ai-ehr-assistant](https://github.com/ladislav-lettovsky/ai-ehr-assistant)

A guardrailed, patient-facing AI assistant that explains Electronic Health Records in plain language with strict safety enforcement.

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![GPT-4o-mini](https://img.shields.io/badge/GPT--4o--mini-412991?style=flat-square) ![GPT-4o](https://img.shields.io/badge/GPT--4o-412991?style=flat-square) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square)

- ReAct agent with 4-node state machine: agent → tool → validate → policy
- 11 patient-scoped tools with deterministic safety routing (12 policy rules)
- 7-dimension validation rubric scored by GPT-4o — **10/10 test cases passed**
- Multilingual support, health literacy adaptation, and PHI protection

---

### [ai-rag-knowledge-analyst](https://github.com/ladislav-lettovsky/ai-rag-knowledge-analyst)

A RAG pipeline that enables analysts to extract insights from lengthy business reports through natural-language queries.

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square) ![GPT-4o-mini](https://img.shields.io/badge/GPT--4o--mini-412991?style=flat-square) ![PyMuPDF](https://img.shields.io/badge/PyMuPDF-PDF_Processing-blue?style=flat-square) ![BM25](https://img.shields.io/badge/BM25-Hybrid_Retrieval-green?style=flat-square)

- Full RAG pipeline: PDF → chunking → embedding → Chroma → retrieval → generation
- Three-mode comparison: raw LLM vs. prompt-engineered vs. RAG (grounded)
- Hybrid retrieval infrastructure (BM25 + vector similarity)
- RAG achieves **1.0 groundedness** where plain LLM scores 0.0

---

## Background

- **VP, Head of Sales Engineering** at Sabre Corporation (2022–2024) — Led airline IT solutions technical sales, 20+ solution architects, exceeded global sales target 2x
- **Director, New Business Ventures & M&A** at Sabre Corporation (2009–2022) — Led LATAM Airlines Group PSS implementation, 3 acquisitions + 1 divestiture ($40M+)
- **2 US Patents** in airline network design and passenger reaccommodation
- **Languages**: Czech (native) · English (native)

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ladislavlettovsky/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github&logoColor=white)](https://github.com/ladislav-lettovsky)

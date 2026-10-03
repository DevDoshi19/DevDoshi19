<div align="center">

# Dev Doshi

**AI & Backend Engineering Student · Systems Builder**

I build backend and AI systems to understand how real software works — from retrieval pipelines and LLM workflows to transactions, caching, queues, and system design.

[LinkedIn](https://www.linkedin.com/in/devdoshi19/) · [LeetCode](https://leetcode.com/u/DevDoshi_19/) · [HackerRank](https://hackerrank.com/profile/devdoshi1927)

</div>

---

## What I'm Building Toward

My projects increasingly sit at the intersection of **AI, backend engineering, and distributed-systems thinking**.

I care less about collecting frameworks and more about understanding the problems behind them:

- How do we make an LLM application reliable?
- How do retrieval, validation, retries, and observability fit together?
- How do we keep money movement atomic and idempotent?
- When do caches, queues, workers, and pub/sub actually help?
- How do we turn these ideas into systems that are easy to reason about?

I'm learning these ideas by building, breaking, debugging, and documenting them.

---

## Featured Work

### [VaultMind](https://github.com/DevDoshi19/VaultMind)
**Hybrid RAG Intelligence Engine**

A production-oriented RAG application built around a LangGraph workflow.

**What it explores**
- Hybrid retrieval using **ChromaDB + BM25**
- Reciprocal Rank Fusion (RRF)
- Query classification and relevance gating
- Context validation and token budgeting
- Input/output guardrails
- Retry logic, confidence scoring, and cost tracking
- FastAPI + Streamlit split
- Docker Compose and GitHub Actions
- LangSmith tracing and RAGAS evaluation

**Why it matters:** this is where my AI work moved beyond “call an LLM” toward thinking about **retrieval quality, failure modes, observability, and system structure**.

---

### [Bank Transaction System](https://github.com/DevDoshi19/Bank-Transaction-System)
**Backend system for accounts, ledgers, and transfers**

A Node.js/Express backend focused on the engineering problems behind financial transactions.

**What it explores**
- JWT authentication and authorization
- Ledger-based balance calculation
- MongoDB transactions and atomic writes
- Idempotency keys
- Transaction state management
- TTL-based JWT blacklist cleanup
- Layered backend structure

**Why it matters:** this project pushed me toward thinking about **consistency, atomicity, failure handling, and concurrent requests** rather than only API implementation.

---

### [Redis Live Leaderboard](https://github.com/DevDoshi19/Redis-live-leaderboard)
**Real-time ranking with Redis Sorted Sets**

A focused implementation for understanding how Redis can support continuously updated rankings.

It builds on concepts from my broader [Redis learning repository](https://github.com/DevDoshi19/Redis-learning), where I explore TTLs, hashes, queues, BullMQ, pub/sub, and sorted sets through smaller experiments.

---

### [AI Diagram Studio](https://github.com/DevDoshi19/AI-diagram-studio)
**Natural language → editable architecture diagrams**

A full-stack AI application using React, FastAPI, PostgreSQL/SQLite, and Excalidraw.

The interesting part for me is the system boundary: an LLM produces structured diagram data, the backend streams it with **SSE**, and the frontend turns it into an editable canvas.

---

## Engineering Practice

### Algorithms & Problem Solving
[DSA_ProblemSolving](https://github.com/DevDoshi19/DSA_ProblemSolving) · [DSA](https://github.com/DevDoshi19/DSA)

I use these repositories to build pattern recognition and strengthen the fundamentals behind problem solving — arrays, strings, linked lists, trees, graphs, heaps, binary search, stacks, queues, and related patterns.

### System Design & LLD
[system-design-lab](https://github.com/DevDoshi19/system-design-lab) · [low-level-design-python](https://github.com/DevDoshi19/low-level-design-python)

These are my working notes and implementations for understanding:
**APIs, components, data flow, storage, concurrency, interfaces, and object-oriented design.**

### Backend Foundations
[Redis-learning](https://github.com/DevDoshi19/Redis-learning) · [Spotify-Backend](https://github.com/DevDoshi19/Spotify-Backend)

I use smaller backend projects to understand the building blocks that show up inside larger systems:
**caching, queues, workers, authentication, storage, APIs, and service boundaries.**

### Frontend Foundations
[TypeScript-learning](https://github.com/DevDoshi19/TypeScript-learning) · [react-learning](https://github.com/DevDoshi19/react-learning)

I'm currently strengthening TypeScript and React so I can understand and build across the full application boundary — not just the backend.

---

## Current Technical Direction

**AI / LLM**
`LangChain` · `LangGraph` · `LangSmith` · `RAG` · `OpenAI` · `Gemini` · `Groq`

**Backend**
`Python` · `FastAPI` · `Node.js` · `Express` · `MongoDB` · `PostgreSQL` · `SQLAlchemy`

**Systems**
`Redis` · `BullMQ` · `Docker` · `GitHub Actions` · `SSE` · `REST APIs`

**Frontend**
`TypeScript` · `React` · `Vite`

**Foundations**
`DSA` · `OOP` · `System Design` · `Low-Level Design`

---

## How I Learn

I try to keep a simple loop:

**Learn → Build → Break → Debug → Understand → Document**

Some repositories are polished applications. Others are deliberately smaller experiments.

Both are useful.

The larger projects show what I can build.  
The smaller repositories show **what I am actively learning**.

---

## A Few Projects Worth Exploring

| Project | Focus |
| --- | --- |
| [VaultMind](https://github.com/DevDoshi19/VaultMind) | Hybrid RAG, LangGraph, evaluation, guardrails |
| [Bank Transaction System](https://github.com/DevDoshi19/Bank-Transaction-System) | Transactions, ledgers, idempotency, auth |
| [AI Diagram Studio](https://github.com/DevDoshi19/AI-diagram-studio) | AI + FastAPI + React + SSE |
| [Redis Live Leaderboard](https://github.com/DevDoshi19/Redis-live-leaderboard) | Redis Sorted Sets and real-time ranking |
| [System Design Lab](https://github.com/DevDoshi19/system-design-lab) | System design practice |
| [DSA Problem Solving](https://github.com/DevDoshi19/DSA_ProblemSolving) | Algorithms and patterns |

---

## Beyond the Code

B.Tech in **Artificial Intelligence & Data Science**.

I enjoy understanding systems deeply, especially the parts that become interesting under real constraints: **scale, consistency, latency, concurrency, failure, and cost**.

I'm currently exploring how strong backend fundamentals and AI engineering come together to build useful software.

---

<div align="center">

**Build things. Understand why they work. Then make them better.**

</div>

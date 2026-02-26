# Hi there, I'm Anushka 👋

**Senior Software Engineer** | Backend • Full Stack • Data Infrastructure | **MS CS @ Georgia Tech** | **AI/ML Enthusiast**

8+ years building production systems at scale - backend services, data pipelines, and full stack product features. Previously at Zynga (1M+ DAU) and ZS Associates (50K+ users). Currently at Georgia Tech deepening expertise in systems, databases, and AI.

---

## 🚀 About Me

- ⚙️ Former Senior Software Engineer at **Zynga** — built distributed backend systems, real-time leaderboards, event pipelines, and full stack product features supporting **1M+ DAU**
- 📊 Former Senior Software Engineer at **ZS Associates** — architected and owned a Big Data catalog platform end to end serving **50K+ users**
- 💡 Strong focus on **distributed systems**, **database internals**, **stream processing**, and **scalable architecture**
- 🎓 MS in Computer Science @ Georgia Tech — Database Systems, Machine Learning, AI, NLP

---

## 🛠️ Tech Stack

**Languages:** Python • Go • Java • TypeScript • JavaScript • C# • SQL  
**Backend & Data:** Apache Kafka • Apache Spark • Redis • PostgreSQL • MongoDB • Redshift • Elasticsearch  
**Frontend:** React / Next.js • Angular • Node.js  
**Cloud:** AWS (S3, EC2, RDS, Redshift, Lambda, SageMaker, DynamoDB, CloudFormation, Step Functions)  
**DevOps & Observability:** Docker • Kubernetes • Prometheus • Splunk • CI/CD  
**Frameworks:** FastAPI • Flask • gRPC  
**AI/ML:** Stable Diffusion • HuggingFace • OpenCV • Pandas • NumPy  
**Architecture:** Microservices • RESTful APIs • Distributed Systems • Event-Driven Design
---

## 🎯 Featured Projects

### 📦 Mini Data Warehouse + Query Engine
Columnar mini data warehouse with a custom SQL-like query engine supporting joins, aggregates, partition pruning, predicate pushdown, and vectorized execution.  
**Tech:** Python, Go, FastAPI, SQLite, Docker

### 🌊 Real-Time Streaming Data Platform
Distributed log-based streaming system with partitioned topics, consumer groups, at-least-once delivery semantics, offset management, and fault recovery.  
**Tech:** Go, gRPC, RocksDB, Docker, Prometheus

### 📊 Hybrid Vector & Metadata Search Engine
- ⁠Architected and benchmarked a hybrid search system to solve the "selective filtering" problem in vector databases, comparing Pre-filtering, Post-filtering, and Metadata-aware Inverted File (IVF) structures.
- Implemented a Custom Metadata IVF Index that routed queries to relevant partitions, achieving a ~77x speedup (0.23ms vs. 17.9ms) over standard Post-filtering for highly selective queries (0.4% selectivity).
- ⁠Optimized query execution using Bitmap-based filtering, which proved most efficient for "Very Loose" selectivity (100% match), outperforming partition-based routing by approximately 35%.
- ⁠Conducted rigorous performance analysis across three selectivity regimes—Very Selective (0.4%), Loose (17.7%), and Very Loose (100%)—to identify the optimal cross-over points for hybrid search strategies.
- ⁠Engineered baselines using IVFPQ and IVF-Flat indices on a 100,000-row dataset of 768-dimensional embeddings, analyzing the trade-offs between brute-force pre-filtering and ANN-based post-filtering.

**Tech:** Python, FAISS, NumPy, Pandas, Bitmaps, arXiv Dataset (100k records)

### 🎮 AI-Based Connect 4 Game Service
Full stack game service with RESTful APIs in FastAPI for session management and persistent game state, paired with an AI bot using alpha-beta pruning with iterative deepening.  
**Tech:** Python, FastAPI, Next.js, PostgreSQL, MongoDB, Redux

---

## Other Projects

### 🧠 Transformer Language Model from Scratch

- Implemented a **GPT-style Transformer language model** end-to-end in PyTorch, including embeddings, pre-norm Transformer blocks, RMSNorm, SwiGLU feed-forward layers, and causal multi-head self-attention with RoPE.
- Built the **full training pipeline** from scratch: memory-mapped data loading, batching, AdamW optimization, gradient clipping, checkpointing, and cosine learning rate scheduling.
- Trained a ~**17M parameter model** on the **TinyStories** dataset, achieving **≤ 1.8 validation loss**, with further improvements at higher token budgets.
- Implemented **autoregressive decoding** with temperature scaling and **top-p (nucleus) sampling** for text generation.
- Implemented a **byte-level BPE tokenizer** with custom merge rules, encoding, and decoding.
- Passed a comprehensive **pytest-based test suite** covering attention, normalization, transformer blocks, training, and inference.

**Tech:** PyTorch, Transformers, RoPE, RMSNorm, SwiGLU, AdamW, CUDA, Pytest

### 🤖 Prison Dodgeball — Autonomous Game AI System
- Designed and implemented a physics-constrained ballistic interception system for autonomous agents, solving one-shot projectile trajectories against moving targets under gravity.
- Applied iterative numerical refinement to reconcile analytical intercept solutions with real-world constraints (speed limits, animation delay, dynamic launch points).
- Built decision heuristics combining kinematic stability analysis, navmesh path prediction, and parabolic occlusion checks to maximize hit probability while avoiding unrealistic throws.
- Integrated projectile prediction into a finite state machine–driven agent architecture, coordinating movement, evasion, ball collection, rescues, and throw timing.
- Balanced realism vs. accuracy tradeoffs common in production games by selectively rejecting infeasible or low-confidence actions.

**Tech:** Unity, C#, AI, Game AI

### 🧩 Raven's Progressive Matrices Solver
AI solver for non-verbal intelligence tests using pattern recognition and logical reasoning  
**Tech:** Python, OpenCV, NumPy

> **Note:** Academic project code is private due to Georgia Tech's Office of Student Integrity policies. I'm happy to discuss the technical implementation, architecture decisions, and demonstrate functionality during interviews. Please reach out if you'd like to request access for recruiting purposes.

---

## 💼 Professional Highlights

### Zynga Inc. (2022–2025)
- Designed multi-tier competitive leaderboard system — local + global leaderboards, challenge lifecycle engine, Hall of Fame persistence, backed by geo-partitioned Redis across multiple regions supporting 1M+ DAU
- Built punchcard loyalty feature end to end, reward engine, multi-platform IAP with transaction state machine, and client-facing UI flows driving 30% revenue increase
- Operated multi-region Kafka event ingestion pipeline with DLQ, retry logic, and at-least-once delivery guarantees
- Developed Gen AI inference pipeline on AWS SageMaker with S3-backed asset storage

### ZS Associates (2017–2022)
- Architected Big Data catalog platform from scratch — PostgreSQL schema design, read replicas, partitioning, Angular SPA frontend, JWT auth with RBAC, reducing page load from 4-6s to under 2s for 50K+ users
- Resolved database bottlenecks across 8-12M row tables — composite indexing, N+1 fixes, pagination — reducing worst-case query latency from 8-10s to under 1.5s
- Engineered automated data migration across PostgreSQL, S3, and Redshift with zero errors, cutting effort from 15 days to 3 minutes
- Built testing infrastructure from 0% to 65% coverage, CI/CD pipelines cutting deployment from 2 hours to 20 minutes

---

## 🏆 Certifications
- AWS Certified Developer Associate
- Machine Learning — Stanford University

## 📫 Let's Connect
- 💼 [LinkedIn](https://www.linkedin.com/in/anushkabajpai31/)
- 📧 anushkabajpai31@gmail.com

---

💡 **Open to opportunities in:** Software Engineering • Backend • Full Stack • Data Infrastructure

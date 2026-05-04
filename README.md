# Anudeep Reddy Mutyala
**AI Engineer — Agentic Systems & LLM Applications**  
Hyderabad, India | Open to Remote (US / Global)  
[themachinist.org](https://themachinist.org) · [linkedin.com/in/anudeep-reddy-mutyala](https://linkedin.com/in/anudeep-reddy-mutyala) · [anudeepreddy332@gmail.com](mailto:anudeepreddy332@gmail.com)

---

## What I Build

AI engineer focused on agentic systems and LLM-based pipelines — tool calling, retrieval-augmented generation (RAG), LangGraph state machines, and human-in-the-loop workflows. I build with evaluation-first thinking: every system I ship has a benchmark harness, regression tests, and documented failure modes.

Background in mechanical engineering, automotive design, and operations. I bring a different lens to system reliability and failure reasoning than most people coming purely from software.

---

## Agentic AI Projects

**[Code Review & Auto-Fix Agent](https://github.com/anudeepreddy332/code-agent)** · [themachinist.org/code-agent](https://themachinist.org/code-agent)  
LangGraph · LangSmith · Python subprocess sandbox  
Execute → diagnose → patch → re-execute loop with bounded reflexion (max 5 iterations), per-iteration cost gating, and human-in-the-loop approval checkpoint. **95% fix rate on 20-script benchmark** · mean 2.3 iterations · ~$0.0006 per run. Resilience-tested against timeouts, cost ceiling violations, and invalid API keys.

**[Knowledge Agent — Hybrid RAG System](https://github.com/anudeepreddy332/knowledge-agent)** · [themachinist.org/knowledge-agent](https://themachinist.org/knowledge-agent)  
ChromaDB · BM25 · sentence-transformers  
Hybrid retrieval pipeline: BM25 + dense search fused via Reciprocal Rank Fusion → cross-encoder reranking (ms-marco-MiniLM-L-6-v2). Two-stage architecture (20 candidates → top 5). **92% accuracy and 100% tool-routing accuracy** on adversarial test cases. Claim verification with source grounding and persistent JSON memory layer.

**[CLI Research Agent](https://github.com/anudeepreddy332/cli-research-agent)** · [themachinist.org/cli-research-agent](https://themachinist.org/cli-research-agent)  
DeepSeek API · Tavily · httpx · BeautifulSoup  
Raw agent execution loop built from scratch using OpenAI-compatible tool-calling protocol — no frameworks — to understand the mechanics before abstracting them. Benchmarked across 10 real-world queries. Later rebuilt with LangGraph to compare raw loop vs. framework execution (equivalent output quality, improved state traceability).

---

## ML & Data Engineering Projects

**[Silent Recall Detection System](https://github.com/anudeepreddy332/nhtsa-silent-recall-detection-system)**  
Automated ETL pipeline on 10,000+ NHTSA complaint and recall records. Identified 28 vehicle models with complaint-to-recall ratios exceeding 50:1.

**[Production Line Defect Analytics](https://github.com/anudeepreddy332/bosch-production-line-defect-analysis)**  
1.18M+ records, 4,268 variables. Feature space reduced ~80%. Single station identified with 7.8× higher failure probability. Storage optimized 60GB → 1.77GB Parquet.

**[Bearing Failure Prediction & RUL](https://github.com/anudeepreddy332/bearing-failure-prediction)**  
984 vibration recordings at 20,480 Hz. Regression model R² = 0.985. Late-stage prediction error reduced from ~30 hours to 2.88 hours via weighted loss optimization.

---

## Tech Stack

**LLM & Agent Systems:** LangGraph · LangChain · ReAct loops · tool calling · prompt versioning · HITL workflows · OpenAI-compatible APIs  
**Retrieval & RAG:** ChromaDB · BM25 · dense retrieval · Reciprocal Rank Fusion · cross-encoder reranking  
**Evaluation & Observability:** Benchmark harnesses · regression suites · LangSmith tracing · structured run logging  
**Backend & Infrastructure:** Python · FastAPI · async workflows (httpx) · subprocess sandboxing · uv · Git  
**Search & Data:** Tavily API · BeautifulSoup · pandas · NumPy · PostgreSQL · Parquet

---

## Background

M.S. Mechanical Engineering — Wright State University, Ohio  
Design Engineer — Honda R&D Americas (2016–2018)  
Advanced Cicerone (1 of ~230 globally)

Non-linear path. Systematic thinker. I've shipped things that had to work — automotive components with NVH, crash, and cost targets, fermentation monitoring systems with real variance, training programs with pass/fail outcomes. That background informs how I approach agent reliability and failure reasoning.

---

*Available immediately. Drop a message or email — I reply fast.*

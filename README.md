<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=ARYA%20DOSHI&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=32"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=00D9FF&center=true&vCenter=true&width=750&lines=AI+%2F+ML+Engineer;GenAI+%7C+RAG+%7C+Agentic+Systems;Building+Production+AI+%26+Trading+Systems" alt="Typing SVG" />

<br/>

<a href="mailto:doshiarya27@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/arya-doshi-3837aa249"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/aryadoshii"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://v0-arya-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white"/></a>
<a href="https://orcid.org/0009-0007-0744-9977"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white"/></a>

</div>

---

## 🔥 About Me

B.Tech graduate (Electronics & Telecommunications, CGPA 8.66) from Vishwakarma Institute of Technology, Pune. Recently completed an AI Engineer Internship at QubridAI building production agentic systems with LangGraph, CrewAI, and Google ADK. My work spans GenAI infrastructure, RAG pipelines, systematic trading, and computer vision — always targeting production-grade quality.


---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white) ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

**AI / ML & GenAI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black) ![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)

**Agentic & Orchestration**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![CrewAI](https://img.shields.io/badge/CrewAI-FF4B4B?style=for-the-badge&logo=crewai&logoColor=white) ![Google ADK](https://img.shields.io/badge/Google%20ADK-4285F4?style=for-the-badge&logo=google&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white)

**Infrastructure & Tools**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![FAISS](https://img.shields.io/badge/FAISS-0078D7?style=for-the-badge&logo=meta&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logo=databricks&logoColor=white)

</div>

**Domains:** Agentic AI · RAG Systems · Computer Vision · Systematic Trading · Federated Learning · Model Quantization · Quant Research

---

## 🧑‍💼 Experience

**AI Engineer Intern** · QubridAI (Virginia, Remote) · Jan – Mar 2026
-  Built 7+ reference applications and cookbook notebooks on QubridAI’s unified API platform using frontier models (OpenAI, Anthropic, Gemini, Qwen, Nemotron); delivered use cases spanning multi-agent code generation, image
restoration, text rewriting, and UI-to-code conversion.
-  Developed agentic AI applications and multi-step workflows using frameworks such as CrewAI, leveraging specialized executor agent roles and prompt engineering to automate complex multi-stage tasks.
---

## 💎 Featured Projects


### 📡 TeleTriage — Production Telecom Fault Resolution Engine
*3-tier hybrid RAG pipeline*

Built from scratch: **CAG** (exact/fuzzy cache) → **Hybrid RAG** (BM25Okapi + BGE-small-en-v1.5 FAISS + RRF k=60 + bge-reranker-base cross-encoder) → **Generative fallback** (Groq Llama-3.3-70B → Gemini 2.0 Flash → local Qwen2.5-1.5B). Ingest: 7,181 KB entries from 3GPP specs via MinHash LSH dedup. Results: BERTScore **0.815**, latency reduced from **~1,458ms → ~163ms**, 142 passing tests.

`LangChain` `FAISS` `BM25Okapi` `BGE` `Groq` `Gemini` `Streamlit` `3GPP`

---

### 🏦 QuantEdge — Systematic Equity Trading Platform

Long-short market-neutral strategy with 32+ quantitative factors. Honest post-audit: walk-forward validation corrected; committed Sharpe **1.01**; alpha driven by size/liquidity + low-beta + contrarian tilts; regime-dependent (2023 H1). Surgical fixes applied: beta calculation, train-only imputation, ticker-grouped signal shift.

`Python` `scikit-learn` `Random Forest` `yfinance` `Streamlit` `Plotly`

---

### 📊 EarningsEdge — AI-Powered Earnings Call Analyzer
*LangGraph · Multi-Modal Finance*

9-node async LangGraph pipeline analyzing earnings calls across 4 signals: tone drift (30%), guidance accuracy (25%), accruals quality (25%), analyst revisions (20%). Stack: BGE-large-en-v1.5 → ChromaDB, cross-encoder/nli-deberta-v3-base NLI, ProsusAI/finbert sentiment, vectorbt backtesting. Obsidian Terminal dashboard in Streamlit.

`LangGraph` `ChromaDB` `FinBERT` `DeBERTa` `BGE` `vectorbt` `Groq` `Streamlit`

---

### 🧬 TrialTransparency — Clinical Trial Validation Pipeline
*4-tier LLM rule engine*

Rebuilt from scratch: L1–L4 rule engine + LLM explainability layer (Groq Llama-3.3-70B / Gemini 2.0 Flash fallback), hash-keyed disk cache, 500 trial corpus with 127 injected errors (seed=42). Results: FORMAT_ERROR F1 = **0.926**, overall Recall = **0.961**, 13/13 pytest passing.

`Python` `Groq` `Gemini` `Pytest` `LLM Evaluation`

---

### 🗄️ Distributed Database Engine
*Java 17 · Systems Engineering*

B-tree + WAL + MVCC + LockManager + DeadlockDetector, Raft consensus protocol, JDBC driver via SPI. JMH benchmark: **1.82M ops/sec**, 146 passing tests.

`Java 17` `Raft` `MVCC` `JDBC` `JMH`

---

## 📚 Research & Publications

- 🏆 **MedSynGAN** — Best Paper Award, CVR 2025 @ NIT Goa · *Springer LNNS Vol. 1644*
- 📊 **Cross-Asset Investment Risk Analysis** — Co-authored with Wellington Management AVP · *ICSSAS 2025*
- ☁️ **Intelligent Cloud CRM** — *Int'l Conf. on Circuits, Systems and Simulation 2025*
- 🛡️ **Patent:** IoT-Enabled Smart Energy Meter · Application No. 202521004082 · Published Feb 2025

---

<div align="center">

**Open to AI Engineering, Machine Learning Engineering, Quantitative Development and Research Opportunities.**

**India · Dubai · Singapore · Europe · USA**

*For full experience & certifications, visit my [LinkedIn](https://www.linkedin.com/in/aryadoshii/) or [Portfolio](https://v0-arya-portfolio.vercel.app/).*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>

</div>

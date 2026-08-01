# Hi, I'm Derin 👋
 
### Statistics Undergraduate @ UNILAG · AI/ML Engineer · Fullstack Engineer
 
I build end-to-end systems — from FastAPI backends and ML pipelines to 3D React frontends. I care about shipping things that actually work in production, not just running in a notebook.
 
---
 
## 👤 About Me
 
- 🏫 Second-year **Statistics student** at the **University of Lagos (UNILAG)**, CGPA 3.72
- 🤖 Dual track: **AI/ML Engineering** (RAG systems, classification pipelines, LLM integration) + **Fullstack Engineering** (FastAPI, React, PostgreSQL, Redis)
- 🛠️ Building on an **M1 MacBook Air** in **VS Code**, deploying to Railway and Vercel
- 🎯 Long-term goal: ML Architect — hybrid/remote role, converting SIWES to a full-time offer
---
 
## 🧠 Languages & Tools
 
### 💻 Core Languages
[![Skills](https://skillicons.dev/icons?i=py,javascript,rust,r,java,html,css)](https://skillicons.dev)
 
### ⚙️ Backend & Infrastructure
[![Skills](https://skillicons.dev/icons?i=fastapi,postgres,redis,celery)](https://skillicons.dev)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=python&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-4B8BBE?style=for-the-badge&logo=python&logoColor=white)
![asyncpg](https://img.shields.io/badge/asyncpg-336791?style=for-the-badge&logo=postgresql&logoColor=white)
 
### 🎨 Frontend
[![Skills](https://skillicons.dev/icons?i=react,vite,threejs)](https://skillicons.dev)
![React Three Fiber](https://img.shields.io/badge/React%20Three%20Fiber-000000?style=for-the-badge&logo=three.js&logoColor=white)
![GLSL](https://img.shields.io/badge/GLSL%20Shaders-5586A4?style=for-the-badge&logo=opengl&logoColor=white)
 
### 🧪 AI/ML & Data Science
[![Skills](https://skillicons.dev/icons?i=sklearn)](https://skillicons.dev)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=python&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Gemini](https://img.shields.io/badge/Gemini%20API-4285F4?style=for-the-badge&logo=google&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![IBM SPSS](https://img.shields.io/badge/IBM%20SPSS-054ADA?style=for-the-badge&logo=ibm&logoColor=white)
 
### 🚀 Tooling & Deployment
[![Skills](https://skillicons.dev/icons?i=git,github,vscode,streamlit)](https://skillicons.dev)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Resend](https://img.shields.io/badge/Resend-000000?style=for-the-badge&logo=mail&logoColor=white)
 
---
 
## 📂 Projects
 
### 🌐 [E-commerce Price Intelligence Engine](https://github.com/oluwaisrael/ecommerce-price) — *Fullstack · AI/ML*
A live price tracking system for Nigerian e-commerce (Jumia & Jiji) with a 3D galaxy visualization frontend.
 
**Backend:** FastAPI + PostgreSQL (asyncpg) scraping real product listings via cloudscraper, with Celery + Redis handling scheduled 6-hour price checks and Resend delivering email alerts on price drops.
 
**Frontend:** React 19 + Vite with a React Three Fiber "PriceUniverse" scene — two spiral galaxies (Jumia in orange, Jiji in cyan) rendered with custom GLSL shaders (FBM noise, domain warping, curl noise, 43k instanced stars), 60fps on M1.
 
`FastAPI` `PostgreSQL` `Redis` `Celery` `React 19` `React Three Fiber` `GLSL` `cloudscraper` `Resend`
 
---
 
### 🔐 [Auth Service](https://github.com/oluwaisrael/auth-service) — *Backend*
Production-grade authentication microservice — built as a standalone, reusable backend module.
 
**V1 Ships:** Register, login, refresh token, logout, get/update profile, change password — all 7 endpoints live. UUID primary keys, hashed refresh tokens stored in Redis, Pydantic v2 validation, schemas never expose `hashed_password`.
 
`FastAPI` `PostgreSQL` `SQLAlchemy 2.0 async` `asyncpg` `Alembic` `Redis` `Passlib/bcrypt` `python-jose` `Pydantic v2`
 
---
 
### 🤖 [UniRAG: Hybrid RAG Academic Assistant](https://github.com/oluwaisrael/rag-course-app) — *AI Engineering*
A retrieval-augmented chatbot that answers questions grounded strictly in uploaded university lecture materials, with page-level citations.
 
**Architecture:** Dual-index hybrid retrieval — dense semantic search via `sentence-transformers` (FAISS) + sparse BM25 keyword matching — merged and reranked with a cross-encoder (`ms-marco-MiniLM-L-6-v2`) before passing top results to **Gemini 2.5 Flash** for grounded generation. Live PDF upload via Streamlit with Wikipedia fallback.
 
🌐 [Launch App](https://unirag-trpvefapprewkjzrpsndcbw.streamlit.app/)
 
`FAISS` `BM25` `sentence-transformers` `cross-encoder` `Gemini 2.5 Flash` `Streamlit`
 
---
 
### 🧠 [Neural Network from Scratch](https://github.com/oluwaisrael/neural-network-from-scratch) — *ML Fundamentals*
A fully connected neural network built in pure NumPy — no frameworks. MNIST handwritten digit recognition implemented from first principles: forward propagation, backpropagation, gradient descent, ReLU + Softmax activations. ~85.6% training accuracy after 500 iterations.
 
`NumPy` `Python` `Jupyter`
 
---
 
### 📉 [Customer Churn Prediction](https://github.com/oluwaisrael/customer-churn-prediction) — *ML*
XGBoost classification pipeline targeting telecom churn. Handled major class imbalances and optimized decision thresholds to hit **68% churner recall** with interactive feature importance visualizations.
 
`XGBoost` `Pandas` `Streamlit`
 
---
 
### 🎧 [Music Hit Predictor](https://github.com/oluwaisrael/Music-Hit-Predictor) — *ML*
Evaluated whether Afrobeats track popularity is predictable from acoustic features. Pivoted from Spotify API (post-2024 access restrictions) to Kaggle, ran rigorous 5-fold CV, and honestly reported a **null result** — 57.3% LogReg vs. 55.2% baseline. The science said no; the writeup says why.
 
🌐 [Launch App](https://music-hit-predictor-kxitaremaxmairznaqbxuy.streamlit.app/)
 
`LogReg` `Pandas` `Streamlit`
 
---
 
### 🚢 [Titanic Survival Prediction](https://github.com/oluwaisrael/titanic-survival-prediction) — *ML*
Classic benchmark — cleaned messy demographic subsets, handled categorical encoding, compared Logistic Regression vs Random Forest to hit a verified **81% accuracy** floor.
 
`sklearn` `Pandas` `Jupyter`
 
---
 
## 📈 2026 Roadmap
 
| Track | Status |
|---|---|
| AI Engineer path (roadmap.sh) | 50% complete — LLM Fundamentals, Prompt & Context Engineering done |
| IBM SkillsBuild Data Fundamentals | In progress |
| freeCodeCamp Scientific Computing with Python | ✅ Certified |
| Kaggle: Intro to ML, Intermediate ML, Pandas | ✅ All certified |
| Rust (45 min/day) | In progress |
| SIWES Industrial Placement (STA299) | Targeting AI/ML or Fullstack role |
| TAG Ecosystem (Lagos AI/ML community) | Active member — AI Engineering + Applied AI tracks |
 
**Next milestone:** Job-ready as an AI/ML + Fullstack Engineer by Q4 2026 — targeting SIWES conversion to full-time.
 
---
 
## 🤝 Let's Connect
 
- 💼 **LinkedIn:** [linkedin.com/in/adeoti-israel-a10503262](https://linkedin.com/in/adeoti-israel-a10503262)
- 🛠️ **GitHub:** You're already here — explore the repos and drop a ⭐ if something's useful!
 

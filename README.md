# Sophie Lin (Ao Lin)

**BS Computer Science @ NYU Abu Dhabi** | Double Minor in Engineering & Applied Mathematics | GPA: 3.85

I build production systems that work — from multi-service cloud deployments to ML pipelines on HPC clusters. Currently focused on full-stack engineering, applied ML, and adaptive learning systems.

[![Portfolio](https://img.shields.io/badge/Portfolio-sophie--l--l.github.io-00d4ff?style=flat-square)](https://sophie-l-l.github.io/)
[![LinkedIn](https://www.linkedin.com/in/ao-lin-859725262/)](https://www.linkedin.com/in/ao-lin-859725262/)
[![Email](https://img.shields.io/badge/Email-al7855%40nyu.edu-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:al7855@nyu.edu)

---

## Production Software

### [EduCode](https://github.com/Sophie-l-l/capstone) — Adaptive Learning Platform for Programming Education
A three-service platform (Next.js frontend, Express API, FastAPI AI service) that classifies student coding errors using an academic framework (IEEE 1044-2009) and tracks skill mastery through Bayesian Knowledge Tracing.

- 60+ rule-based error patterns with Gemini LLM fallback and 768-dim embedding deduplication
- Real-time instructor analytics: at-risk detection, error clustering, KC mastery heatmaps
- Deployed on Google Cloud Run + Vercel with PostgreSQL (Cloud SQL)

Tech: Next.js 16, React 19, Express, FastAPI, Prisma, PostgreSQL, Google Gemini, Docker\
Best for: **Full-Stack SWE, EdTech, AI/ML Engineering**

> [Live Demo](https://educode-adaptive-platform.vercel.app) | [Source Code](https://github.com/Sophie-l-l/capstone)

---

### [WorldBite](https://github.com/Sophie-l-l/WorldBite) — E-Commerce Platform with Enterprise Patterns
Production backend with circuit breaker, retry + exponential backoff, multi-tier rate limiting, and structured observability.

- Prometheus-compatible metrics, Winston logging with correlation IDs, real-time health dashboards
- Full commerce flow: cart, checkout, returns/refunds, partner CSV catalog ingestion, RBAC
- Docker multi-stage build (~150MB), Vitest + Supertest test suites

Tech: Node.js, TypeScript, Express, SQLite/PostgreSQL, Docker\
Best for: **Backend SWE, Platform Engineering, Infrastructure**

---

### [FreshtiqChef](https://github.com/Sophie-l-l/FreshtiqChef) — Mobile Food Quality Inspection App
Cross-platform Flutter app for food quality inspectors with a Tinder-style swipe interface, real-time Socket.io notifications, and atomic batch claiming to prevent race conditions across inspectors.

- Clean architecture with 15 API service classes, Riverpod state management, and Freezed immutable models
- Dio interceptor chain: JWT injection, 401 auto-recovery with token refresh, structured request logging
- Optimistic UI updates with automatic rollback, multi-step OTP auth, Excel export with date filtering
- 12,500+ lines of Dart across 69 files, compiled release APK shipped

Tech: Flutter/Dart, Riverpod, Dio, Socket.io, GoRouter, Freezed, Material Design 3\
Best for: **Mobile Engineering, Consumer Apps, Startup**

---

## Machine Learning & Data

### [Jane Street Market Prediction](https://github.com/Sophie-l-l/jane-street-market-prediction) — Kaggle Silver Medal, Top 4%
Ensemble of LightGBM, XGBoost, CatBoost, and a custom PyTorch Lightning neural network for real-time financial prediction on 47M+ samples.

- 5-fold DNN ensemble with custom R-squared loss and confidence calibration
- Feature engineering: lagged signals, smoothed aggregations across 79 base features
- Final score: 0.0081 | Rank: 109/3,412 teams

Tech: PyTorch Lightning, XGBoost, LightGBM, CatBoost, Polars, NumPy\
Best for: **ML Engineering, Quantitative Finance, Data Science**

> [Repository](https://github.com/Sophie-l-l/jane-street-market-prediction)

---

### [ML Algorithms from Scratch](https://github.com/Sophie-l-l/ML-from-scratch) — Applied Machine Learning Coursework
Implementations of core ML algorithms using only NumPy — no sklearn model calls.

- Linear & Logistic Regression, Decision Trees, SVMs, K-Means Clustering, Neural Networks
- Complete training loops, gradient descent variants, cross-validation from scratch

Tech: Python, NumPy, Matplotlib\
Best for: **ML Engineering, Research**

---

## AI & Research

### [MyoMetricsMRI](https://github.com/Sophie-l-l/myomagic) — AI-Powered DMD Early Detection (Product Manager) | [mMEDCON](https://www.mmedcon.com)
Product Manager for MyoMetricsMRI (M³), part of the mMEDCON project — an AI-powered MRI analysis platform targeting Duchenne Muscular Dystrophy early detection. Led the application and market research that got us into the **NYU 2025 Summer Startup Sprint** (1 of 17 teams selected).

- Led market research, competitive analysis, and prepared the accelerator application
- Conducted 34 customer discovery interviews with physicians from NYU Langone Radiology and Akron Children's Hospital
- Defined product roadmap, go-to-market strategy, and built investor pitch decks
- Co-founder later selected for **NYU Female Founders Fellowship** (Fall 2025, 1 of 9 fellows)

Tech: React, TypeScript, Vite, Tailwind CSS\
Best for: **Product Management, HealthTech, AI, Startup**

### Vision-Language Navigation for Blind Users — Research Assistant *(Ongoing)*
Fine-tuning vision-language models (VGGT + Depth Anything V2 + Qwen2.5-VL) on 219 walking videos for urban blind navigation. NYU Abu Dhabi, HPC (A100/V100).

Best for: **AI/ML Research, Computer Vision**

### [NomNom](https://github.com/Sophie-l-l/nomnom) — AI Therapy Chatbot
LangChain + GPT-4o-mini with BufferMemory for context-aware therapeutic dialogue.

> [Demo Video](https://youtu.be/ppIAHSyNp_8) | [Source Code](https://github.com/Sophie-l-l/nomnom)

---

## Professional Experience

**MyoMetricsMRI (mMEDCON)** — Product Manager (May – Sep 2025)
Led market research and accelerator application that got the team into [NYU Summer Startup Sprint 2025](https://entrepreneur.nyu.edu/resource/startup-sprint-student/) (1 of 17 teams). Conducted 34 customer discovery interviews, defined product roadmap, and built investor pitch decks for AI-powered DMD diagnostics.

**China-Gulf Forum** — Tech & Innovation Team (Jan 2025 - Present)
Built the [official forum website](https://github.com/Sophie-l-l/china-gulf-forum); organized hybrid international conference (500+ attendees) with speakers from UNOOSA and TII.

**Viva La Munich** — IT Intern (Jan - May 2024)
Developed user-tailored event database systems and architecture.

---

## Technical Skills

| | |
|---|---|
| **Languages** | TypeScript, JavaScript, Python, Dart, SQL, HTML/CSS |
| **Frontend** | React, Next.js, Flutter, Tailwind CSS, Framer Motion |
| **Backend** | Node.js, Express, Flask, FastAPI, Prisma, Knex |
| **AI/ML** | PyTorch, XGBoost, LightGBM, LangChain, Google Gemini, scikit-learn |
| **Databases** | PostgreSQL, MongoDB, SQLite |
| **Cloud** | Google Cloud (Run, SQL, Build), Vercel, Docker, GitHub Actions, SLURM/HPC |
| **Patterns** | Circuit Breaker, Rate Limiting, Observability, JWT/RBAC, BKT |

---

**New York University Abu Dhabi** — BS Computer Science | Double Minor: Engineering & Applied Mathematics | GPA: 3.85 | May 2026

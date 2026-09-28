<p align="center"><img src="terminal-card.svg" alt="Hem Patel terminal banner" /></p>

# Hem Patel

**AI/ML engineer in training. I build RAG systems, evaluation harnesses and ML services, and I publish the numbers, including the ones that don't look good.**

B.E. Computer Engineering · IIT Mandi (AI-DS), two undergraduate degrees in parallel.

[LinkedIn](https://www.linkedin.com/in/hem-patel-02b215377) · [patelhem60@gmail.com](mailto:patelhem60@gmail.com)

**Currently:** shipping small AI/ML builds, learning in public, **open to internships**.

---

## Projects

### [RAG QA Chatbot](https://github.com/Hem60/RAG-CHAT-BOT): fully local retrieval-augmented QA over PDFs

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-vector%20search-0467DF)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?logo=huggingface&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

Ask questions over technical PDFs (built for Data Structures notes). CPU embeddings (`all-MiniLM-L6-v2`) → FAISS index → `gemma-2-9b-it` for grounded answers, on a 100% free-tier stack.

- Refuses to answer when the documents don't contain the answer.
- **LLM-as-judge eval harness** that reports errors separately: 10 questions attempted, 6 scored, 4 errored → **3.5/5 on scored, 2.5/5 penalised**.

### [Movie Recommender](https://github.com/Hem60/MOVIE_RECOMMENDER): item-based collaborative filtering

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

MovieLens 100k, cosine-similarity recommender with genre filtering, evaluated with **Precision@10**, served through a FastAPI REST API and a web UI, containerised with Docker.

### [Iris Predictor](https://github.com/Hem60/IRIS-PREDICTOR): end-to-end MLOps pipeline

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

RandomForest classifier (~96% test accuracy) behind a Flask + Gunicorn API and interactive UI. Pytest on every push, Docker image built in CI and pushed to GHCR, deployed on Render.

---

## Stack

```
languages   Python · HTML · CSS · JavaScript
ai/ml       RAG pipelines · LLMs · embeddings · FAISS · scikit-learn · evaluation harnesses
backend     FastAPI · Flask · Docker · GitHub Actions (CI/CD)
tools       Git · GitHub · VS Code · Claude
```

---

> **Note:** my **raksha-ai** project (team finance AI assistant) is a **private repository**, so it isn't linked here.
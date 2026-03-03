# 🌾 Sohr.ai — Santali AI Platform

**Sohr.ai** (pronounced **Sohr-ai**, from the Santali harvest festival *Sohrai*) is a complete **Santali AI platform** —  
combining language models, embeddings, speech, and tooling with a simple API for developers.

Santali (sat, Ol Chiki) has over 7M speakers, but almost no production‑ready AI support.  
Sohr.ai aims to change that with **open models, open data, and an open ecosystem**.

---

## 🔍 What is Sohr.ai?

Sohr.ai is:

- A **core set of models** for Santali:
  - Text generation and understanding (chat, completion, Q&A)
  - Embeddings for search, clustering, and recommendations
  - Spellchecking, normalization, and grammar assistance
  - (Planned) Speech recognition (ASR) and text‑to‑speech (TTS)

- A **developer platform**:
  - Hosted **HTTP API** for inference
  - Python / JavaScript SDKs
  - CLI tools for local workflows and automation

- An **open ecosystem**:
  - Public datasets and preprocessing pipelines
  - Benchmarks for Santali language tasks
  - Community contributions and research collaborations

---

## 🎯 Vision

Our long‑term vision:

- Make Santali **a first‑class language in AI** — as easy to integrate as English or Hindi.
- Enable developers to build **Santali‑first products**: education, jobs, content, government access.
- Provide **transparent, well‑documented datasets and models** that anyone can inspect, improve, and deploy.
- Serve as a **reference blueprint** for other Adivasi and low‑resource languages.

---

## 🧱 Platform Components

Planned components of Sohr.ai:

- **Models**
  - Base language model for Santali and code‑mixed text
  - Instruction‑tuned chat model for interactive use
  - Embedding model for search and retrieval
  - Task‑specific models (spellcheck, NER, classification, translation)
  - (Future) ASR/TTS models for spoken Santali

- **Data**
  - Curated text corpus (Ol Chiki + Roman)
  - Parallel English ↔ Santali datasets
  - Domain‑specific corpora (education, govt schemes, jobs, culture, lyrics)
  - Clear documentation of sources, licenses, and preprocessing

- **APIs & Tools**
  - REST API for all models
  - SDKs (Python/JS) and example clients
  - Command‑line tools for:
    - Proofreading and normalization
    - Transliteration
    - Dataset cleaning and evaluation

---

## 🚧 Status & Roadmap

> Sohr.ai is in **early development**. APIs, models, and interfaces will evolve quickly.

Planned roadmap (high‑level):

- **v0.1** – Public text corpus and preprocessing scripts  
- **v0.2** – Spellcheck / normalization model + basic API  
- **v0.3** – Embeddings + search toolkit  
- **v0.4** – EN ↔ Santali translation and chat‑style model  
- **v1.0** – Stable platform: hosted API, SDKs, documentation, and reference apps

Check the [ROADMAP.md] (coming soon) for technical details and timelines.

---

## 🚀 Getting Started (early preview)

> Example interface — exact package and model names will be finalized before release.

### Install SDK

```bash
pip install sohr-ai

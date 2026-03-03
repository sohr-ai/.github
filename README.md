# 🌾 Sohr.ai — Sohrai Santali LLM & NLP Stack

**Sohr.ai** (pronounced **Sohr-ai**, from the Santali harvest festival **Sohrai**) is an open initiative to build the first complete **LLM and NLP ecosystem for the Santali language (sat, Ol Chiki script)**.

For 7M+ Santali speakers, there is still **no** production-ready language model, spellchecker, or translation system.  
Sohr.ai aims to change that — with **open data, open models, and open tools**.

---

## ✨ Vision

- Build a **Santali-native language model** that understands Ol Chiki, Roman Santali, and code-mixed text.
- Provide **practical tools**: spellcheck, grammar correction, translation, summarization, search.
- Create a **shared public dataset** and contribution framework so any developer/researcher can extend the ecosystem.
- Make Santali AI **as easy to use** as English models: one pip install, one API call.

---

## 🧱 Project Components

Planned core components of Sohr.ai:

- **📚 Corpus**
  - Clean text corpus (Ol Chiki + Roman)
  - Parallel EN ↔ Santali data
  - Domain-specific subsets (education, govt schemes, jobs, culture, lyrics)

- **🧠 Models**
  - Tokenizer for Santali (Ol Chiki + Roman)
  - Base language model (fine-tuned from multilingual LLM)
  - Task-specific heads (spellcheck, NER, classification, translation)

- **🛠 Tools & APIs**
  - Python SDK (`sohr-ai`)
  - REST inference API
  - CLI tools for local use (proofreading, transliteration, dataset cleaning)

- **🌍 Community**
  - Contribution guidelines for new data
  - Benchmarks and leaderboards for Santali tasks
  - Example apps: keyboard integration, content moderation, job listing translation

---

## 🚧 Status

> This project is under **active early development**.

Planned milestones:

- [ ] v0.1 – Public dataset + basic tokenizer  
- [ ] v0.2 – Spellchecker & normalization model  
- [ ] v0.3 – EN ↔ Santali translation model  
- [ ] v0.4 – Instruction-tuned Santali LLM (chat-style)  
- [ ] v1.0 – Production-ready API, docs, and reference apps

---

## 🚀 Getting Started

> These commands are **provisional** and will be updated once the first release is published.

### Installation

```bash
pip install sohr-ai

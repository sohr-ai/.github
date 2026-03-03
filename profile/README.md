# 🌾 Sohr.ai — Santali AI Platform

Sohr.ai is an open-source ecosystem dedicated to making the Santali language a first-class citizen in the AI world. Inspired by the Sohrai harvest festival, we bridge Adivasi cultural heritage with modern neural architectures.

## 🎯 Key Pillars

* **🧠 Neural Foundations:** Open-source LLMs and embeddings optimized for Ol Chiki (Unicode U+1C50–U+1C7F).
* **🔓 Data Sovereignty:** Curating the largest open Santali parallel corpus for community-led research.
* **🛠️ Developer Tools:** High-performance SDKs and APIs for localized Adivasi tech solutions.

## 🧱 Project Structure

This monorepo is designed for full visibility across service boundaries.
```
.
├── 🤖 models/      # Target: Weights, LoRA adapters (ByT5, IndicTrans2)
├── 📊 datasets/    # Target: Normalization pipelines (Ol Chiki/Roman)
├── 🌐 api/         # Target: FastAPI/Node Inference Gateway
├── 📦 sdk/         # Target: Multi-language client libraries
│   ├── python/     # Research-focused library (sohr-ai)
│   └── js/         # Web/Mobile SDK (@sohr-ai/sdk)
├── 🐚 cli/         # Target: Normalization & cleanup tools
└── 📓 examples/    # Target: RAG and translation demos
```
## 🎨 Linguistic & Cultural Context

The Ol Chiki script, created by Pandit Raghunath Murmu in 1925, is a "true alphabet" derived from natural shapes, perfectly capturing Santali phonology.

### The Five-Day Sohrai Ritual as a Technical Framework
We map our development to the five days of the Sohrai harvest festival:

| Day | Ritual | Dev Phase | Technical Objective |
| :--- | :--- | :--- | :--- |
| D1 | Um Hilok | Cleaning | Sanitizing raw corpora & script normalization. |
| D2 | Dakaka | Baselines | Tokenization and initial model architecture. |
| D3 | Khuntao | Training | High-compute training of ByT5 models. |
| D4 | Jaley | Integration | Deploying SDKs and opening the community API. |
| D5 | Haako Katkom | Evaluation | Community feedback loops and stable release. |

## 🚧 Status & Roadmap

**Current Status:** 🔴 Organization Setup Phase. We are currently recruiting contributors and setting up the foundational Um Hilok (Data Cleaning) pipelines.

### 📍 Technical Roadmap
* **v0.1 — Foundations:** Release Santali Tokenizer and datasets/cleaning logic.
* **v0.2 — Literacy:** Initial release of the Spellcheck CLI and script converters.
* **v0.3 — Intelligence:** First release of native Santali Embedding models.
* **v1.0 — Ecosystem:** Stable release of Hosted API and multi-language SDKs.

## 📊 Technical Specifications

### Santali Parallel Corpus Statistics
We target the following metrics for initial model proficiency:

| Split | Sentences | English Tokens | Santali Tokens |
| :--- | :--- | :--- | :--- |
| Train Set | 104,451 | 1,082,726 | 1,036,528 |
| Validation | 1,503 | 14,850 | 16,001 |
| **Aggregate** | **~108k** | **~1.1M** | **~1.1M** |

### ByT5 Finetuning Configuration
Byte-level models are prioritized to handle the unique characters of Ol Chiki without "unknown token" errors.

| Parameter | Planned Value |
| :--- | :--- |
| Architecture | `google/byt5-small` |
| Learning Rate | $3 \times 10^{-4}$ |
| Batch Size | 64 |
| Precision | Mixed (fp16) |

## 🚀 Standardized API Interface
The platform aims for a seamless, "copy-and-run" developer experience.

```python
from sohr import SohrClient

client = SohrClient(api_key="YOUR_KEY")

# 1. Grammar & Script Correction
text = "ᱟᱢᱟᱹᱨ ᱠᱟᱱ ᱨᱮᱜᱟᱜᱽ"
res = client.correct(text) # -> Corrected Ol Chiki

# 2. Semantic Search Embeddings
vector = client.embed("ᱥᱳᱦᱨᱟᱭ ᱯᱮᱨᱥᱴ").vector
```

## 🤝 Contributing

We follow [Conventional Commits](https://www.conventionalcommits.org/). As we are in the early stages, help with data cleaning and tokenization is most needed!

* **Fork** the repository.
* **Create a branch**:
  1. Use the naming convention `feat/` or `fix/`.
  2. Implement your changes.
* **Open a Pull Request** to merge your contributions.

## 🧾 License

* **Code:** [LICENSE](LICENSE)
* **Models/Data:** [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) or [LICENSE-DATA](LICENSE-DATA) per asset.

*Built with ❤️ for the Santali Community. 🌾*

# Poli-IA: Institutional AI Assistant 🏛️📚

[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/LlamaIndex-RAG-orange.svg)](https://www.llamaindex.ai/)
[![UI](https://img.shields.io/badge/Gradio-Interface-brightgreen.svg)](https://gradio.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An advanced Retrieval-Augmented Generation (RAG) assistant powered by **Llama** (via Groq API) and **LlamaIndex**, developed as the final project for the Module 1 Hackathon. This system functions as a dual-purpose institutional guide, handling administrative inquiries (school services, events) and academic research support (thesis exploration).

---

## 🌟 Key Features

* **Dynamic RAG Engine:** Indexes local TXT and PDF documents from the repository to ensure zero hallucinations and real-time data retrieval.
* **High-Performance Inference:** Utilizes the `openai/gpt-oss-20b` model via Groq for ultra-fast response times.
* **Interactive UI:** Features a clean, user-friendly chat interface built with Gradio.
* **Strict Guardrails:** Configured with a specialized system prompt enforcing professional tone, mandatory emojis for accessibility, and strict adherence to provided source context.

---

## 📂 Repository Structure

```text
├── administrativo.txt
├── tesis/
│   └── thesis_example.txt
└── README.md}
```

## 🛠️ Built With
- Groq: Fast LLM inference engine.
- LlamaIndex: Framework for connecting custom data sources to LLMs.
- Gradio: Python library for building machine learning web interfaces.
- HuggingFace: Open-source embedding models (bge-small-en-v1.5).

## 📄 License
This project is open-source under the MIT License.

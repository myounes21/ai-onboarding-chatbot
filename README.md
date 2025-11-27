# 🤖 AI Onboarding Chatbot (RAG System)

A Retrieval-Augmented Generation (RAG) chatbot designed to provide instant, factual answers regarding company onboarding documents and FAQs. This project demonstrates modern LLM integration, relying on fast, cost-effective, open-source-aligned APIs for both embeddings and generation.

---

## ✨ Features

* **Factual Retrieval:** Uses the Cohere Embeddings API to search document knowledge base.
* **Rapid Generation:** Leverages the Groq API for extremely fast, low-latency LLM responses (via Llama 3).
* **Traceable:** Integrated with LangSmith for full observability and debugging of the RAG chain.
* **Secure:** Uses `.env` for all secrets and `.gitignore` to prevent secret leaks.

## 🛠️ Tech Stack

* **Framework:** LangChain (LCEL)
* **Embeddings (E):** Cohere API (Free Tier)
* **LLM (G):** Groq API (Llama 3 / Mixtral)
* **Vector Store:** ChromaDB
* **UI:** Streamlit
* **Environment:** Python (venv)

## 🚀 Setup & Installation

These steps assume you have a working Python 3 environment and have created a virtual environment (`venv`).

### 1. Dependencies

Install all necessary packages using your resolved `requirements.txt` file:

```bash
pip install -r requirements.txt --upgrade
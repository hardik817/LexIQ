# LexIQ
An offline-ready legal QA system using FAISS-based retrieval, locally hosted LLaMA 3 3B, and Cohere reranking to provide accurate, citation-backed legal answers.
# LexIQ: Legal Question Answering with LLaMA 3, FAISS & Cohere Rerank

LexIQ is a product-focused, open-source Retrieval-Augmented Generation (RAG) pipeline designed for **legal question answering**. It leverages:

- ⚖️ **LLaMA 3 (3B)** as a local, instruction-tuned language model for generating detailed answers.
- 🔍 **FAISS** for fast dense vector retrieval of legal documents (e.g., case law, clauses, holdings).
- 🧠 **Cohere ReRank** to prioritize and rerank the most contextually relevant documents before answering.

## ⚖️ Key Features

- **Locally hosted LLaMA 3.2B** model for secure inference.
- **RAG pipeline** with FAISS for fast, vector-based legal document retrieval.
- **Cohere Rerank** to prioritize the most relevant results.
- **Claude AI** to generate smart tags (like `implied warranty`, `due process`, `Article 11 ECHR`).
- Clean, responsive chatbot UI with suggested legal questions.

---

## 🚀 Example Questions

- “Can I be arrested for peaceful protest without permission?”
- “Is this user agreement clause legally unfair?”
- “Does the landlord’s failure to fix heating justify withholding rent?”
- “Does this arrest violate Article 11 of the ECHR?”

### 📦 Tech Stack

- Python 3.10+
- LangChain (Retrieval + Chains)
- FAISS (Vector index backend)
- Cohere Python SDK (Reranking)
- HuggingFace Transformers + LLaMA-3 (local)
- Claude AI


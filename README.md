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

## 📚 About the LexGLUE Dataset

[LexGLUE (Legal General Language Understanding Evaluation)](https://huggingface.co/datasets/coastalcph/lex_glue) is a benchmark dataset designed for evaluating legal NLP models. It includes legal case data from the European Court of Human Rights and other legal bodies.

### LexGLUE tasks used:

- **CaseHOLD**: Predicts the correct legal holding among multiple choices.
- **EUR-Lex**: Multi-label classification for EU legislative documents.
- **LEDGAR**: Clause classification in commercial legal contracts.

Your chatbot is trained on **CaseHOLD**, making it ideal for reasoning over precedents, holdings, and statutory interpretation.

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


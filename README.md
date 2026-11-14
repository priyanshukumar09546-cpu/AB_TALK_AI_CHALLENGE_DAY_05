# 🔍 Mini Semantic Search Engine (Day 5 - AI Challenge)

A lightweight **Semantic Search Engine** built in Python that retrieves relevant sentences based on **contextual meaning** rather than exact keyword matching. This project demonstrates the core retrieval mechanism behind modern **RAG (Retrieval-Augmented Generation)** pipelines and AI-powered recommendation systems.

---

## 🚀 Overview

Traditional keyword search fails when a user's query uses different wording than the stored documents. By converting text into dense vector embeddings and measuring **Cosine Similarity**, this mini search engine understands user intent and surfaces the most contextually relevant results.

### Key Features
* **Custom Knowledge Base:** 20 curated sentences covering Artificial Intelligence, Machine Learning, and modern tech concepts.
* **Dense Vector Embeddings:** Uses the `all-MiniLM-L6-v2` model from `sentence-transformers` to generate 384-dimensional embeddings.
* **Top-K Semantic Retrieval:** Computes cosine similarity between the query vector and document vectors to return the top 3 matches with similarity scores.
* **Side-by-Side Comparison:** Compares **Semantic Search** vs. **Keyword Search** on identical queries to highlight where exact word matching falls short.

---

## 🛠️ Tech Stack

* **Python 3**
* **Sentence-Transformers** (`all-MiniLM-L6-v2`)
* **Scikit-Learn** (`cosine_similarity`)
* **NumPy**

---

## ⚙️ Installation & Setup

1. Clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/<your-repo-name>.git
   cd <your-repo-name>

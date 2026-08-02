# 📚 Baseline Retrieval-Augmented Generation (RAG) System

A Retrieval-Augmented Generation (RAG) project that explores the limitations of a baseline RAG pipeline and demonstrates systematic improvements using better embeddings, optimized chunking, Max Marginal Relevance (MMR), and instruction-based response generation.

## 📖 Overview

Large Language Models (LLMs) often generate incorrect or outdated information because they rely only on their pre-trained knowledge. Retrieval-Augmented Generation (RAG) addresses this limitation by retrieving relevant information from external documents before generating a response.

This project implements a baseline RAG pipeline using educational documents related to Artificial Intelligence, Machine Learning, and Deep Learning, analyzes its shortcomings, and improves retrieval quality through multiple optimization techniques.

---

## 🎯 Objectives

- Build a baseline Retrieval-Augmented Generation pipeline.
- Analyze retrieval precision and response quality.
- Improve semantic retrieval using Sentence Transformers.
- Reduce redundant retrieval using Max Marginal Relevance (MMR).
- Optimize chunking strategy for better context retrieval.
- Generate structured and user-friendly responses.
- Reduce hallucinations using prompt engineering.

---

## 📂 Dataset

The project uses domain-specific educational documents covering:

- Artificial Intelligence
- Machine Learning
- Deep Learning

The documents are converted into machine-readable text before indexing.

---

## 🛠️ Technologies Used

- Python
- LangChain
- FAISS
- Sentence Transformers
- Hugging Face Embeddings
- Retrieval-Augmented Generation (RAG)
- Prompt Engineering

---

## ⚙️ Methodology

### Phase 1: Baseline RAG

The baseline pipeline consists of:

1. Document Loading
2. Text Chunking
3. Embedding Generation
4. FAISS Vector Database
5. Similarity Search (Top-K Retrieval)

Output:
- Raw retrieved text chunks

---

### Phase 2: System Improvements

Several enhancements were introduced:

- Advanced Sentence Transformer embeddings
- Max Marginal Relevance (MMR)
- Smaller chunk sizes
- Optimized retrieval depth
- Instruction-tuned language model
- Prompt engineering
- Hallucination reduction

These improvements significantly increased retrieval relevance and response quality.

---

## 🔬 Experimental Analysis

The baseline and improved systems were evaluated using:

- Factual queries
- Conceptual queries
- Comparative queries

Evaluation focused on:

- Retrieval relevance
- Retrieval diversity
- Response quality
- Hallucination reduction
- User-friendliness

---

## 📊 Comparison

| Feature | Baseline | Improved |
|----------|----------|-----------|
| Embedding Model | Default | Sentence Transformer |
| Retrieval Strategy | Top-K | MMR |
| Chunk Size | Large | Optimized |
| Response Generation | Raw Text | Structured Answers |
| Hallucinations | High | Reduced |
| Retrieval Diversity | Low | Improved |
| User Experience | Moderate | Better |

---

## 🚀 Key Improvements

✔ Better semantic retrieval

✔ Reduced redundant results

✔ Improved context relevance

✔ Structured answer generation

✔ Lower hallucination rate

✔ More reliable responses

---

## 📈 Results

The improved RAG pipeline demonstrated:

- Better retrieval precision
- Improved semantic matching
- Reduced repetitive retrieval
- More concise responses
- Lower hallucination frequency
- Better overall user experience

---

## 📌 Limitations

The system can still miss relevant information when retrieval fails, even if the required knowledge exists in the dataset.

Future work will focus on improving retrieval precision and hybrid retrieval techniques.

---

## 🔮 Future Improvements

- Hybrid Search (Dense + BM25)
- Cross-Encoder Re-ranking
- Query Expansion
- Multi-query Retrieval
- Knowledge Graph Integration
- Agentic RAG
- Evaluation Metrics (Recall@K, Precision@K, MRR)

---

## 📁 Project Structure

```
project/
│
├── data/
├── vector_db/
├── notebooks/
├── app/
├── embeddings/
├── README.md
└── requirements.txt
```

---

## 🎓 Learning Outcomes

Through this project, the following concepts were explored:

- Retrieval-Augmented Generation
- Vector Databases
- FAISS Indexing
- Sentence Embeddings
- Semantic Search
- Prompt Engineering
- Hallucination Reduction
- Information Retrieval

---

## 📜 License

This project is developed for educational and research purposes.

---

## 👨‍💻 Author

**Tanishq Tomar**

B.Tech CSE (AI & ML)

Interested in Data Science, Machine Learning, LLMs, Retrieval-Augmented Generation, and AI Research.

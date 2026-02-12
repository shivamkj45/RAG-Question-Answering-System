RAG Based Question Answering System
** PROJECT OVERVIEW

This project implements a beginner-level Retrieval Augmented Generation (RAG) system using LangChain and FAISS.

The system retrieves relevant information from a text-based AI knowledge source using semantic similarity search.

** DATASET

Type: TXT file

Source: Self-created AI notes

Topics covered:

Artificial Intelligence

Machine Learning

Deep Learning

NLP

Computer Vision

Applications

Limitations

** RAG ARCHITECTURE Text Dataset ↓ Text Chunking ↓ Embedding Model ↓ FAISS Vector Database ↓ User Query → Embedding ↓ Similarity Search ↓ Retrieve Top-K Chunks ↓ Formatted Answer

** TEXT CHUNKING STRATEGY

Chunk Size: 150

Chunk Overlap: 30

Reason:

Improve retrieval accuracy

Maintain context continuity

** EMBEDDING MODEL

Model: sentence-transformers/all-MiniLM-L6-v2

Reason:

Lightweight

Fast

Good semantic similarity performance

** VECTOR DATABASE

FAISS (Facebook AI Similarity Search)

Used for efficient similarity search of embeddings.

** TEST QUERIES

What is Artificial Intelligence?

Applications of AI?

What are limitations of AI?

** HOW TO RUN

Open Google Colab

Install required libraries

Run notebook step-by-step

Execute test queries

**FUTURE IMPROVEMENTS

Better chunking strategies

Hybrid search (BM25 + Vector Search)

Reranking models

Metadata filtering

Streamlit UI deployment


Better generative LLM integration

## RAG Architecture Diagram

RAG ARCHITECTURE
![RAG Architecture](rag_architecture.png)



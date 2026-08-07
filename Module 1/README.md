# Retrieval Augmented Generation (RAG) Application

Unlock the power of unstructured data by building intelligent search systems that ground LLMs in real, accurate information.

## 🎯 Project Overview

This project demonstrates how to harness 80% of the world's data—the unstructured portion—and transform it into actionable insights. Using Retrieval Augmented Generation (RAG), you'll build a system that intelligently searches through documents, PDFs, and transcripts to answer questions with factual accuracy and contextual relevance.

## ✨ Key Features

- **Hybrid Search Capabilities** — Combines keyword search (sparse vectors) and semantic search (dense embeddings) for comprehensive retrieval
- **Smart Re-ranking** — Automatically ranks results by relevance to eliminate noise and surface the most pertinent information
- **Cortex Search Integration** — Leverage Snowflake's enterprise search service to index and query unstructured data at scale
- **LLM-Powered Generation** — Augment LLM responses with grounded, retrieval-based evidence for accurate, hallucination-free answers
- **Quality Measurement** — Built-in evaluation metrics using LLM Judge to assess RAG performance and accuracy

## 🔧 What I Build

- End-to-end RAG pipeline using Cortex Search as the retriever in a Snowflake Notebook
- Document parsing and intelligent chunking using recursive character splitting
- Hybrid search combining dense embeddings and keyword matching
- Community support chatbot powered by FOMC Meeting Minutes (real-world example)
- Evaluation framework to measure retrieval and generation quality

## 🚀 Real-World Applications

From financial institutions analyzing earnings calls and contracts, to retailers understanding customer feedback, to education platforms leveraging classroom communications—RAG empowers organizations across every industry to turn unstructured data into competitive advantage.

---

**Built with:** Snowflake • Cortex Search • Cortex LLM • Vector Embeddings • Hybrid Search

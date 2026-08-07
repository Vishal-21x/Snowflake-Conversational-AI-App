# Text-to-SQL Application

Transform natural language questions into accurate SQL queries and get instant insights from your data.

## 🎯 Project Overview

This project demonstrates how Large Language Models can revolutionize data access by bridging the gap between business users and complex databases. Instead of waiting for analysts to write custom queries, users can ask questions in plain English and receive precise, actionable results in seconds.

## ✨ Key Features

- **Natural Language Queries** — Ask questions like "How much revenue did we make last year?" without writing SQL
- **Powered by Cortex Analyst API** — Leverage Snowflake's enterprise-grade LLM capabilities for accurate query generation
- **Snowflake Integration** — Seamlessly query your structured data with schema understanding and contextual mapping
- **User-Friendly Interface** — Built with Streamlit for an intuitive experience that democratizes data access

## 🧠 Why Cortex Analyst vs. Raw LLMs?

### The Problem with State-of-the-Art LLMs Alone:
Even the smartest LLMs struggle with semantic complexity:
- ❌ Lacks contextual understanding of dimension tables
- ❌ Missing joins between tables (returns numerical IDs instead of human-readable labels)
- ❌ No error correction mechanism for syntactic/semantic errors

### The Cortex Analyst Solution: Agentic Workflow
A sophisticated multi-stage intelligent pipeline:

1. **Classification Agent** — Determines if question is answerable with SQL
2. **Feature Extraction Agent** — Identifies question type (time series, year-over-year, etc.)
3. **Context Enrichment Agent** — Adds semantic model context relevant to the question
4. **SQL Generation Agents** — Array of LLMs each attempt to generate SQL
5. **Error Correction Agent** — Validates SQL syntax & semantics using Snowflake compiler
6. **Synthesizer Agent** — Produces final, optimized SQL

**Result:** Accurate, human-readable queries with proper joins and contextual intelligence ✅

## 🔧 What I Build

- Text-to-SQL engine using Cortex Analyst API in a Snowflake Notebook
- LLM-powered results interpretation to convert data back into natural language insights
- Streamlit frontend for end-users to interact with their data effortlessly

## 🚀 Why It Matters

Eliminates the tedious cycle of ad-hoc query requests, empowers business teams with self-service analytics, and transforms decision-making from hours to minutes.

---

**Built with:** Snowflake • Cortex Analyst API • LLMs • Streamlit

---

### Cortex Analyst 
<img width="1917" height="975" alt="image" src="https://github.com/user-attachments/assets/1ad5b721-f3f0-4d5d-9e4a-925f528b0090" />

---

### Why should you trust LLM-as-a-judge
[Benchmarking LLM-as-a-Judge for the RAG Triad Metrics ](https://www.snowflake.com/en/engineering-blog/benchmarking-LLM-as-a-judge-RAG-triad-metrics/) | Dive deep into the inner workings of RAG Triad LLM Judge evaluators including prompts and benchmark results. 

[Eval-Guided Optimization of LLM Judges for the RAG Triad](https://www.snowflake.com/en/engineering-blog/eval-guided-optimization-llm-judges-rag-triad/) | Learn more about how LLM judges can be benchmarked and optimized against human evaluations.


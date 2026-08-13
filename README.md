# RAG with LangChain

A practical implementation of Retrieval-Augmented Generation (RAG) using LangChain. This project demonstrates how to build a pipeline to chat with your own documents, allowing an LLM to retrieve context from specific data sources to provide accurate, grounded answers.

## Features
*   **Document Loading:** Easily ingest various file types (PDFs, Text, etc.).
*   **Chunking & Indexing:** Efficiently split text and create vector embeddings.
*   **Vector Database:** Integration with local or cloud-based vector stores.
*   **Retrieval Pipeline:** Custom retrieval logic for context-aware Q&A.
*   **Chain Integration:** Uses LangChain's LCEL (LangChain Expression Language) for a clean, modular pipeline.

## Prerequisites
Ensure you have the following installed:
*   Python 3.10+
*   [Poetry](https://python-poetry.org/) or `pip`

## Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/thusithakit/rag-with-langchain.git](https://github.com/thusithakit/rag-with-langchain.git)
cd rag-with-langchain
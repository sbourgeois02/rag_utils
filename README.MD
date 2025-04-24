# RAG Utils

This repository contains utilities for **RAG (Retrieval-Augmented Generation)** workflows. These tools are designed to simplify the transformation of source documents into a format suitable for use in vector databases.

The primary focus is on processing and preparing data for embedding models and subsequent storage/retrieval via vector search systems like Pinecone.

---

## ✅ Current Utilities

### 🔹 Chunker

The **Chunker** tool breaks down documents into small, manageable pieces to optimize performance with embedding models. It includes:
- Custom formatting rules
- Sentence overlap handling
- Word count limits to fit model token constraints

---

## 🧪 Planned Utilities

### 🔸 Upsertion Script

This upcoming utility will:
- Read chunked files
- Generate embeddings using an embedding model via API (e.g., OpenAI)
- Upsert (update/insert) the results into a vector database like Pinecone

### 🔸 Vector DB Pipeline

A unified pipeline that:
- Calls the Chunker and Upsertion Script
- Allows users to point to an input folder
- Automates the full workflow to populate a vector database with chunked, embedded data

---

## 📌 Purpose

These tools are intended to:
- Accelerate the development of RAG systems
- Standardize the chunking and embedding process
- Make working with vector databases easier and more modular

---

## 🛠️ Status

This project is actively being developed. Contributions, suggestions, and feedback are welcome!


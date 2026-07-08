# 📚 RAG Book Assistant

An AI-powered **Retrieval-Augmented Generation (RAG)** application that enables users to interact with PDF documents through natural language conversations. The application processes uploaded books, stores their semantic representations in a vector database, retrieves the most relevant information using advanced retrieval techniques, and generates context-aware responses with the help of Mistral AI.

## 🚀 Overview

RAG Book Assistant is designed to simplify information retrieval from large PDF documents. Instead of manually searching through hundreds of pages, users can upload a document and ask questions in plain English. The system retrieves the most relevant content from the document and uses a Large Language Model (LLM) to generate accurate, context-based answers.

## ✨ Key Features

- 📄 Upload and analyze PDF books and documents
- 🤖 Context-aware question answering using Retrieval-Augmented Generation (RAG)
- 🧠 Semantic search powered by Mistral AI Embeddings
- 💾 Persistent vector storage using ChromaDB
- 🔍 Intelligent document retrieval with Maximal Marginal Relevance (MMR)
- ✂️ Automatic document chunking for efficient retrieval
- 💬 Interactive and user-friendly Streamlit interface
- ⚡ Fast and relevant responses based only on uploaded document content

## 🛠️ Technologies Used

- **Python**
- **Streamlit**
- **LangChain**
- **Mistral AI**
- **Mistral AI Embeddings**
- **ChromaDB**
- **PyPDFLoader**
- **Recursive Character Text Splitter**
- **MMR (Maximal Marginal Relevance) Retrieval**
- **python-dotenv**

## 🧠 Core Concepts Implemented

- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- Semantic Search
- Vector Embeddings
- Vector Database Management
- Prompt Engineering
- Document Chunking
- Context-Aware Response Generation

## ⚙️ Project Workflow

The application follows a complete RAG pipeline:

- PDF document ingestion
- Text extraction and preprocessing
- Recursive text chunking
- Embedding generation using Mistral AI
- Storage of embeddings in ChromaDB
- Semantic retrieval using MMR
- Context injection into the LLM
- Accurate answer generation based on retrieved document context

## 🎯 Highlights

- Implements an end-to-end Retrieval-Augmented Generation pipeline.
- Uses semantic embeddings instead of traditional keyword-based search.
- Employs Maximal Marginal Relevance (MMR) retrieval to improve diversity and relevance of retrieved document chunks.
- Stores embeddings in a persistent ChromaDB vector database for efficient querying.
- Ensures responses are grounded in the uploaded document, reducing hallucinations.
- Built with a modular architecture for scalability and future enhancements.

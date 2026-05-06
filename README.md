# NLP Project: document-reader-nlp

## Overview
This project is a Retrieval-Augmented Generation (RAG) system that allows users to ask questions based on uploaded PDF documents. It extracts relevant text from educational materials and generates accurate answers using NLP techniques. The system is designed for question answering over domain-specific documents, especially electrical engineering concepts such as voltage, current, and resistance.

## Tech Stack
- Python
- Google Colab
- Hugging Face Transformers (FLAN-T5)
- SentenceTransformers (MiniLM embeddings)
- FAISS (vector similarity search)
- PyPDF (PDF text extraction)
- NumPy

## What I built
- Developed a PDF text extraction pipeline using PyPDF
- Implemented text chunking strategy for efficient retrieval
- Created semantic search system using FAISS vector database
- Built embedding pipeline using SentenceTransformer model
- Designed a question-answering system using FLAN-T5 model
- Integrated a full RAG pipeline (Retrieve → Generate → Answer)

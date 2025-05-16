# Computer Diagnostics Chatbot

## Overview
This project is an NLP-powered chatbot designed to assist with computer troubleshooting across 14 common scenarios. It leverages semantic similarity matching with SentenceTransformer embeddings to understand user queries and provide accurate responses.

## Features
- Utilizes SentenceTransformer for semantic matching with a confidence threshold of 0.7
- Incorporates a fallback to a large language model (LLLM) using Ollama and the Gemma3 model for improved answer accuracy
- Semantic matching pipeline uses a single pre-trained transformer model with a domain relevance detection threshold of 0.2
- Stores chat context and uploaded PDF documents for an enhanced user experience and continuity
- Built with Streamlit for an interactive web interface

## Technologies Used
- SentenceTransformer (all-MiniLM-L6-v2)
- Ollama LLM (Gemma3)
- Langchain framework for vectorstore and retrieval-based QA
- FAISS for vector similarity search
- PyMuPDF for PDF loading and text extraction
- Streamlit for UI

## Usage
1. Upload a PDF document relevant to the diagnostics.
2. Interact with the chatbot to ask troubleshooting questions.
3. Chat history and documents persist during the session for context-aware responses.

---

## Author
Nirant Bendale

---

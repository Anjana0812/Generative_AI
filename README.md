Generative AI RAG PDF Assistant

This project implements a Retrieval-Augmented Generation (RAG) system for searching and retrieving relevant information from uploaded PDF documents.

Features
Upload and process PDF documents
Extract text from PDF files
Split documents into smaller text chunks
Generate multilingual text embeddings using Sentence Transformers
Store and search embeddings using FAISS
Retrieve the most relevant document sections for a user query
Designed to support documents containing Indian languages
Technologies Used
Python
Google Colab
PyPDF
Sentence Transformers
FAISS
NumPy
Gradio
Workflow

PDF Upload → Text Extraction → Text Chunking → Embeddings → FAISS Vector Search → Relevant Information Retrieval

This project demonstrates the basic implementation of a Retrieval-Augmented Generation pipeline for document-based question answering and semantic search.

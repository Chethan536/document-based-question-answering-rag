# Document-Based Question Answering using RAG

This project demonstrates a basic implementation of a Retrieval Augmented
Generation (RAG) system for answering questions from documents.

The system retrieves relevant information from documents using semantic search
and prepares the context for Large Language Model (LLM) based answer generation.

## Project Overview
- Load PDF documents
- Split documents into smaller text chunks
- Generate embeddings using Hugging Face models
- Store embeddings in a FAISS vector database
- Retrieve relevant document chunks for a user query

## Tech Stack
- Python
- LangChain
- FAISS
- Hugging Face Embeddings
- Jupyter Notebook

## Why RAG?
Traditional LLMs may hallucinate responses. RAG improves reliability by grounding
the LLM response in retrieved document context, leading to more accurate answers.

## Note
This project focuses on the **retrieval component** of RAG. The retrieved context
can be passed to any LLM (such as Gemini or OpenAI) for answer generation.

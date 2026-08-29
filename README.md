# EU Machinery Compliance System

AI-powered compliance evidence and traceability system for the EU Machinery Regulation.

## Overview

This project is an end-to-end Retrieval-Augmented Generation (RAG) system designed to retrieve relevant regulatory evidence from EU Machinery Regulation documents and generate traceable answers.

The system combines semantic retrieval, CrossEncoder reranking, and LLM-based answer generation to improve the relevance and traceability of compliance information.

## Key Features

- PDF document ingestion and text processing
- Text cleaning and chunking
- Semantic embeddings
- Qdrant vector database for retrieval
- CrossEncoder reranking
- Evidence-based retrieval
- LLM answer generation
- Traceable source references
- FastAPI REST API
- Automated tests
- Ruff linting
- Docker support

## Architecture

```text
EU Machinery Regulation PDF
            ↓
     Text Extraction
            ↓
    Cleaning & Chunking
            ↓
       Embeddings
            ↓
     Qdrant Vector DB
            ↓
   Semantic Retrieval
            ↓
 CrossEncoder Reranking
            ↓
   Relevant Evidence
            ↓
    LLM Answer Generation
            ↓
  Answer + Traceable Sources

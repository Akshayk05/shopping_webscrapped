# RAG-based E-commerce Product Search

## Overview

This project simulates a **Retrieval-Augmented Generation (RAG)** style system for product search in an E-commerce setting.  
It uses:

- Simulated product data with 50+ features  
- Sentence Transformers for text embeddings  
- FAISS for fast similarity search over product vectors  
- Simple query-to-result retrieval pipeline  

---

## Features

- Generates dummy E-commerce product data (50 products, 50+ features each)  
- Embeds product descriptions into dense vector space using `sentence-transformers`  
- Builds a FAISS vector index for quick nearest neighbor search  
- Accepts user queries, converts them into embeddings, and retrieves top matching products  
- Easily extendable to real scraped data and production vector DBs  

---

## Requirements

- Python 3.7+  
python rag_ecommerce.py
You will be prompted to enter a product query, for example:

Enter your product query: wireless earphones under 1000
The system will output top matching products based on vector similarity.

Project Structure
rag_ecommerce.py: Main script with data simulation, embedding, indexing, and query search

(Optional) Additional scripts to extend scraping, UI, or vector DB integration

- Future Improvements
Integrate real scraped E-commerce data

Use larger, domain-specific embedding models

Add Flask/Django web UI for interactive search

Integrate OpenAI or custom LLM for natural language generation responses

Store and manage vector DB on cloud for scalability

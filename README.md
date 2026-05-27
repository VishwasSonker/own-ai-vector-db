# Own AI — Vector Database + RAG Engine

An AI-powered semantic search engine and custom Vector Database built in C++ featuring HNSW indexing, KD-Tree search, Retrieval-Augmented Generation (RAG), interactive embedding visualization, and local LLM integration using Ollama.

---

## 🚀 Features

- Custom Vector Database implementation in C++
- HNSW (Hierarchical Navigable Small World) indexing
- KD-Tree nearest neighbor search
- Brute Force similarity search benchmarking
- Semantic Search using vector embeddings
- Retrieval-Augmented Generation (RAG)
- Local LLM integration with Ollama
- Interactive embedding visualization using PCA
- Real-time search latency benchmarking
- Document chunking and embedding pipeline
- REST API backend using `cpp-httplib`
- Interactive frontend dashboard

---

## 🧠 Technologies Used

### Backend
- C++
- cpp-httplib
- REST APIs
- HNSW Graph Search
- KD-Tree
- Vector Similarity Search

### Frontend
- HTML
- CSS
- JavaScript
- Canvas API

### AI / ML
- Ollama
- nomic-embed-text
- llama3.2
- Retrieval-Augmented Generation (RAG)
- Embeddings

---

## 📸 Screenshots

## Project Interface

## 📸 Project Interface

![Project Interface](assets/project%20interface.png)

---

## Search Visualization

![Search UI](/assets/search.png)

---

## RAG Chat Interface

![RAG Chat](/assets/rag.png)

---

## Benchmark Dashboard

![Benchmark](/assets/benchmark.png)

---

## 🏗️ Documents

![Documents](/assets/documents.png)

### Project Flow

```text
Frontend (HTML/CSS/JS)
        ↓
C++ REST API Server
        ↓
Vector Database Engine
        ↓
Embedding + RAG Pipeline
        ↓
Ollama Local LLM
```

---

## ⚡ Search Algorithms Implemented

### 1. HNSW
Approximate nearest neighbor search using a hierarchical graph structure for ultra-fast semantic retrieval.

### 2. KD-Tree
Space-partitioning data structure used for efficient nearest neighbor queries.

### 3. Brute Force
Baseline similarity search implementation for benchmarking and comparison.

---

## 🤖 RAG Pipeline

The project supports Retrieval-Augmented Generation (RAG):

1. User inserts documents
2. Documents are chunked
3. Embeddings are generated using Ollama
4. Embeddings are stored in the vector database
5. Relevant chunks are retrieved during queries
6. Context is sent to the LLM for answer generation

---

## 📂 Project Structure

```text
own-ai-vector-db/
│
├── backend/
│   ├── main.cpp
│   ├── httplib.h
│
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── app.js
│
├── assets/
│   ├── screenshots/
│   ├── demo.mp4
│   └── architecture.png
│
├── docs/
│
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🛠️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/own-ai-vector-db.git
cd own-ai-vector-db
```

---

### 2. Install Ollama

Download and install Ollama:

https://ollama.com/

---

### 3. Pull Required Models

```bash
ollama pull nomic-embed-text
ollama pull llama3.2
```

---

### 4. Compile Backend

```bash
g++ main.cpp -o vectordb -std=c++17
```

---

### 5. Run Backend Server

```bash
./vectordb
```

Server starts at:

```text
http://localhost:8080
```

---

### 6. Run Frontend

Open:

```text
frontend/index.html
```

in your browser.

---

## 📊 Features Demonstrated

- Semantic vector search
- Approximate nearest neighbor retrieval
- Vector similarity metrics
- Real-time benchmarking
- Interactive vector visualization
- RAG-based AI responses
- Document embedding pipeline
- REST API communication

---

## 📈 Future Improvements

- PostgreSQL + pgvector integration
- Cloud deployment
- User authentication
- PDF/DOCX upload support
- Hybrid search (BM25 + vector search)
- Docker support
- Distributed vector indexing
- Multi-user document spaces

---

## 🎯 Learning Outcomes

This project was built to explore:

- Vector databases
- Semantic search systems
- Approximate nearest neighbor algorithms
- Retrieval-Augmented Generation (RAG)
- Embedding pipelines
- Systems programming in C++
- Full-stack AI application development

---

## ⭐ If You Like This Project

Give this repository a star and feel free to contribute or suggest improvements.

# Homework 2 – Vector Search

This repository contains my solution for **Homework 2 – Vector Search** from **LLM Zoomcamp 2026 (Module 2)** by **DataTalksClub**.

The objective of this homework is to implement a semantic search pipeline using text embeddings, compare it with traditional keyword search, and improve retrieval quality through Hybrid Search.

---

# Learning Objectives

During this homework I implemented the following concepts:

- Generate text embeddings using a lightweight ONNX model
- Compute cosine similarity between vectors
- Build vector search manually with NumPy
- Index embeddings using **minsearch**
- Compare keyword search and semantic search
- Combine both approaches using **Hybrid Search** with Reciprocal Rank Fusion (RRF)

---

# Project Structure

```text
llm-zoomcamp-hw2/
│
├── embed/
│   ├── download.py
│   └── embedder.py
│
├── models/
│
├── homework_02.ipynb
├── main.py
├── pyproject.toml
├── uv.lock
└── README.md
```

---

# Technologies Used

- Python
- NumPy
- ONNX Runtime
- minsearch
- Jupyter Notebook
- uv

---

# Running the Project

## Clone the repository

```bash
git clone <repository-url>
```

## Create the environment

```bash
uv sync
```

## Download the embedding model

```bash
uv run python embed/download.py
```

## Launch Jupyter Notebook

```bash
uv run jupyter notebook
```

Open:

```
homework_02.ipynb
```

and execute the notebook cells sequentially.

---

# Homework Tasks

The notebook covers:

- Query embedding
- Cosine similarity
- Document chunking
- Manual vector search
- Vector indexing
- Keyword search
- Hybrid Search (RRF)

---

# Learning in Public

This homework is part of my **LLM Zoomcamp 2026 – Learning in Public** journey.

## Social Posts

🐦 X

*Add the link to your X post here.*

💼 LinkedIn

*Add the link to your LinkedIn post here.*

---

# References

- **LLM Zoomcamp 2026**
  https://github.com/DataTalksClub/llm-zoomcamp

- **DataTalksClub**
  https://github.com/DataTalksClub

- **Alexey Grigorev**
  https://github.com/alexeygrigorev

---

# License

This repository is intended for educational purposes as part of the **LLM Zoomcamp 2026** learning journey.
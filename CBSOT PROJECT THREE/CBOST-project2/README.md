# Semantic Research Paper Search Engine

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![FAISS](https://img.shields.io/badge/FAISS-Vector_Search-green)
![Transformers](https://img.shields.io/badge/SentenceTransformers-NLP-orange)

## Project Overview
This project implements a semantic search engine for Machine Learning research papers. Unlike traditional keyword search, it retrieves papers based on semantic similarity using transformer-generated embeddings and a FAISS vector index.

## Problem Statement
Finding relevant research papers using keyword search often misses semantically related work. This project addresses that limitation by representing papers and user queries as dense embeddings.

## Features
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Semantic embeddings using all-MiniLM-L6-v2
- FAISS vector indexing
- Natural language search
- Top-k relevant paper retrieval

## Tech Stack
Python, Pandas, NumPy, Hugging Face Datasets, Sentence Transformers, FAISS, Jupyter Notebook

## Repository Structure
```
notebooks/
    EDA.ipynb
    Search_Engine.ipynb
images/
README.md
requirements.txt
dataset.md
LICENSE
CONTRIBUTING.md
```

## Installation
```bash
pip install -r requirements.txt
```

## How to Run
1. Execute EDA.ipynb
2. Execute Search_Engine.ipynb
3. Run search_paper("your query")

## Future Improvements
- Streamlit Web App
- Filters by author/year
- PDF upload
- Research paper summarization

## Author
Rituraj

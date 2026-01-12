# Distributed Text Search Engine (PySpark)

A distributed text search system that ranks documents by relevance using the **Vector Space Model** with **TF-IDF weighting** and **cosine similarity**. Performs text preprocessing, builds an **inverted index**, and returns top-K results for a query using PySpark RDDs.

## Tech Stack
- Python
- PySpark (RDD-based processing)

## Key Features
- Text preprocessing: tokenization, stop-word removal, stemming
- Inverted index construction
- TF-IDF weighting + Vector Space Model ranking
- Cosine similarity scoring and top-K retrieval

## Project Layout
- `distributed-text-search.ipynb` – Jupyter notebook
- `data/` – documents + stopword list

## How to Run

### Google Colab
1. Upload the notebook
2. Extract the documents in `data/`
3. Upload the `data/` files (or mount Google Drive)
4. Run all cells one by one

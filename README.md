# intelligent-search

A collection of semantic and traditional search techniques implemented in Python, including BERT-based semantic search and TF-IDF-based search.

## Project Structure

- **BERT-Semantic Search/**  
  Implementations and notebooks for semantic search using BERT embeddings.

- **TF-IDF Search/**  
  Classic information retrieval using TF-IDF and inverted index techniques.
  - `corpus_vocab.json` — Vocabulary of the corpus.
  - `data.json` — Raw data used for search.
  - `example_queries.json` — Sample queries for testing.
  - `example_queries_results.json` — Results for the sample queries.
  - `inverted-index-search.ipynb` — Notebook for inverted index search.
  - `spaCy-preprocess-text.ipynb` — Text preprocessing using spaCy.
  - `tf-idf-search.ipynb` — Notebook for TF-IDF search.
  - `updated_data.json` — Updated data after preprocessing.
  - `updated_data_vectorized.json` — Vectorized data for efficient search.

## Getting Started

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/intelligent-search.git
    cd intelligent-search
    ```

2. Install dependencies (recommended: use a virtual environment):
    ```sh
    pip install -r requirements.txt
    ```

3. Explore the notebooks in each folder to understand and run the search algorithms.

## Notebooks

- **BERT-Semantic Search:**  
  Demonstrates semantic search using BERT embeddings.

- **TF-IDF Search:**  
  Shows how to build an inverted index and perform TF-IDF-based search.

## Requirements

- Python 3.7+
- Jupyter Notebook
- spaCy
- scikit-learn
- transformers (for BERT)
- numpy, pandas

## License

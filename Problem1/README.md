# NLU Assignment 2 - Word2Vec

This repository contains Natural Language Understanding assignment focused on Word2Vec implementations using PyTorch.

## Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/shyamaljoshi1/NLU-Assignment-2.git
cd NLU-Assigement-2
```

### 2. Run Data Collection Notebook
Open and execute **`NLU_Assignment2_DataCollection.ipynb`** to:
- Scrape data from 5 IITJ sources
- Preprocess and clean the corpus
- Generate tokenized text for training

### 3. Run Word2Vec Notebook
Open and execute **`NLU_Assignment2_Word2Vec.ipynb`** to:
- Train custom CBOW and Skip-gram models
- Analyze word embeddings and semantic relationships
- Visualize embedding spaces and generate analogies

## Requirements
- Python 3.7+
- PyTorch
- NumPy, Pandas, Matplotlib, Scikit-learn
- NLTK, Requests, BeautifulSoup4

All dependencies are installed automatically when running the notebooks.

## Output Files
- `data/iitj_corpus_clean.csv` - Preprocessed corpus
- `data/iitj_tokens.json` - Tokenized text
- `data/models/` - Trained model weights
- Visualizations (PNG files) - PCA, t-SNE, word clouds, etc.

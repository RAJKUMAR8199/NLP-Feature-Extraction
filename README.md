# Amazon Reviews NLP Feature Extraction

## Overview
This project demonstrates Natural Language Processing (NLP) feature extraction techniques on the Amazon Fine Food Reviews dataset.

The notebook converts cleaned review text into numerical representations suitable for machine learning and sentiment classification tasks.

---

## Objectives
- Text preprocessing validation
- Bag-of-Words (BoW)
- N-gram feature extraction
- TF-IDF vectorization
- Sparse matrix analysis
- Text visualization using WordCloud and heatmaps

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- WordCloud
- Jupyter Notebook

---

## NLP Techniques Implemented

### 1. Bag-of-Words (BoW)
- Converts text into word-frequency vectors
- Uses `CountVectorizer`

### 2. N-grams
- Extracts unigram and bigram patterns
- Captures contextual relationships between words

### 3. TF-IDF
- Assigns importance weights to words
- Reduces influence of overly common terms

### 4. TF-IDF with Bigrams
- Captures phrase-level importance
- Improves contextual understanding

---

## Visualizations
- TF-IDF WordCloud
- Bigram Importance Bar Chart
- Sparsity Heatmap

---

## Key Insights
- Important customer sentiment phrases identified
- Sparse matrix behavior observed in NLP features
- Bigram TF-IDF captures richer contextual meaning

---

## Project Structure
```text
Amazon-Reviews-NLP/
│
├── 2_CP_Feature_Extraction.ipynb
├── README.md
├── LICENSE
└── .gitignore
```

---

## Future Improvements
- Sentiment classification models
- Deep learning embeddings
- Word2Vec / GloVe integration
- Transformer-based NLP models

---

## Author
Raj Kumar

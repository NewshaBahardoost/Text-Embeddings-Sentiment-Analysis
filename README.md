# 📝 Text Embeddings for Sentiment Analysis

## Overview
This project demonstrates how to use **word embeddings** to analyze customer sentiment in text data. Using a set of sentences extracted from product reviews, I built a simple **Word2Vec-like model** to capture the semantic relationships between words. This approach helps businesses understand customer opinions and improve **feedback-driven decisions**.

---

## Business Goal
- Transform customer feedback into numerical representations (embeddings).
- Discover relationships between words (e.g., *good ↔ awesome*).
- Enable **sentiment clustering, topic analysis, and recommendation insights**.

---

## Approach
1. Preprocessed text: removed punctuation and tokenized words.
2. Built a **skip-gram neural network** (PyTorch) with a window size of 2.
3. Learned **2D word embeddings** for ~3,000 unique words.
4. Computed the top 5 semantically similar words for given terms.

---

## Example Results

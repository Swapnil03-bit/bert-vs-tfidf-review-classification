# BERT vs TF-IDF Review Rating Classification

## Overview
This project compares traditional TF-IDF features with contextual BERT embeddings
for predicting product review ratings (1–5 stars).

## Techniques Used
- TF-IDF Vectorization
- BERT (bert-base-uncased) embeddings
- Logistic Regression
- Macro-F1 and Weighted-F1 evaluation

## Tools
- Python
- Scikit-learn
- PyTorch
- HuggingFace Transformers
- Google Colab

## Key Findings
- TF-IDF performs well on majority classes
- BERT generalizes better across minority classes

## How to Run
```bash
pip install -r requirements.txt

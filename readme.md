This project emphasizes experimentation and interpretability rather than black-box optimization.

## Overview:
A step-by-step NLP-based fake news detection system using Naive Bayes and advanced text representation techniques.

## Problem Statement
Identify whether a news article is real or fake using NLP techniques.

## Used pipeline:

1. Text cleaning (lowercase, punctuation removal, whitespace normalization)
2. Baseline: CountVectorizer + Naive Bayes
3. NLP pipeline: clean text → CountVectorizer
4. TF-IDF → Naive Bayes
5. TF-IDF + Bigram → Naive Bayes


The project further explores advanced models and optimization techniques to improve performance and reliability.
Advanced models like Logistic Regression, SVM, and ANN were explored for performance comparison.

Although tree-based ensemble models like Random Forest and XGBoost are powerful for tabular data, linear models such as Logistic Regression and Linear SVM are more suitable for high-dimensional sparse text representations like TF-IDF
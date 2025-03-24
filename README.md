# Unigrams-and-Sentiment-Classification-on-Kazakh-dataset
# README

**Contributers:** Amina Alisheva and Ariana Kenbayeva  
**Date:** 24.02.2025  

### Overview
This project involves building and analyzing unigram, bigram, and trigram language models, evaluating their perplexity, and applying different smoothing techniques. Additionally, we perform sentiment analysis using various classification models and compare their accuracy.

### Code Structure
All code is implemented in a **Google Colab notebook**, structured into the following sections:
- **Preprocessing:** Tokenizes the dataset and prepares it for model training.
- **N-gram Model Implementation:** Constructs unigram, bigram, and trigram models.
- **Perplexity Calculation:** Computes perplexity scores for different n-gram models.
- **Smoothing Techniques:** Implements Laplace, Interpolation, Backoff, and Kneser-Ney smoothing.
- **Sentiment Analysis:** Compares Logistic Regression, Naive Bayes, and Binary Naive Bayes for sentiment classification.
- **Regularization Analysis:** Evaluates the effects of L1 and L2 regularization in Logistic Regression.
- **Results & Discussion:** Summarizes findings and model performance.

### Requirements
Ensure you have the required libraries installed in your Colab environment:
```python
!pip install numpy pandas nltk scikit-learn
```

### Running the Code
1. Open the Google Colab notebook.
2. Run each section in sequential order to preprocess data, train models, and analyze results.
3. The final results, including perplexity scores and classification accuracy, will be displayed in the output cells.

### Results Summary
- **Trigram model achieved the best perplexity score (1.46).**
- **Backoff smoothing provided the most effective results.**
- **Naive Bayes classifier outperformed others in sentiment analysis (accuracy: 0.93).**
- **L2 regularization significantly improved Logistic Regression accuracy (0.95).**

### Contribution
- **Amina Alisheva**: Sentiment analysis and regularization experiments.
- **Jafar Isbarov & Ariana Kenbayeva**: N-gram model implementation, smoothing techniques, and perplexity evaluation.

### Contact
For any questions, please reach out to the team members.

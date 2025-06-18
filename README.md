# 📦 Sentiment Analysis on Amazon Reviews  
**Comparative Study of Classical ML and Transformer-Based Models**

> 📘 This repository contains the project report for the **Natural Language Processing** course, part of the **Master’s degree in Computer Science** at **Sapienza University of Rome**, held by **Prof. Stefano Faralli** and **Prof. Iacopo Masi**.


## 📝 Project Overview

This project explores **sentiment analysis** on Amazon product reviews using a two-phase evaluation pipeline that compares classical machine learning algorithms with transformer-based models.

### Phase 1: Baseline Evaluation with TF-IDF  

- **Models Evaluated**:
  - Logistic Regression  
  - Multinomial Naive Bayes  
  - DistilBERT (fine-tuned transformer model)  

- **Features Used**: TF-IDF vectors  
- **Classification Labels**: Positive, Negative, Neutral  
- **Evaluation Metrics**:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-Score  
  - Confusion Matrix  

### Phase 2: Embedding Strategy Comparison  

- **Goal**: Assess whether alternative embeddings improve performance  
- **Additional Embeddings**:
  - Word2Vec (CBOW & Skip-gram)  
  - Hybrid: Word2Vec + DistilBERT  

- **Focus Model**: Logistic Regression  

- **Observation**:
  - DistilBERT achieves highest accuracy overall  
  - Hybrid approaches offer moderate improvements but at the cost of higher complexity

## 📊 Key Takeaways

- TF-IDF with logistic regression is a strong baseline for sentiment classification  
- DistilBERT significantly outperforms classical models in all metrics  
- Hybrid embeddings can enhance classical model performance, but introduce additional computational overhead

## 🛠️ Technologies Used

- scikit-learn  
- NLTK  
- Gensim  
- Hugging Face Transformers  
- Pandas / NumPy / Matplotlib / Seaborn

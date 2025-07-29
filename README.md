# Twitter Text Classification

This repository focuses on **binary text classification** using Twitter datasets, comparing traditional machine learning, neural networks, and transformer-based models.  
We train and evaluate the following models:

- **Logistic Regression** with **TF-IDF vectorization**  
- **Feedforward Deep Neural Network (DNN)** with **Word2Vec embeddings** (Skip-gram & CBOW)  
- **BERT** (transformer-based fine-tuning)  
- **DistilBERT** (lightweight transformer fine-tuning)

The project highlights how different representation methods (TF-IDF vs. Word2Vec vs. contextual embeddings) affect model performance.

## Features
- Preprocessing of raw Twitter data (EDA, cleaning, tokenization).
- Vectorization via **TF-IDF** and **Word2Vec (Skip-gram + CBOW)**.
- Fine-tuning pipelines for transformer-based models.
- Performance evaluation and visualization (accuracy, precision, recall, and F1-score).

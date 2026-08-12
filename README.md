# 📈 Stock Market Sentiment Analysis

## 📖 Project Description
Stock market prices are influenced by financial news, company performance, and market sentiment. Investors often find it difficult to analyze a large amount of news manually. This project uses Artificial Intelligence (AI), Natural Language Processing (NLP), and Machine Learning (ML) to automatically classify stock market news as **Positive**, **Negative**, or **Neutral**. The system helps investors and analysts understand market sentiment and supports better investment decisions.

---

## 🎯 Goal
To develop an AI-based sentiment analysis system that classifies stock market news into positive, negative, or neutral sentiments using NLP and Machine Learning techniques.

---

## 🚀 Objectives
- Preprocess stock market news data.
- Generate text embeddings using Word2Vec and Sentence Transformer.
- Build and compare Random Forest and Neural Network models.
- Evaluate model performance using classification metrics.
- Predict sentiment for new stock market news headlines.

---

## 📂 Dataset
The dataset contains:
- News headlines related to the stock market
- Sentiment labels (Positive, Neutral, Negative)

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Gensim
- Sentence Transformers
- TensorFlow / Keras

### Machine Learning Models
- Random Forest
- Neural Network

### Embedding Techniques
- Word2Vec
- Sentence Transformer (BAAI/bge-base-en-v1.5)

---

## ⚙️ Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Text Embedding
   - Word2Vec
   - Sentence Transformer
5. Model Building
   - Random Forest
   - Neural Network
6. Model Evaluation
7. Prediction on New News Headlines

---

## 📊 Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🏆 Final Model

| Component | Selected Model |
|-----------|----------------|
| Embedding Technique | Sentence Transformer (BAAI/bge-base-en-v1.5) |
| Classification Model | Random Forest |

The final model achieved the best performance and was selected for stock sentiment prediction.

---

## ✨ Features
- Stock news sentiment classification
- Comparison of Word2Vec and Sentence Transformer embeddings
- Comparison of Random Forest and Neural Network models
- Prediction of unseen news headlines
- Performance evaluation using multiple metrics

## 📌 Results
- Sentence Transformer produced better text embeddings than Word2Vec.
- Random Forest outperformed the Neural Network in test accuracy.
- The final model successfully classified stock news into Positive, Neutral, and Negative sentiments.

---

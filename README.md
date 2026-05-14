# Sentiment Analysis using NLP

This project performs Sentiment Analysis on movie reviews using different NLP and Machine Learning approaches.  
The goal is to classify reviews as **Positive** or **Negative** based on textual content.

The project compares multiple techniques for sentiment classification:
1. TF-IDF with Machine Learning Models
2. FastText
3. Deep Learning Models

---

# 📌 Project Overview

Sentiment Analysis is a Natural Language Processing (NLP) task used to identify emotions or opinions from text data.

In this project:
- Text data is cleaned and preprocessed
- Reviews are converted into numerical representations
- Multiple models are trained and evaluated
- Different approaches are compared for performance

Dataset used:
- [IMDB Movie Review Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

---

# 🚀 Approaches Used

## 1️⃣ FastText

FastText is a text classification library developed by Facebook.

In this approach:
- Data is converted into FastText format
- The model learns word and subword representations
- Text classification is performed efficiently

### Advantages
- Very fast training
- Handles unknown words better
- Good performance on text classification tasks

---

## 2️⃣ TF-IDF + Machine Learning Models

In this approach:
- Reviews are converted into numerical vectors using **TF-IDF Vectorization**
- Traditional ML models are trained on these vectors

### Models Used
- Logistic Regression
- Naive Bayes
- Random Forest


### Advantages
- Fast training
- Easy to implement
- Good baseline performance

---

## 3️⃣ Deep Learning Models

Deep Learning models are used to capture complex patterns in textual data.

### Techniques Used
- Tokenization
- Padding
- Embedding Layer
- Neural Networks using TensorFlow/Keras

### Advantages
- Better understanding of context
- Improved accuracy on large datasets
- Learns semantic relationships between words

---

# 📂 Project Structure

├── sentimentAnalysis.ipynb  
├── IMDB Dataset.csv  
├── sentiment.train  
├── sentiment.test  
├── requirements.txt  
├── README.md  

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- SpaCy
- FastText
- Matplotlib
- Seaborn
- Jupyter Notebook

---


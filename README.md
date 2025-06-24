Here, I've used the process like
- Replacing Emoticons and Emojis
- Converting to lower case
- Removing URL's and HTML tags
- Removing Punctuations
- Chatwords Treatment
- Spelling Correction
- Removing Stopwords
- Tokenization

# 🐦 Twitter Sentiment Analysis using LSTM

A deep learning-based sentiment analysis pipeline that classifies public tweets as **positive**, **negative**, or **neutral**. This project leverages the power of **NLP** and **LSTM networks** to analyze sentiments from raw textual data.

---


## ✨ Project Features

- Real-world tweet dataset handling  
- Advanced text preprocessing: tokenization, lemmatization, noise removal  
- LSTM-based deep learning model   
- Class imbalance handling  
- Evaluation using accuracy, precision
- Data visualization for insights and interpretation  

---

## 🛠 Tech Stack

**Language:** Python 3.x  

**Libraries:**
- `Pandas`, `NumPy` – Data handling  
- `NLTK`, `re` – Text preprocessing  
- `Scikit-learn` – Vectorization & metrics  
- `Keras` (TensorFlow backend) – Deep Learning  
- `Matplotlib`, `Seaborn` – Visualization  

**Model:** LSTM (Long Short-Term Memory Network)

---

## 🔁 Workflow

### 1. Data Collection
- Pre-collected dataset of 162,980 tweets

### 2. Preprocessing
- Clean tweets (remove URLs, mentions, hashtags, emojis, stopwords)
- Tokenize and lemmatize
- Label encoding and class balancing

### 3. Text Vectorization
- Tokenizer + Padding

### 4. Model Training
- LSTM model built 
- Dropout and regularization to prevent overfitting

### 5. Evaluation
- Classification report and confusion matrix
- Accuracy and AUC analysis


---

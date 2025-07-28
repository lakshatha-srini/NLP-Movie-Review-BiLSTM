# NLP-Movie-Review-BiLSTM
This project performs sentiment analysis on IMDB movie reviews using a Bidirectional LSTM (BiLSTM) model with Word2Vec embeddings.  
It loads and cleans labeled and unlabeled review datasets, trains custom embeddings, and applies semi-supervised learning for improved accuracy.

---

## 📂 Dataset
The dataset follows the below structure:
Sentiment_Analysis/
│── train/
│ ├── pos/ (Positive reviews)
│ ├── neg/ (Negative reviews)
│ ├── unsup/ (Unsupervised reviews)
│
│── test/
│ ├── pos/(Positive reviews)
│ ├── neg/(Negative reviews)


- **Labeled data:** 25k positive and negative reviews for training/testing  
- **Unlabeled data:** Used to train Word2Vec embeddings and improve predictions  
- Source: IMDB review dataset (publicly available)

---

## ⚙️ Technologies Used
- **Python**  
- **NumPy, Pandas** (Data handling)  
- **Gensim** (Word2Vec embeddings)  
- **NLTK** (Text preprocessing, stopwords)  
- **TensorFlow / Keras** (BiLSTM model)  
- **Scikit-learn** (Metrics and evaluation)  
- **Pandarallel** (Faster text processing)

---

## How to Run
1. Clone the repository:

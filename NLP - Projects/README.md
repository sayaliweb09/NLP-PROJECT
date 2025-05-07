# 📝 NLP Projects: Sentiment Analysis & News Classification

This repository contains two NLP projects:

1. **IMDb Movie Review Sentiment Analysis** – A machine learning model to classify IMDb movie reviews as positive or negative.
2. **News Article Classification** – A classifier to categorize news articles into predefined topics (sports, politics, technology, etc.).

---

## 📂 Project Structure

```


NLP-Projects/
├── IMDb-Sentiment-Analysis/
│   ├── IMDb Movie Review Sentiment Analysis.ipynb  # Jupyter Notebook
│   ├── data_imdb.csv  # IMDb dataset 
│   ├── IMDb Movie Review Sentiment Analysis.pdf  # Report 
│
├── News-Article-Classification/
│   ├── News Article Classification.ipynb  # Jupyter Notebook
│   ├── data_news.csv  # News dataset 
│   ├── News Article Classification.pdf  # Report
│
├── README.md  # Project documentation
```

---

## 📌 Project 1: IMDb Movie Review Sentiment Analysis

### 🔹 Overview
This project classifies IMDb movie reviews as **positive** or **negative** using machine learning models.

### 🔹 Dataset
- **Source**: IMDb movie reviews dataset.
- **Size**: 50,000 reviews (balanced between positive and negative).
- **Format**: CSV with two columns: `review` (text) and `sentiment` (label).

### 🔹 NLP Techniques Used
- Text preprocessing (stopword removal, lemmatization, punctuation removal)
- Feature extraction using **TF-IDF** and **Word2Vec**
- Machine learning models: **Naive Bayes, Logistic Regression, SVM, Random Forest**
- **SVM performed the best** with an accuracy of **88.6%**.

### 📊 **Results**
- **Best Model:** SVM
- **Accuracy:** 88.6%
- **F1-score:** 88.8%
- **ROC-AUC:** 88.6%

---

## 📌 Project 2: News Article Classification

### 🔹 Overview
This project categorizes news articles into predefined categories (sports, politics, technology, etc.).

### 🔹 Dataset
- **Source**: Labeled dataset of 50,000 news articles.
- **Columns**: `category`, `headline`, `short_description`, `keywords`.

### 🔹 NLP Techniques Used
- Text preprocessing (lowercasing, punctuation removal, stopword removal)
- **TF-IDF** for feature extraction
- Classification models: **Logistic Regression, Naive Bayes, SVM**
- **SVM performed best** with an accuracy of **81.7%**.

### 📊 **Results**
- **Best Model:** SVM
- **Accuracy:** 81.7%
- **F1-score:** 81.7%

---

## 🔧 Installation & Usage

1. **Clone the repository** (if using Git):
   ```bash
   git clone https://github.com/HimanshuJagga/NLP-Projects.git
   Run Jupyter Notebook: jupyter notebook
   ```
Open the .ipynb files and execute the cells to train and test the models.

🎯 Future Improvements
Implement deep learning models (LSTM, BERT).
Expand datasets with more categories.
Optimize feature engineering techniques.

⭐ Contributing & Feedback
Feel free to fork this repository, create issues, or suggest improvements!

📧 Contact: www.linkedin.com/in/sayaligajbhiye
# 📩 SMS Spam Detection using Machine Learning

An end-to-end Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using **Natural Language Processing (NLP)** and supervised learning algorithms. The project covers the complete ML lifecycle, including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and deployment through an interactive Streamlit web application.

---

## 🚀 Overview

Spam messages are a common challenge in modern communication systems. This project implements an intelligent spam detection pipeline capable of automatically classifying SMS messages using classical Machine Learning techniques and NLP.

The workflow includes:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Text feature extraction using TF-IDF
* Training and evaluation of multiple classifiers
* Interactive prediction through a Streamlit web application

---

## ✨ Features

* 📌 End-to-end NLP pipeline
* 🔤 Text preprocessing

  * Lowercasing
  * Tokenization
  * Stopword Removal
  * Punctuation Removal
  * Stemming using Porter Stemmer
* 📊 Exploratory Data Analysis (EDA)
* ☁️ Word Cloud visualization
* 📝 TF-IDF Vectorization
* 🤖 Multiple Machine Learning models for comparison
* 📈 Performance evaluation using standard classification metrics
* 💻 Interactive Streamlit web application
* 💾 Serialized model and vectorizer for real-time inference

---

## 🛠️ Tech Stack

| Category            | Technologies                   |
| ------------------- | ------------------------------ |
| Language            | Python                         |
| Data Analysis       | Pandas, NumPy                  |
| Visualization       | Matplotlib, Seaborn, WordCloud |
| NLP                 | NLTK                           |
| Machine Learning    | Scikit-learn                   |
| Deployment          | Streamlit                      |
| Model Serialization | Pickle                         |

---

## 📂 Project Structure

```text
SMS-Spam-Detection/
│
├── app.py                      # Streamlit web application
├── model.pkl                   # Trained ML model
├── vectorizer.pkl              # TF-IDF Vectorizer
├── spam.csv                    # Dataset
├── SMS_Spam_Detection.ipynb    # Model development notebook
├── requirements.txt
├── README.md
└── images/
    └── app.png                 # Application screenshot
```

---

## ⚙️ Machine Learning Pipeline

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Text Preprocessing
5. Feature Engineering
6. TF-IDF Vectorization
7. Model Training
8. Model Evaluation
9. Deployment using Streamlit

---

## 🤖 Models Evaluated

* Gaussian Naive Bayes
* Multinomial Naive Bayes
* Bernoulli Naive Bayes

After comparative evaluation, **Multinomial Naive Bayes** delivered the best overall performance on the SMS Spam Collection dataset when combined with TF-IDF feature extraction.

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Confusion Matrix

Since spam detection prioritizes minimizing false positives while maintaining strong predictive performance, precision was considered alongside overall accuracy.

---

## 💻 Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/SMS-Spam-Detection.git
cd SMS-Spam-Detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

or

```bash
python -m streamlit run app.py
```

---

## 📸 Application Preview

<img width="558" height="254" alt="Screenshot 2026-06-29 130247" src="https://github.com/user-attachments/assets/f109d7bf-8b87-4b04-b88d-d4f2a75d417a" />


---

## 📚 Dataset

This project uses the **SMS Spam Collection Dataset**, a benchmark dataset containing labeled SMS messages categorized as **Spam** and **Ham**.

---

## 🚀 Future Improvements

* Deep Learning-based spam detection (LSTM, GRU)
* Transformer-based models (BERT)
* Hyperparameter optimization
* Model deployment on Streamlit Community Cloud
* REST API using FastAPI
* Docker containerization
* CI/CD with GitHub Actions

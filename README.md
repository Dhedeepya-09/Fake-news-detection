📰 Fake News Detection using Machine Learning
📌 Project Overview
This project implements a Fake News Detection System using Machine Learning techniques.
The model classifies news articles as REAL or FAKE using Natural Language Processing (NLP) and supervised learning.

The system uses:

TF-IDF Vectorization

Passive Aggressive Classifier

Real-world news dataset

Python & Scikit-learn

🚀 Technologies Used
Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

📂 Dataset
The dataset used is:

Fake or Real News Dataset
Source:
https://raw.githubusercontent.com/lutzhamel/fake-news/master/data/fake_or_real_news.csv

It contains:

News article text

Label (FAKE / REAL)

~6000+ news samples

⚙️ How It Works
1️⃣ Text Preprocessing
News text is converted into numerical format using:

TF-IDF (Term Frequency - Inverse Document Frequency)

This helps the model understand important words in each article.

2️⃣ Model Training
We use:

Passive Aggressive Classifier

It is suitable for large-scale text classification problems and updates weights only when misclassification occurs.

3️⃣ Prediction
The model predicts:

REAL → Genuine News

FAKE → Fake News

📊 Model Performance
Accuracy: ~90%+ (varies slightly per run)

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

▶️ How to Run (Google Colab)
Open Google Colab

Copy and paste the provided Python code

Run all cells

Test with custom news headlines

No dataset download required (auto-loaded from URL).

🧠 Key Concepts Used
Natural Language Processing (NLP)

TF-IDF Vectorization

Supervised Machine Learning

Text Classification

Binary Classification

📌 Example Usage
Input:

NASA announces new discovery on Mars
Output:

Prediction: REAL
🔮 Future Improvements
Deploy using Streamlit Web App

Use Deep Learning (LSTM / BERT)

Add Model Saving (.pkl)

Improve preprocessing with stemming & lemmatization

👩‍💻 Author
P.Dhedeepya

📰 Fake News Detection using Machine Learning
�
A Natural Language Processing Project to Classify News as REAL or FAKE 

🚀 Project Overview
With the rapid growth of digital platforms like Facebook and Twitter, misinformation spreads faster than ever.
This project builds an Automated Fake News Detection System using:
🔹 Natural Language Processing (NLP)
🔹 TF-IDF Vectorization
🔹 Passive Aggressive Classifier
🔹 Supervised Machine Learning
The model predicts whether a news article is:
✅ REAL
❌ FAKE
❗ Problem Statement
Fake news can:
Manipulate public opinion
Influence elections
Spread panic
Damage credibility of institutions
Manual verification is inefficient.
Hence, an intelligent ML-based detection system is required.
📂 Dataset
📌 Fake or Real News Dataset
🔗 Source:
https://raw.githubusercontent.com/lutzhamel/fake-news/master/data/fake_or_real_news.csv�
📊 Dataset Details
📄 6000+ news articles
📝 Text column (news content)
🏷 Label column (REAL / FAKE)
🛠 Tech Stack
💻 Programming Language
Python
📚 Libraries Used
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
☁ Platform
Google Colab
Jupyter Notebook
⚙️ Methodology
1️⃣ Data Preprocessing
Load dataset
Handle missing values
Split into training & testing sets
2️⃣ Text Vectorization – TF-IDF
TF-IDF (Term Frequency – Inverse Document Frequency):
Converts text into numerical format
Assigns importance to meaningful words
Reduces impact of common words
3️⃣ Model Used – Passive Aggressive Classifier
🚀 Why This Model?
Fast and efficient
Suitable for large-scale text classification
Updates weights only when misclassification occurs
Performs well for binary classification
4️⃣ Model Training & Evaluation
80% Training Data
20% Testing Data
Evaluation Metrics:
Accuracy Score
Confusion Matrix
Precision
Recall
F1-Score
📊 Model Performance
Metric
Performance
Accuracy
~90%+
Precision
High
Recall
High
F1-Score
Balanced
⚠ Results may vary slightly per execution.
▶️ How to Run the Project
✅ Run on Google Colab
Open Google Colab
Paste the provided Python code
Run all cells
Test custom news text
No dataset download required (auto-fetched from URL).
📁 Project Structure
Copy code

Fake-News-Detection/
│
├── fake_news_detection.ipynb
├── README.md
└── requirements.txt
💡 Example Prediction
📝 Input:
Copy code

NASA announces discovery of water traces on Mars.
🤖 Output:
Copy code

Prediction: REAL
🧠 Key Concepts Covered
Natural Language Processing (NLP)
TF-IDF Vectorization
Supervised Machine Learning
Binary Classification
Model Evaluation
🔮 Future Improvements
🌐 Deploy using Streamlit
💾 Save trained model (.pkl)
🤖 Implement Deep Learning (LSTM / BERT)
🧹 Advanced preprocessing (Stemming, Lemmatization)
📊 Add interactive dashboard
👩‍💻 Author:
Dhedeepya

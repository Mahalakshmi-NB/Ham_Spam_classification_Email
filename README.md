📧 Ham-Spam Email Classification using NLP & Machine Learning
🚀 Project Overview

This project builds a Spam Detection System that classifies messages as Ham (legitimate) or Spam (unwanted) using Natural Language Processing (NLP) and Machine Learning.

It automatically:

Downloads the dataset
Preprocesses text data
Trains multiple models
Compares performance
Allows real-time user input for prediction
🎯 Features
📥 Automatic dataset download (UCI SMS Spam Collection)
🔍 Text processing using TF-IDF Vectorization
🤖 Model comparison:
Naive Bayes
Logistic Regression
📊 Performance evaluation (Accuracy & Classification Report)
💬 Interactive prediction system (user input)
🛠️ Technologies Used
Python 🐍
Pandas
Scikit-learn
NumPy
NLP (TF-IDF Vectorizer)
📂 Dataset
Source: UCI Machine Learning Repository
Dataset: SMS Spam Collection
Format:
ham → Legitimate message
spam → Unwanted message
⚙️ Workflow
1. Dataset Handling
Automatically downloads and extracts dataset
Loads data into a Pandas DataFrame
2. Data Preparation
Splits data into:
75% Training
25% Testing
3. Feature Extraction
Uses TF-IDF Vectorizer
Removes English stopwords
4. Model Training

Two models are trained and compared:

🔹 Naive Bayes
Fast and efficient for text classification
🔹 Logistic Regression
More robust and often gives better accuracy
5. Model Evaluation
Accuracy Score
Classification Report (Precision, Recall, F1-score)
6. Prediction System
Takes user input from console
Predicts whether message is HAM or SPAM
📊 Sample Output
--- Training Naive Bayes ---
Naive Bayes Accuracy: 0.96

--- Training Logistic Regression ---
Logistic Regression Accuracy: 0.98

--- Try it out! ---
Enter message: Congratulations! You won a free ticket
Prediction: SPAM

Enter message: Let's meet tomorrow
Prediction: HAM

🔮 Future Improvements

Add Deep Learning models (LSTM, BERT)
Deploy as a Web App (Flask/Streamlit)
Add email integration
Improve preprocessing (stemming, lemmatization)

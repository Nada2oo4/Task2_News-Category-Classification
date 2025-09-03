# Task2_News-Category-Classification
📌 Project Overview:

This project was developed as part of the Elevvo Pathways Internship – NLP Track.
The goal of this task is to build a Text Classification system that automatically predicts the category of a news article based on its content.
News classification is an important NLP application, widely used in recommendation systems, search engines, and digital journalism. This project demonstrates how to preprocess raw text, extract features, and train machine learning models for multi-class classification.
📂 Dataset:

Source: News Category Dataset
Size: ~200,000 news headlines/articles
Categories: classifying the news articales into 4 categories: "World News," "Sports News," "Business News," "Science Technology News"

🛠️ Steps Implemented:
Data Preprocessing:
Text cleaning (removing punctuation, lowercasing, stopword removal).
Tokenization and stemming/lemmatization.
Feature Extraction
Bag-of-Words and TF-IDF Vectorization for converting text into numerical features.
Model Training
Classical ML models tested, such as:
Logistic Regression
Naive Bayes
Random Forest
Support Vector Machine (SVM)
Evaluation
Accuracy, Precision, Recall, and F1-score were calculated.
Confusion matrices and classification reports were used to analyze performance.

📊 Results:
The models were compared across different metrics.
Logistic Regression Accuracy: 0.8946
SVM Accuracy: 0.8972
Neural Network Accuracy: 0.9047

so,Neural Network performed the best and showed the best accuracy.
🚀 Technologies Used:
Python 3
Jupyter Notebook
Libraries:
pandas
numpy
scikit-learn
nltk
matplotlib
seaborn

Bonus tasks that has been done:
1- Visualized the most frequent words per category using bar plots or word clouds
2- trained the model using a neural network  (simple feedforward NN with Keras)

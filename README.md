NewsBot Intelligence System

An end-to-end Natural Language Processing (NLP) project that classifies news articles into categories and analyzes sentiment to generate meaningful insights from textual data.

📌 Project Overview

The NewsBot Intelligence System is designed to process and analyze news articles using NLP techniques. It performs:

🏷️ Text Classification (Business, Entertainment, Politics, Sport, Tech)
😊 Sentiment Analysis (Positive, Neutral, Negative)
📊 Feature Engineering & Visualization
🤖 Machine Learning Model Training & Evaluation

The goal is to transform unstructured news text into structured, actionable insights.

🚀 Key Features
Text preprocessing (cleaning, tokenization, stopword removal)
TF-IDF vectorization for feature extraction
Sentiment analysis integration
Multiple ML models for classification
Model evaluation using:
Classification Report
Confusion Matrix
Feature importance analysis (Logistic Regression)

🧠 Technologies Used
Python 🐍
Scikit-learn
Pandas & NumPy
NLTK / TextBlob (for NLP & sentiment)
Matplotlib & Seaborn (visualization)

📊 Model Performance (Best Model: Logistic Regression)
Accuracy: 66%
Strong performance in:
Entertainment (F1: 0.75)
Sport (F1: 0.72)
Needs improvement in:
Politics (Recall: 0.47)
Tech (Recall: 0.50)

🔍 Key Insights
TF-IDF features effectively capture category-specific keywords.
Sentiment features (e.g., positive/neutral scores) contribute to classification.
Some overlap exists between categories like business and politics, leading to misclassifications.
Contextual understanding is limited with traditional models.

⚙️ Project Workflow
Data Loading & Exploration
Text Preprocessing
Feature Engineering (TF-IDF + Sentiment + Metadata)
Model Training (Logistic Regression & others)
Model Evaluation
Performance Analysis & Improvement

🌍 Real-World Applications
News aggregation platforms
Market sentiment analysis for finance
Social media monitoring tools
Content recommendation systems

📁 Project Structure
├── Midterm_NewsBot_Intelligence_System.ipynb
├── data/
├── models/
├── outputs/
└── README.md

👤 Author: Iffraah Rehman

⭐ Portfolio Value

This project demonstrates:

End-to-end NLP pipeline development
Feature engineering and model evaluation
Practical application of machine learning on real-world text data

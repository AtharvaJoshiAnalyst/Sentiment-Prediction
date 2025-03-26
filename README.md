# Sentiment-Prediction

Sentiment Analysis: Amazon Product Reviews

📌 Project Overview

This project performs sentiment analysis on customer reviews of an Amazon product using Natural Language Processing (NLP) techniques. The goal is to classify reviews as positive, negative, or neutral, analyze sentiment trends, and extract insights that help businesses improve their products based on customer feedback.

🛠 Key Features

✅ Sentiment Categorization – Classifies reviews as positive, negative, or neutral.
✅ Trend Analysis – Identifies changes in customer sentiment over time.
✅ Pretrained Sentiment Models – Uses TextBlob, VADER, and Hugging Face BERT for sentiment classification.
✅ Model Comparison – Evaluates performance to determine the best model for accuracy.
✅ Data Visualization – Uses word clouds, sentiment distribution charts, and trend graphs for insights.

📊 Dataset

The dataset used in this project is publicly available on Kaggle:
🔗 Amazon Product Reviews Dataset

It contains customer reviews, ratings, and review text, which are used to analyze sentiment.

Install Dependencies
Make sure you have Python 3.7+ installed. Install the required libraries using:

pip install -r requirements.txt
3️⃣ Run the Jupyter Notebook
jupyter notebook
Open the .ipynb file inside the notebooks/ directory and follow the steps inside the notebook.

📌 Models Used

Several pretrained NLP models were used to classify sentiment:

1️⃣ TextBlob – Simple rule-based sentiment analysis.
2️⃣ VADER (Valence Aware Dictionary & sEntiment Reasoner) – Optimized for short text like social media reviews.
3️⃣ Hugging Face BERT – Deep learning-based state-of-the-art sentiment classifier.

Each model's performance was evaluated, and BERT performed the best, achieving the most accurate sentiment classification.

📊 Results & Findings

📌 Most reviews (80%+) are positive, indicating overall customer satisfaction.
📌 The most frequently used words in positive reviews include "great," "works," and "fast."
📌 Negative reviews highlight minor issues, with words like "problem," "issue," and "slow."
📌 Model 4 (BERT) achieved the best accuracy, correctly classifying the highest number of positive and negative reviews.

✅ Best Performing Model: BERT
🚀 Key Strength: More accurate positive and negative sentiment detection

📌 Future Improvements

🚀 Fine-tune BERT on a custom Amazon dataset for improved accuracy.
🚀 Deploy as a web app using Flask or Streamlit for real-time sentiment analysis.
🚀 Integrate with an API to analyze live product reviews dynamically.


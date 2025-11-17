📝 Sentiment Analysis Project
CodeAlpha Internship – Task 4

This project focuses on applying Natural Language Processing (NLP) techniques to analyze and classify sentiment from Amazon product reviews. It combines text preprocessing, machine learning, and emotion detection to understand customer opinions and emotional tone.

📌 Project Overview

The goal of this project is to:

Classify text as positive, negative, or neutral

Detect emotions such as joy, anger, trust, fear, and more

Analyze sentiment patterns from large datasets

Extract insights that support product improvement and marketing strategy

The dataset contains 400K+ Amazon reviews in FastText format, which are cleaned, processed, and analyzed end-to-end.

🧹 1. Text Preprocessing

To prepare the data for modeling, the following preprocessing steps were performed:

Lowercasing

Removing punctuation

Removing stopwords

Lemmatization

Removing rare and frequent words

Spell correction

Structuring clean text for sentiment analysis

These steps help improve accuracy and reduce noise.

🎭 2. Emotion Detection (NRC Lexicon)

The NRC Emotion Lexicon was used to detect 8 core emotions:

Anger

Anticipation

Disgust

Fear

Joy

Sadness

Surprise

Trust

Each word in the cleaned review text is mapped to the emotion lexicon to calculate emotional frequency.

🧠 3. Sentiment Classification

Two approaches were used:

🔹 Machine Learning Model

TF-IDF Vectorization for feature extraction

Logistic Regression classifier

Achieved ~84% accuracy on test data

Works well for domain-specific sentiment prediction

🔹 Rule-Based Sentiment Analyzer

VADER (Valence Aware Dictionary and sEntiment Reasoner)

Works without training data

Good for detecting neutral sentiment

Useful for quick, real-time analysis

📊 4. Visualizations

Graphs included in the project:

Sentiment distribution (positive vs negative)

Emotion frequency across the dataset

Insights from sentiment patterns

These help convert raw data into interpretable insights.

📈 Key Insights

Positive sentiments are highly associated with joy, trust, and anticipation

Negative reviews often contain anger, sadness, and disgust

Sentiment analysis can help businesses identify product issues and customer satisfaction trends

🛠 Technologies Used

Python

Pandas, NumPy

NLTK

VADER Sentiment Analyzer

Scikit-learn

Matplotlib

NRC Emotion Lexicon

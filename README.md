# Social Media Sentiment Analysis

This project focuses on classifying sentiments (positive or negative) in social media comments, particularly tweets, using machine learning models. It utilizes natural language processing (NLP) techniques to analyze public opinions, providing valuable insights for brand monitoring, customer feedback, and trend prediction.

## 1. Project Overview

- **Domain:** Natural Language Processing (NLP)
- **Technique:** Sentiment Analysis
- **Goal:** Predict sentiment polarity (positive or negative) of tweets using machine learning
- **Dataset:** 1.6 million pre-labeled tweets (binary: positive or negative)

## 2. Problem Statement

Social media content is often noisy and contains ambiguous expressions, sarcasm, slang, etc., making it difficult to classify sentiments accurately. This project addresses these challenges by:
- Cleaning and preprocessing tweet data
- Converting text to numeric features using TF-IDF
- Applying multiple classification algorithms for sentiment prediction

## 3. Objectives

- Clean and preprocess tweet data effectively
- Train and evaluate multiple machine learning models
- Compare performance using metrics like accuracy, precision, recall, and F1-score

## 4. Dataset

- **Source:** Twitter Sentiment Dataset (1.6M tweets)
- **Labels:** Positive (1), Negative (0)
- **Challenges:** Short text, sarcasm, noise (hashtags, emojis), no neutral class

## 5. Preprocessing

- Convert to lowercase
- Remove URLs, mentions, hashtags, numbers, and punctuation
- Tokenization and vectorization using **TF-IDF**

## 6. Machine Learning Models

| Model                  | Accuracy |
|------------------------|----------|
| Logistic Regression    | 79.03%   |
| SGD Classifier         | 78.04%   |
| XGBoost                | 72.75%   |

## 7. Evaluation

- **Logistic Regression**: Best performance overall, balanced precision and recall
- **SGD**: Better recall on positive class
- **XGBoost**: Struggled with negative sentiment recall

## 8. Metrics Used

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve

## 9. Future Scope

- Integrate deep learning models like BERT or RoBERTa for better context understanding
- Improve sarcasm and ambiguity detection
- Apply to real-time social media monitoring and hate speech detection

## 10. Applications

- **Brand Monitoring**
- **Customer Feedback Analysis**
- **Fake News & Hate Speech Detection**
- **Social Trend Prediction**

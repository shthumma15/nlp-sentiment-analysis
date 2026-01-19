# Sentiment Analysis on Product Reviews using NLP

## Project Overview
This project analyzes customer product reviews to determine sentiment (positive or negative) using Natural Language Processing (NLP) and machine learning.  
The goal is to help businesses understand customer satisfaction and identify areas for product improvement.

---

## Dataset
Amazon product reviews dataset provided in FastText format (`train.ft.txt`, `test.ft.txt`).

Each review contains:
- Review text
- Sentiment label (positive / negative)

Due to dataset size, a representative sample was used for modeling.

---

## Approach
- Parsed raw FastText text files into structured data
- Sampled 100,000 balanced reviews for efficient training
- Cleaned text (lowercasing, punctuation removal, stopwords)
- Converted text into numerical features using TF-IDF
- Trained a Logistic Regression classifier
- Evaluated model performance using accuracy and recall
- Interpreted influential words driving sentiment

---

## Results
- Accuracy: ~87.7%
- Recall (Negative Sentiment): ~88%
- Strong ability to identify dissatisfied customers

---

## Key Insights
- Words such as *excellent* strongly drive positive sentiment.
- Words such as *disappointing* strongly drive negative sentiment.
- Customer dissatisfaction is often linked to product quality issues.

---

## Business Recommendations
- Monitor negative reviews to detect recurring issues early.
- Use sentiment analysis to prioritize product quality improvements.
- Leverage positive feedback to reinforce strengths in marketing.

---

## Tools Used
Python, Pandas, Scikit-learn, TF-IDF, Logistic Regression, Jupyter Notebook

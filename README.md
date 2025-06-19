# Fake News Detection using NLP & Machine Learning

This repository contains a Jupyter Notebook implementation for detecting fake news using machine learning techniques. It processes a dataset of news headlines and bodies, vectorizes the text, and trains a model to classify the news as *real* or *fake*.

## Project Highlights

- Text preprocessing using `TfidfVectorizer`
- Supervised classification using `PassiveAggressiveClassifier`
- Accuracy evaluation and prediction
- Model pipeline built for real-world binary classification of news articles

## Dataset Information

The dataset used in this project is typically a CSV file with the following structure:

- `text`: The body or headline of the news article
- `label`: Either "REAL" or "FAKE" indicating the article's authenticity

> You can download a similar dataset from [Kaggle - Fake News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

## ML Workflow

1. **Data Loading & Exploration**
2. **Text Vectorization (TF-IDF)**
3. **Train-Test Split**
4. **Model Training** using `PassiveAggressiveClassifier`
5. **Accuracy & Performance Evaluation**
6. **Prediction Testing**

## Libraries Used

- `pandas`
- `sklearn`
- `numpy`
- `TfidfVectorizer`
- `PassiveAggressiveClassifier`

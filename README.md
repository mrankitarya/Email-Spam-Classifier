# Email Spam Classifier using Machine Learning (M.L.) & Deep Learning (D.L.)

## Overview

This repository contains two implementations of an email spam classification model:

1. **Machine Learning Approach (Logistic Regression)**: Utilizes logistic regression to classify emails as either spam or ham (non-spam).
2. **Deep Learning Approach (LSTM)**: Implements a Long Short-Term Memory (LSTM) model for more advanced classification, capturing dependencies in sequences for better performance in spam classification tasks.

## Requirements

- Python 3.x
- Libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `tensorflow`
  - `keras`
  - `matplotlib`
  - `seaborn`
  - `nltk`
  - `scipy`

## Machine Learning (Logistic Regression)
- In this approach, logistic regression is used as a classifier. The steps followed are:
- Data Preprocessing:
  - Text cleaning (removal of stop words, punctuation, etc.)
  - Tokenization and TF-IDF vectorization.
    
- Model Training:
  - Logistic regression model is trained on the vectorized email data.
    
- Model Evaluation:
  - Performance is evaluated using metrics like accuracy, precision, recall, and F1-score.

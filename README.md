# Email Spam Classifier using Machine Learning (M.L.) & Deep Learning (D.L.)

## Overview

This repository contains two implementations of an email spam classification model:

1. **Machine Learning Approach (Logistic Regression)**: Utilizes logistic regression to classify emails as either spam or ham (non-spam).Achieved an accuracy of approximately 96.59%.
  
3. **Deep Learning Approach (LSTM)**: Implements a Long Short-Term Memory (LSTM) model for more advanced classification, capturing dependencies in sequences for better performance in spam classification tasks. Achieved an accuracy of approximately 98.74%, demonstrating the effectiveness of LSTM in capturing sequential information for text classification.

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


## Deep Learning (LSTM)
- This approach uses Long Short-Term Memory (LSTM) networks, which are well-suited for 
  sequence prediction tasks. The key steps involved are:

- Text Preprocessing:
  - Text cleaning and tokenization.
  - Sequence padding and word embeddings.
    
- Model Architecture:
  - LSTM layers are used to capture the temporal dependencies in the text data.
    
- Model Training:
  - The model is trained using the processed data, and the loss and accuracy are monitored.

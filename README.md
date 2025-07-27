# Sentiment-Analysis-with-NLP
This repository contains a simple and effective implementation of sentiment analysis using Natural Language Processing (NLP) techniques. It classifies movie reviews into positive or negative sentiments using machine learning.


## Contents Overview

- NLP.ipynb: Notebook with preprocessing, feature extraction, model training, and evaluation.

## Steps

- Text preprocessing: lowercase, punctuation removal, stopword filtering, stemming
- Feature extraction: Bag of Words, Tokenization, Padding
- Model training with:
  - Naive Bayes
  - Support Vector Machine (SVM)
  - Long Short-Term Memory (LSTM)
- Accuracy evaluation on test data

## Requirements Install dependencies: 
```bash 
pip install pandas numpy matplotlib seaborn nltk scikit-learn tensorflow
``` 
## Models & Dataset

- Dataset: IMDB Dataset (binary sentiment)
- Models:
  - Naive Bayes
  - Support Vector Machine (SVM)
  - LSTM (Keras/TensorFlow)

## How to Use

1. Clone the repository
2. Open `NLP.ipynb` in Jupyter Notebook
3. Run all cells to:
   - Preprocess the data
   - Train the models
   - Evaluate and compare results



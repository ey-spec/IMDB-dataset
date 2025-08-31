IMDB Sentiment Analysis

This project implements sentiment analysis on the IMDB Dataset of 50K Movie Reviews. The goal is to classify movie reviews as positive or negative using both traditional machine learning and deep learning approaches.

Dataset

Source: IMDB 50K Movie Reviews Dataset

The dataset contains 50,000 reviews labeled as positive or negative.

Steps
1. Text Preprocessing

Removed HTML tags

Converted text to lowercase

Removed punctuation and extra whitespaces

Removed stopwords

Applied stemming and lemmatization

2. Feature Extraction

Used TF-IDF Vectorizer to transform text into numerical features.

3. Logistic Regression Model

Built and trained a logistic regression classifier.

Achieved around Train Accuracy: ~92% and Test Accuracy: ~89%.

4. Neural Network Model

Implemented a feedforward neural network using Keras.

Achieved Train Accuracy: ~93% and Test Accuracy: ~89%.

Plotted training and testing accuracy across epochs.

Future Work

Experiment with LSTM / GRU models for better sequence handling.

Use pre-trained embeddings (e.g., GloVe, Word2Vec) for richer feature representation.

Apply regularization techniques to improve generalization.

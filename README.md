# Sentiment Analysis using TF-IDF and Multinomial Naive Bayes

This project focuses on sentiment analysis of text data using the Term Frequency-Inverse Document Frequency (TF-IDF) model and the Multinomial Naive Bayes algorithm. The goal is to convert text documents into a matrix of TF-IDF features and build a classification model to predict sentiment.

## Introduction

The TF-IDF model is a numerical measure of the importance of words in a document collection. It is used to convert text documents into a matrix of TF-IDF features, which can be used for various natural language processing tasks, including sentiment analysis.

### Labeling the Sentiment Text and Data Splitting

In this project, the text data is labeled with sentiment labels (e.g., positive and negative) and split into training and test datasets for model evaluation.

### Vectorization with Word Embeddings

Word Embeddings, also known as Word Vectorization, is an NLP technique used to map words or phrases from a lexicon to corresponding vectors of real numbers. These word vectors can capture word semantics and are essential for text analysis.

## Modelling

The project includes the following steps for modeling:

1. **Multinomial Naive Bayes for Bag of Words (BoW):** The Multinomial Naive Bayes algorithm is applied to the BoW representation of text data.

2. **Multinomial Naive Bayes for TF-IDF Features:** The Multinomial Naive Bayes algorithm is applied to the TF-IDF features of the text data.

## Model Training and Performance Evaluation

The models are trained using the labeled data, and their performance is evaluated on the test dataset. Model performance metrics, including accuracy, are calculated to assess the quality of predictions.

### Accuracy of the Model

The accuracy of both the BoW-based and TF-IDF-based models is calculated to measure their predictive performance.

### Visualizing the Classification Report

The classification report is visualized to provide detailed information on model performance, including precision, recall, and F1-score.

### Confusion Matrix

A confusion matrix is generated to show how well the classification models perform on the test data, indicating true positives, true negatives, false positives, and false negatives.

## Visualizing Positive and Negative Words

Word clouds are created to visualize the most frequently occurring positive and negative words in the text data. Word clouds provide a graphical representation of word frequency and importance.

## Word Cloud for Positive Review Words

A word cloud is generated to display the most frequent positive review words in the dataset.

### Word Cloud for Negative Review Words

A word cloud is generated to display the most frequent negative review words in the dataset.

## Usage

To use this project:

1. Clone this repository.
2. Install the required Python libraries mentioned in the project's setup instructions.
3. Run the provided scripts or Jupyter notebooks to perform sentiment analysis and visualize results.

---

**Author:** Devanshu3


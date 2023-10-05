# AtharvaShinde_INBT04755_September2023
# THIS PROJECT IS MADE FOR INTERNSHIP iNeuBytes
# IMDb Movie Review Sentiment Analysis

This project involves data cleaning, tokenization, and Naive Bayes classification on the IMDb movie review dataset. The goal is to analyze and predict the sentiment (positive or negative) of movie reviews.

## Table of Contents

- [Introduction](#introduction)
- [Data Cleaning](#data-cleaning)
- [Tokenization](#tokenization)
- [Sentiment Analysis](#sentiment-analysis)
- [Data Visualization](#data-visualization)
- [Model Evaluation](#model-evaluation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we perform the following tasks:

- Data Cleaning: We handle missing values, remove duplicates, and verify the consistency of sentiment labels.

- Tokenization: We tokenize the text data using the NLTK library, removing stopwords, special characters, and converting words to lowercase. The tokenized reviews are then used to create features.

- Sentiment Analysis: We train a Naive Bayes classifier using both Bag-of-Words (BoW) and TF-IDF features to predict sentiment labels.

- Data Visualization: We visualize the distribution of sentiment labels, word frequency, and generate word clouds.

- Model Evaluation: We evaluate the model using accuracy, precision-recall curves, and ROC curves.

## Data Cleaning

- Handling missing values.
- Removing duplicate rows.
- Ensuring sentiment labels are 'positive' and 'negative.'

## Tokenization

- Removing HTML tags and special characters.
- Converting text to lowercase.
- Tokenizing the text.
- Removing stopwords.
- Stemming the words.

## Sentiment Analysis

- Splitting the dataset into training and testing sets.
- Extracting features using Bag-of-Words (BoW) and TF-IDF.
- Training a Naive Bayes classifier.
- Evaluating the model's performance.

## Data Visualization

- Visualizing the distribution of sentiment labels.
- Generating word cloud visualizations.
- Illustrating the top N most frequent words.

## Model Evaluation

- Calculating accuracy, precision, recall, and F1-score.
- Visualizing the confusion matrix.
- Plotting precision-recall and ROC curves.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Psyrus7/Major_Project.ipynb
   cd imdb-sentiment-analysis

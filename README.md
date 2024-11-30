# Sentiment Analysis of Tweets using Logistic Regression

This repository contains a machine learning project designed to classify the sentiment of tweets as either positive or negative. The project uses a Logistic Regression model combined with a TF-IDF vectorizer to convert text data into numerical features. Stemming is applied to reduce words to their root forms to improve model performance. The project includes steps for data preprocessing, model training, and evaluation.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Model Training and Evaluation](#model-training-and-evaluation)

## Project Overview

This machine learning project aims to classify the sentiment of tweets as either **positive** or **negative**. It utilizes the following techniques:
- **TF-IDF Vectorization**: Converts text data into numerical format.
- **Logistic Regression**: The model used for sentiment classification.
- **Stemming**: Reduces words to their root form to improve feature consistency.
- **Stopword Removal**: Filters out commonly used words that do not contribute to sentiment.

The dataset used is the Sentiment140 dataset, which contains tweets labeled as either positive (1) or negative (0). The model is trained on the pre-processed data and evaluated using accuracy metrics.

## Installation

To get started with this project, you need to have the following dependencies installed:

```bash
pip install numpy pandas scikit-learn nltk


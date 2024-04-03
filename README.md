# Natural-Language-Processing-NLP-
# Sentiment Analysis on Amazon Book Reviews

## Overview
This project is dedicated to predicting Amazon book ratings through the sentiment analysis of book reviews. Utilizing various machine learning models and natural language processing (NLP) techniques, the aim is to effectively discern between positive, negative, and neutral sentiments in reviews and predict their corresponding ratings.

## Dataset
The dataset is sourced from 'Amazon Books Reviews' on Kaggle, consisting of two main tables: book details and book reviews. It features over 3 million reviews, encompassing titles, authors, categories, ratings, review titles, review summaries, and review scores.

## Features
- **Text Preprocessing**: Applying lemmatization and handling NaN values to clean and prepare data for modeling.
- **Model Training**: Exploration of SVM models with RBF and linear kernels, MLP Classifier, and Naive Bayes classifier on review texts and summaries.
- **Sentiment Analysis**: Focused on distinguishing between different sentiments to predict review ratings.
- **Rating Prediction**: Predicting specific book ratings from review texts using SVM models.

## Results
The SVM model with RBF kernel function showed the highest accuracy, demonstrating its capability in handling sentiment analysis for book review ratings.

## Installation
Instructions on how to set up the project environment.

```bash
# Clone the repository
git clone <repository-url>

# Install dependencies
pip install -r requirements.txt












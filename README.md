# Sentiment-Analysis-of-Product-Reviews

This project analyzes product reviews by employing two different sentiment analysis techniques: VADER (Valence Aware Dictionary and sEntiment Reasoner) and a fine-tuned RoBERTa model. The analysis includes visualizing the relationship between sentiment scores and product ratings and comparing sentiment results across models. The main objectives are to evaluate model performance on review text and to explore which approach provides better insights into the sentiment within customer reviews.

# Project Overview
In this project, we leverage both VADER and a RoBERTa-based model to perform sentiment analysis on product review data. This dual approach helps us understand the nuances of different sentiment analysis techniques and how they can be applied to real-world review data.

# Key Features

## Data Preprocessing:
1. Loading and initial exploration of Amazon product review data.
2. Data sampling and preliminary visualization of review distribution by rating.

## Sentiment Analysis with VADER:
1. Using VADER's lexicon-based sentiment analysis tool for a quick and interpretable assessment.
2. Visualizing VADER’s positive, neutral, and negative scores against product ratings.

## Sentiment Analysis with RoBERTa:
1. Using Hugging Face's pre-trained RoBERTa model to analyze sentiment on a deeper, context-aware level.
2. Comparison of VADER and RoBERTa sentiment scores.

## Model Evaluation:
1. Visualizations comparing sentiment scores from VADER and RoBERTa to actual ratings.
2. Error analysis to track cases where models agree or disagree with user-provided sentiments.
   
## Naive Bayes Classifier:
1. Building and training a Naive Bayes model on processed review data to classify sentiment based on manually labeled examples.
2. Testing classifier accuracy and performance on the dataset.

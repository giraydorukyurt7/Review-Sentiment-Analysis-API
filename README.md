# Review Sentiment Analysis API

This project is a Flask-based sentiment analysis API for classifying customer reviews as positive or negative using NLP and machine learning models.

## Overview

The project focuses on review sentiment classification over an e-commerce review dataset. Although the original dataset includes variables such as star rating, helpful count, title, and review text, this implementation mainly uses the **Review** field for text-based sentiment analysis.

The workflow includes:

- sentiment labeling with NLTK's `SentimentIntensityAnalyzer`
- training baseline machine learning models
- serving predictions through a Flask-based API
- testing predictions through a lightweight interface / API flow

This repository is best viewed as a practical NLP + Flask API project rather than a completed full-stack product.

## Dataset Background

The dataset was created in the context of analyzing customer reviews for a product group in order to better understand complaints and satisfaction patterns.

### Dataset contains

- 4 variables
- 5,611 observations

### Variables

- **Star**: Number of stars given to the product
- **Helpful**: Number of people who found the comment helpful
- **Title**: Short review title
- **Review**: Full customer review text

## Method

The sentiment pipeline is based on review text classification.

Main steps:

1. preprocessing review text
2. generating sentiment labels with NLTK `SentimentIntensityAnalyzer`
3. training machine learning models
4. exposing predictions through Flask

## Models

The project includes sentiment classification models based on:

- Logistic Regression
- Random Forest

These models are functional and can be tested through the Python-based API flow.

## Application

The backend API is implemented with Flask.

A lightweight frontend / interface was also started for testing predictions, but the main completed component of the project is the Flask-based API and model inference workflow.

## Technologies Used

- Python
- Flask
- NLTK
- scikit-learn
- Pandas
- NumPy

## Notes

This project focuses primarily on:

- NLP-based sentiment classification
- API-oriented deployment logic
- practical experimentation with classical machine learning models for text analysis

It is not intended to be a polished production interface; the strongest part of the repository is the working sentiment analysis pipeline and Flask API integration.

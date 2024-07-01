## SMS SPAM CLASSIFIER

## Overview 
*  This project implements a machine learning model to classify SMS messages as either spam or ham (non-spam).
*  The goal is to develop a classifier that accurately identifies spam messages to help users filter unwanted content.

## Features 
*  Text Preprocessing: Tokenization, stop word removal, and stemming.
*  Feature Extraction: TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
*  Machine Learning Model: Naive Bayes classifier.

## Technologies Used
*  Python: Programming language used for implementation.
*  Libraries: Scikit-learn, NLTK for natural language processing tasks.
*  Tools: Jupyter Notebook for development and testing.
*  StreamLit: For deployment 

## Dataset
*  Source: The dataset used is the SMS Spam Collection from the UCI Machine Learning Repository.
*  Format: CSV format with labeled messages (spam/ham).
*  Preprocessing: Text data was cleaned by removing special characters, lowercasing, and standardizing text formatting.

## Model
*  Naive Bayes Classifier: Trained on TF-IDF vectorized text data.
*  Performance: Achieved an accuracy of 98% on the test dataset. 

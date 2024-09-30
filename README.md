# CODTECH-Task2
Name: Ninad chaudhari
Company: CODTECH IT SOLUTIONS 
Intern ID: CT08DS7778 
Domain: ML

Project Overview

This project implements a text classification model using the Multinomial Naive Bayes algorithm. The model processes raw text data, converts it into numerical features using natural language processing techniques, and then classifies the text into predefined categories. The project makes use of Python libraries such as pandas, nltk, and scikit-learn.

Key Features

Data Preprocessing: Clean and prepare raw text data by:

Removing special characters, stopwords, and unnecessary punctuation.

Stemming words to their root forms using the Porter Stemmer.


Feature Extraction: Use CountVectorizer to transform the text into numerical features representing word frequencies.

Model Training:

Train a Multinomial Naive Bayes classifier on the processed text data.

The dataset is split into training and testing sets to evaluate model performance.


Model Evaluation:

Evaluate the model using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.


Model Saving: Save the trained model using pickle for later use.


Dependencies

Python 3.x

pandas

numpy

nltk

scikit-learn

seaborn

pickle


How to Run

1. Clone the repository.


2. Install the required dependencies using pip install -r requirements.txt.


3. Run the Jupyter notebook or Python script to load data, preprocess it, train the model, and evaluate performance.



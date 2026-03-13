# Language Detection using Machine Learning
Project Overview

This project focuses on building a Language Detection Model that predicts the language of a given text. Machine learning techniques are used to convert text data into numerical format and train a classification model.
The model learns patterns from different languages and predicts the correct language for new text inputs.

Problem Statement

Computers cannot understand text directly. Therefore, we need to convert textual data into numerical form so that machine learning algorithms can process it and make predictions.
This project solves the problem by using Natural Language Processing (NLP) techniques.

Dataset

The dataset contains two main columns:

Text – Sentence or paragraph in a particular language

Language – The language label for the text

Example:

Text	Language
Hello how are you	English
Bonjour comment ça va	French
Hola como estas	Spanish
Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Natural Language Processing (NLP)

Machine Learning Workflow

Import required libraries

Load the dataset

Data cleaning and preprocessing

Convert text to numerical features using CountVectorizer (Bag of Words)

Split data into training and testing sets

Train the model using Multinomial Naive Bayes

Evaluate model accuracy

Predict language for new text

Model Used

Multinomial Naive Bayes

This algorithm works well for text classification problems because it is efficient with word frequency features.

Feature Engineering

Text data is converted into numbers using:

CountVectorizer

This technique creates a Bag of Words representation, which counts the frequency of each word in the dataset and converts it into a numerical matrix.

Example Prediction

Input:

Bonjour je m'appelle Prachi

Output:

Predicted Language: French
Project Structure
Language-Detection
│
├── Language Detection.ipynb
├── language.csv
├── README.md
Future Improvements

Use TF-IDF Vectorizer

Try Logistic Regression or SVM

Build a web app using Streamlit

Deploy the model online

Author

Prachi Priya
BTech – Civil Engineering (NIT Jamshedpur)
Aspiring Data Analyst / Data Scientist

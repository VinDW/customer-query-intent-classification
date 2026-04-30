# Customer Query Intent Classification using NLP

## Overview

This project applies Natural Language Processing and Machine Learning techniques to classify customer queries into business-relevant intent categories.

The project demonstrates how unstructured customer text can be transformed into structured insights that support service automation, query routing, and business decision-making.

This project was developed as part of a data science portfolio focused on Natural Language Processing, machine learning, model evaluation, and business-facing analytics.

## Business Problem

Organisations receive large volumes of customer messages through emails, chatbot systems, call centres, mobile applications, and online platforms. Manually reading and routing these messages can be time-consuming and inefficient.

This project demonstrates how NLP can be used to classify customer queries into predefined intent categories, allowing organisations to route queries more efficiently, reduce response times, and improve customer service.

## Intent Categories

The customer queries are classified into the following categories:

- Claim enquiry
- Policy update
- Benefit question
- Complaint
- Payment issue
- General information request

## Objectives

The objectives of this project are to:

- Create a structured customer query dataset
- Clean and preprocess unstructured text data
- Perform exploratory text analysis
- Build machine learning models for intent classification
- Evaluate model performance using classification metrics
- Save the best-performing model for future use
- Communicate findings clearly for both technical and business audiences

## Methods

The project uses the following methods:

- Text preprocessing
- Exploratory text analysis
- TF-IDF vectorisation
- Logistic Regression
- Multinomial Naive Bayes
- Support Vector Machine
- Model comparison and evaluation

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook
- GitHub

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Cross-validation accuracy

## Project Structure

```text
customer-query-intent-classification/
│
├── README.md
├── data/
│   └── customer_queries.csv
│
├── notebooks/
│   ├── 01_data_creation_and_cleaning.ipynb
│   ├── 02_exploratory_text_analysis.ipynb
│   └── 03_model_training.ipynb
│
├── outputs/
│   ├── figures/
│   └── tables/
│
├── models/
│   └── best_intent_classifier.pkl
│
├── requirements.txt
└── report.md

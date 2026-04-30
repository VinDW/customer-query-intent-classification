# Customer Query Intent Classification Report

## 1. Project Overview

This project develops a Natural Language Processing model for classifying customer queries into predefined intent categories. The aim is to demonstrate how unstructured customer messages can be transformed into structured business insights using Python and machine learning.

## 2. Business Problem

Organisations often receive large volumes of customer messages through digital channels such as emails, chatbots, mobile applications, and online support systems. Manually reviewing and routing these messages can delay service delivery and increase operational workload.

A customer query intent classification model can help automatically identify the purpose of each customer message and route it to the appropriate support team.

## 3. Data

The dataset used in this project is synthetically generated for portfolio and demonstration purposes. It contains customer queries grouped into six intent categories:

- Claim enquiry
- Policy update
- Benefit question
- Complaint
- Payment issue
- General information request

No private or confidential customer information is used.

## 4. Methodology

The project follows a standard NLP and machine learning workflow:

1. Create a structured customer query dataset
2. Clean and preprocess text data
3. Perform exploratory text analysis
4. Convert text into numerical features using TF-IDF
5. Train supervised machine learning models
6. Compare model performance
7. Save the best-performing model for reuse

## 5. Models

The following models were trained and compared:

- Logistic Regression
- Multinomial Naive Bayes
- Support Vector Machine

All models used TF-IDF features extracted from the cleaned customer query text.

## 6. Evaluation

The models were evaluated using:

- Test accuracy
- Cross-validation accuracy
- Precision
- Recall
- F1-score

The final model was selected based on predictive performance and stability across evaluation metrics.

## 7. Business Value

This project shows how NLP can support business operations by:

- Automatically routing customer queries
- Reducing manual classification workload
- Improving response times
- Supporting chatbot and customer service automation
- Creating structured insights from unstructured text data

## 8. Conclusion

This project demonstrates a complete end-to-end NLP workflow, from data creation and preprocessing to model training, evaluation, and model saving. It provides practical evidence of skills in Python, machine learning, Natural Language Processing, model evaluation, and business communication.

# Understanding Customer Satisfaction with Machine Learning Methods
This repository contains the code and documentation for a term project conducted by İsmail GÜRLER at GAZİ UNIVERSITY in December 2022. 
The project aims to explore customer satisfaction using various machine learning algorithms on a real dataset from an airline company's survey results. 
The goal is to develop a predictive model that can accurately predict customer satisfaction levels.

## Abstract
The project delves into the application of machine learning algorithms for understanding customer satisfaction. Different machine learning models are employed on a dataset containing survey results from an airline company. 
The main objective is to build a prediction model that can accurately forecast customer satisfaction. 
The project involves data preprocessing, model selection, and performance evaluation. The results are presented using visualizations and compared with real data to gauge the model's effectiveness.

## Dataset
The dataset used for this project is available on Kaggle: [Airline Passengers Satisfaction Dataset](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction). 
It contains various attributes related to airline passengers' experiences and their satisfaction levels.

## Loading and Understanding the Data
The data is loaded using Python's Pandas library and inspected to understand its structure and attributes. Information about data types, missing values, and correlations between attributes is analyzed. 
Data preprocessing techniques are applied to handle missing values and remove unnecessary columns.

## Data Preprocessing
1. Missing values in the "Arrival Delay in Minutes" column are filled with the mean value.
2. Unnecessary columns like "Unnamed: 0" and "id" are dropped.
3. Categorical variables are encoded using one-hot encoding.

## Exploratory Data Analysis (EDA)
- Data visualizations are created to understand the distribution of categorical variables, customer satisfaction ratings, and numerical attributes.
- Correlation heatmap is generated to observe correlations between numerical attributes.

## Model Selection and Evaluation
Several machine learning algorithms are evaluated for predicting customer satisfaction:

* Logistic Regression
* Linear Discriminant Analysis
* K-Nearest Neighbors
* Decision Tree Classifier
* Naive Bayes

Models are cross-validated and their accuracies are compared using box plots. The Decision Tree Classifier is chosen for further analysis due to its promising performance.

## Model Performance
The Decision Tree Classifier is trained on the dataset.
The accuracy score, confusion matrix, and classification report are used to evaluate the model's performance on a validation set.

# Conclusion
The project successfully demonstrates the application of various machine learning algorithms for predicting customer satisfaction based on survey data. 
The Decision Tree Classifier showed high accuracy in predicting customer satisfaction levels. 
The code and findings presented in this project can be useful for companies looking to improve their understanding of customer satisfaction and enhance their services.

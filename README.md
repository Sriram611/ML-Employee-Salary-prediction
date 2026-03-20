# Employee Salary Prediction using Machine Learning

This project demonstrates a hands-on implementation of machine learning techniques for predicting employee salary using the Adult dataset.

## Overview
The project focuses on building and evaluating multiple machine learning models to understand their performance on a real-world dataset.

## Steps Performed
- Data cleaning and preprocessing
- Handling missing values
- Feature selection
- Outlier detection and removal
- Data encoding and normalization
- Model training and evaluation

## Models Used
- K-Nearest Neighbors (KNN)
- Multi-Layer Perceptron (MLP Classifier)
- Logistic Regression

## How I implemented this project
1. Imported necessary libraries for data processing and model training  
2. Loaded the Adult dataset for salary prediction  
3. Handled missing values by replacing '?' and removing irrelevant features  
4. Performed data cleaning by removing features that do not contribute to prediction  
5. Detected and handled outliers using boxplots (filtered age between 17 and 75)  
6. Dropped redundant features such as 'education' since 'education.num' was used  
7. Applied label encoding to convert categorical data into numerical format  
8. Split the dataset into training and testing sets  
9. Normalized the data using MinMaxScaler  
10. Trained multiple models including KNN, MLPClassifier, and Logistic Regression  
11. Compared model performance using accuracy metrics  

## Key Learning
This project helped in understanding the complete machine learning workflow from data preprocessing to model comparison.

## Note
This is a hands-on implementation completed as part of my learning during an AI & ML internship.

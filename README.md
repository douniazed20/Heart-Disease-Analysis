# Heart Disease Data Analysis and Prediction

## Overview
This project focuses on analyzing and modeling a dataset related to heart disease using Python.  
The goal is to explore the data, understand the relationships between features, and build a machine learning model to predict heart disease.

## Table of Contents
- Overview
- Project Structure
- Technologies Used
- Dataset Information
- Workflow
- Results
- Author

## Project Structure
- Data Exploration and Cleaning:  
  Loading the dataset, handling categorical data, and preparing it for analysis.
- Data Visualization:  
  Creating plots to understand the distribution and relationships between important variables.
- Statistical Analysis:  
  Calculating descriptive statistics for numerical features.
- Model Building:  
  Training a Logistic Regression model to predict heart disease.
- Model Evaluation:  
  Evaluating the model’s performance using confusion matrix and classification report.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset Information
- File Name: HeartDiseaseTrain-Test.csv
- Source: Kaggle
- Description:  
  Contains medical records of patients, including attributes such as age, chest pain type, maximum heart rate, and diagnosis of heart disease.

## Workflow
1. Loading the Data:  
   Importing the dataset into a DataFrame.
2. Preprocessing:  
   Encoding categorical variables and scaling the data.
3. Visualization:  
   - Target distribution plot.
   - Correlation heatmap.
   - Age distribution plot.
   - Scatter plot of Age vs Max Heart Rate.
4. Model Training:  
   Splitting the dataset into training and testing sets, and fitting a Logistic Regression model.
5. Evaluation:  
   Predicting the test set results and analyzing the model performance.

## Results
- The Logistic Regression model was successfully trained.
- The model achieved good evaluation metrics including precision, recall, and F1-score.
- Data visualizations provided valuable insights into the patterns and relationships in the dataset.

## Author
- Prepared by [Djeghar Douniazed].

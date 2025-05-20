Heart Disease Data Analysis and Prediction

🔍 Overview

This project presents a comprehensive analysis and prediction pipeline for heart disease using Python. The aim is to derive insights from patient data and construct accurate models that can predict the presence of heart disease.

📄 Table of Contents

Overview

Project Structure

Technologies Used

Dataset Description

Class Diagram

Workflow

Results and Visualizations

Author

🏗️ Project Structure

The project consists of the following stages:

1. Data Handling

Load the dataset using DonneesSante class

Inspect missing values and data types

Encode categorical variables

2. Visualization and Analysis

Use the AnalyseDonnees class for:

Correlation matrix heatmap

Target distribution

Age distribution

Scatter plot: Age vs Max Heart Rate

3. Modeling

Logistic Regression model

Decision Tree Classifier

4. Evaluation

Confusion matrix

Classification report

Performance metrics (accuracy, precision, recall, F1-score)

🛠️ Technologies Used

Python

Pandas

Matplotlib

Seaborn

Scikit-learn

Graphviz (used to generate the class diagram)

To install dependencies:

pip install pandas matplotlib seaborn scikit-learn graphviz

📁 Dataset Description

File: HeartDiseaseTrain-Test.csv

Source: Kaggle

Features Include:

Age, sex, chest pain type, blood pressure, cholesterol

Fasting blood sugar, ECG results, max heart rate, exercise-induced angina

Oldpeak, slope, vessels colored, thalassemia

Target: Presence (1) or absence (0) of heart disease

📐 Class Diagram

Two primary classes define the structure:

DonneesSante

Loads and stores the dataset

Provides data preview, info, statistics, and missing value summary

AnalyseDonnees

Takes a DataFrame and provides statistical visualizations

Includes multiple plotting methods for exploring target and feature distributions

The diagram is generated using Graphviz and illustrates class attributes and methods for better architectural understanding.

🔄 Workflow

Data Import: Read CSV file into DataFrame.

Cleaning: Handle missing values, encode categorical columns.

Exploration:

Visualize target and numerical features

Analyze correlations

Modeling:

Train Logistic Regression & Decision Tree Classifier

Evaluation:

Generate classification reports

Compare model performance

📊 Results and Visualizations

Visualization Insights:

Class imbalance and age distribution visualized

Correlation heatmap revealed relationships between numerical features

Scatter plots helped detect trends between variables

Model Performance:

Logistic Regression and Decision Tree both performed well with distinguishable metrics

Decision Tree provided interpretability with slightly less generalization compared to Logistic Regression

Architecture:

Class diagram clearly explains the object-oriented structure of the solution

📎 Full visual outputs and models are included in the Jupyter notebook. Open it with JupyterLab or Google Colab.

👤 Author

Name: [Djeghar Douniazed/Merahi aya/Boudersa manal]GitHub: github.com/douniazed20



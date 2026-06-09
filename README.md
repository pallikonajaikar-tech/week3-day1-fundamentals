# week3-day1-fundamentals
# Week 3 Day 1 - Machine Learning Fundamentals

## Project Overview

This project demonstrates the complete Machine Learning workflow using a Student Performance Dataset. The objective is to predict student marks based on Study Hours, Attendance, and Assignments using the Linear Regression algorithm from Scikit-learn.

## Dataset Information

The dataset contains the following columns:

* Study_Hours
* Attendance
* Assignments
* Marks

### Features

* Study_Hours
* Attendance
* Assignments

### Label

* Marks

## Tasks Performed

### 1. Dataset Exploration

* Loaded the dataset using Pandas.
* Displayed first and last five records.
* Checked dataset shape, column names, and data types.
* Generated summary statistics.

### 2. Feature and Label Identification

Selected Study_Hours, Attendance, and Assignments as features (X) and Marks as the target variable (y).

### 3. Machine Learning Workflow

The project followed these steps:

* Data Collection
* Data Cleaning
* Feature Selection
* Train-Test Split
* Model Training
* Testing
* Evaluation
* Prediction

### 4. Train-Test Split

The dataset was divided into:

* 80% Training Data
* 20% Testing Data

### 5. Model Training

A Linear Regression model was trained using the training dataset.

### 6. Predictions

Predictions were made for new student records using the trained model.

### 7. Actual vs Predicted Comparison

The actual marks and predicted marks were compared to calculate prediction errors.

### 8. Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* R² Score

### 9. Data Visualization

Five Plotly visualizations were created:

1. Study Hours vs Marks
2. Attendance vs Marks
3. Assignments vs Marks
4. Regression Line Visualization
5. Predicted Marks Trend

### 10. Research Activity

Research was completed on:

* Machine Learning
* Linear Regression
* Features
* Labels
* Training Data vs Testing Data
* Real-Life Applications of Machine Learning

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Plotly

## Conclusion

The Linear Regression model successfully learned the relationship between student performance factors and marks. The project helped understand the complete Machine Learning workflow, model training, evaluation, prediction, and visualization techniques.

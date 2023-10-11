# ML_Project_2023
Machine Learning project for CS-C3240 - Machine Learning D, 4.9.2023-13.10.2023

Overview

This project focuses on sentiment analysis using two different machine learning models: Logistic Regression and Multilayer Perceptron (MLP) Classifier. The goal is to predict the sentiment (positive, neutral, or negative) of text data.

![bothmethods](https://github.com/MariusBoda/ML_Project_2023/assets/35667954/54120843-06cb-4c2b-8a3f-08490c02bf66)

# Sentiment Analysis Project

## Overview

This project focuses on sentiment analysis using two machine learning models: Logistic Regression and Multilayer Perceptron (MLP) Classifier. The goal is to predict sentiment (positive, neutral, or negative) in text data.

## Project Structure

### Data Preprocessing
The dataset is loaded from a CSV file, and preprocessing steps include cleaning, handling missing values, and transforming the sentiment column.

### Model Training
Two models, Logistic Regression and MLP Classifier, are trained on preprocessed data. The data is split into training, validation, and test sets. Models are evaluated using metrics such as accuracy, log loss, and classification reports.

### Model Comparison
Performance of the Logistic Regression and MLP Classifier models is compared, highlighting their strengths and weaknesses.

### Confusion Matrix Visualization
The confusion matrix is visualized using seaborn and matplotlib to provide insights into model performance across different sentiment classes.

### Sentiment Analysis Function
A function for sentiment analysis is included, allowing users to input text and receive predicted sentiment using the trained models.

## Usage

1. **Install Dependencies:**
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn

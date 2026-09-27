# Wine Quality Classification

## Project Overview

This project applies machine learning classification techniques to predict wine quality based on its physicochemical properties.

The dataset contains measurements such as acidity, residual sugar, chlorides, sulfur dioxide, pH, sulphates, and alcohol.

## Data Preprocessing

The project includes:

* Loading the wine quality dataset
* Data exploration and validation
* Checking for missing values
* Transforming the target variable into a binary classification problem
* Feature selection
* Feature scaling
* Splitting the data into training and testing sets

## Machine Learning Models

Several classification models were implemented and evaluated:

* Logistic Regression
* Perceptron
* Decision Tree
* Support Vector Machine (SVM)
* Random Forest

Hyperparameter tuning was performed using GridSearchCV for the models where applicable.

## Dataset

The project uses the Wine Quality dataset containing red wine measurements.

The target variable is transformed into:

* `1` → quality ≥ 6
* `0` → quality < 6

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Structure

```text
Wine-Quality-Machine-Learning/
│
├── wine_quality_classification.ipynb
├── winequality-red.csv
├── winequality-white.csv
├── winequality.names
└── README.md
```

## Models Evaluation

The implemented models are compared using classification performance metrics and visualizations such as confusion matrices and feature importance.

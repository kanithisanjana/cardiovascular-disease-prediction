# Cardiovascular Disease Prediction

This project uses **Machine Learning** to predict whether a person is likely to have cardiovascular disease based on health-related features.

## Project Overview

The dataset is analyzed using **Python, Pandas, NumPy, Matplotlib, and Seaborn**. Exploratory Data Analysis (EDA) is performed to understand relationships between factors such as age, gender, cholesterol, and blood pressure and cardiovascular disease.

Several machine learning classification algorithms are trained and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Support Vector Machine (SVM)
* Random Forest

The models are evaluated using accuracy and classification reports. **Random Forest** is selected as the final model in the project and is used to make predictions on new input data.

## Key Features

* Data loading and preprocessing
* Missing value and duplicate checking
* Exploratory Data Analysis
* Correlation analysis
* Feature scaling using StandardScaler
* Training multiple classification models
* Model accuracy comparison
* Classification report
* Cardiovascular disease prediction using the trained Random Forest model

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Machine Learning Workflow

**Data → Data Cleaning → EDA → Feature Scaling → Model Training → Model Comparison → Prediction**

## Dataset

The project uses a cardiovascular disease dataset containing health-related attributes such as age, gender, cholesterol level, and blood pressure. The target variable is `cardio`, which represents the presence or absence of cardiovascular disease.

## Result

Multiple classification models are compared based on their accuracy, with **Random Forest** used as the final prediction model.

> **Note:** This project is intended for educational and machine learning demonstration purposes and should not be used as a medical diagnostic tool.

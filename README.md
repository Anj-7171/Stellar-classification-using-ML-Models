# Star Classification Using Machine Learning

A machine learning project that compares multiple classification algorithms for predicting stellar categories using astronomical data. The project investigates how different supervised learning models perform on star classification tasks after preprocessing, feature encoding, and normalization.

## Overview

Astronomical datasets often contain complex relationships between stellar attributes such as temperature, luminosity, radius, color, and spectral class. This project applies several machine learning algorithms and evaluates their effectiveness in classifying stars into different categories.

<img width="713" height="541" alt="image" src="https://github.com/user-attachments/assets/bd18fb01-c3bf-4ef7-b8e8-776b38e6dba5" />


## Dataset Features

* Temperature
* Luminosity (L)
* Radius (R)
* Absolute Magnitude (A_M)
* Color
* Spectral Class

<img width="665" height="238" alt="image" src="https://github.com/user-attachments/assets/88aab3c2-eb1a-480f-b803-ac08d018560f" />


## Data Preprocessing

The following preprocessing techniques were applied:

* Missing value analysis
* Label encoding of categorical features
* Feature normalization using MinMaxScaler
* Feature standardization using StandardScaler
* Train-test split for model evaluation

## Models Evaluated

1. Gaussian Naive Bayes
2. K-Nearest Neighbors (KNN)
3. Decision Tree Classifier
4. Logistic Regression

## Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Naive Bayes         | 35%      |
| KNN                 | 90%      |
| Decision Tree       | 35%      |
| Logistic Regression | 96%      |

Logistic Regression achieved the highest classification accuracy of 96%, demonstrating strong performance on the processed dataset.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn

## Future Improvements

* Hyperparameter tuning using GridSearchCV
* Cross-validation for more robust evaluation
* Ensemble learning methods such as Random Forest and XGBoost
* Deployment using Streamlit or Flask

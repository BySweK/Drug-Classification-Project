# Drug Classification Project

This project implements a machine learning pipeline to classify patients into the correct medication type based on their health data.

## Project Overview
The goal of this project is to build and optimize a classification model using the **Drug200** dataset. The project demonstrates a complete data science workflow, including data preprocessing, feature encoding, scaling, and hyperparameter optimization.

## Key Features
*   **Data Preprocessing**: Handling categorical variables using `LabelEncoder` and `OrdinalEncoder`.
*   **Feature Scaling**: Standardizing features using `StandardScaler` to improve model performance.
*   **Modeling**: Comparing the performance of `Logistic Regression` and `Support Vector Classifier (SVC)`.
*   **Optimization**: Using `GridSearchCV` to find the best hyperparameters, resulting in an **accuracy of 98%**.

## Technologies Used
*   **Python**
*   **Pandas & NumPy** (Data manipulation)
*   **Scikit-Learn** (Machine Learning algorithms)

## Results
The final optimized SVC model achieved the following performance metrics:
*   **Accuracy**: 0.98
*   **F1-Score**: 0.98 (weighted average)

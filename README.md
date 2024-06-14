# Sonar-Rock-vs-Mine-prediction
This is the Logistic regression project to classifiy whether the sonar return is Rock or a Mine


![image](https://github.com/Atharva1702/Sonar-Rock-vs-Mine-prediction/assets/90234696/7981c2a0-4aac-4362-a079-a8b762cfbd49)


## Introduction
This project aims to predict whether a sonar signal corresponds to a rock or a mine using logistic regression. The dataset contains 60 features which are obtained from the sonar signals.

### Dataset
The dataset used is the Sonar Mines vs Rocks dataset, which contains 208 instances with 60 continuous attributes. Each attribute is a measure of the energy within a particular frequency band, integrated over a certain period of time. The target variable is binary, indicating whether the signal is a rock (R) or a mine (M).

Sonar Mines vs Rocks dataset from kaggle

### Feature Engineering
The feature engineering steps include:

Normalizing the feature values to ensure each feature contributes equally to the model.
Splitting the dataset into training and testing sets.

### Model Training & Results
The logistic regression model is trained using scikit-learn's LogisticRegression module. The model is evaluated using accuracy, precision, recall, and F1-score.

Results
The results of the model are as follows:

Accuracy: 85%

Precision: 84%

Recall: 86%

F1-Score: 85%

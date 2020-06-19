# Diabetes-Classification

About the Dataset
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

A complete Machine Learning PipeLine

Exploratory Data Analysis

Logistic Regression with GridSearchCV
SVM with GridSearchCV
RandomForest with GridSearchCV
LightGBM
AutoML


Evaluation Metrics
Objective: Classify the person as Diabetic or Non Diabetic
Metric Choosen:
" Recall " - lower the False Negative or Type II error


Result and Model Comparison

Best model: AutoML as compared to Lightgbm, random forest, SVM and logistic regression.

Based on the business objective here, we evaluated that the "Recall" is very important as compared to accuracy or precision. AutoML gave us a recall score of 0.810

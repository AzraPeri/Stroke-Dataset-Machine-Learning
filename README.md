Stroke Dataset Machine Learning

This repository presents a complete machine learning workflow built on the Stroke Prediction Dataset. The project focuses on predicting stroke risk by applying multiple classification algorithms, performing thorough data preprocessing, and comparing model performances using common evaluation metrics.

🔍 Project Overview

Stroke is one of the leading causes of mortality and long-term disability worldwide. Early detection of stroke risk can significantly reduce severe health consequences.
In this study, a set of 15 different machine learning models was trained, optimized, and evaluated to identify the most effective method for stroke-risk classification.

📁 Dataset

Source: Kaggle – Stroke Prediction Dataset
Records: 4909 individuals
Features: 12 input variables + 1 target variable (stroke)

The dataset includes demographic, medical, and lifestyle attributes such as age, gender, hypertension, heart disease, average glucose level, BMI, and smoking status.

🛠️ Methodology
1. Data Preprocessing

Handling missing values

Encoding categorical variables

Scaling numerical variables

Balancing the target variable using SMOTE

Train–test split (70/30)

2. Model Training

A total of 15 machine learning algorithms were implemented, including:

Random Forest

Gradient Boosting

Hist Gradient Boosting

SVM

MLP (Neural Network)

AdaBoost

Extra Trees

Bagging

Decision Tree

Logistic Regression

Naive Bayes

KNN

LDA / QDA

Voting Classifier (Best Overall Performance)

3. Evaluation Metrics

Accuracy

Precision

Recall

F1-Score

ROC–AUC

🧪 Results

Among all trained models, the Voting Classifier achieved the highest overall performance, showing strong improvements across accuracy, recall, and AUC.
Tree-based ensemble methods such as Random Forest and Hist Gradient Boosting also provided highly competitive results.

🧪 Results

Among all trained models, the Voting Classifier achieved the highest overall performance, showing strong improvements across accuracy, recall, and AUC.
Tree-based ensemble methods such as Random Forest and Hist Gradient Boosting also provided highly competitive results.

🎯 Purpose of the Study

The project aims to explore how different machine learning techniques perform on medical classification tasks and how these approaches can support early detection and decision-making systems in healthcare.

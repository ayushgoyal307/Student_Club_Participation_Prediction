# Student_Club_Participation_Prediction

# 🎓 Student Club Participation Prediction

This project uses supervised machine learning to predict whether a student will join a club based on interest levels and schedule availability. The aim is to help institutions identify and engage students likely to participate in extracurricular activities.

---

## 📌 Problem Statement

Given student-related data such as interest levels and free hours per week, the task is to predict whether the student will participate in a club. This is framed as a binary classification problem (`Yes` or `No`).

---

## 🎯 Objectives

- Preprocess the dataset for training a machine learning model.
- Train a Logistic Regression classifier.
- Evaluate model performance using standard classification metrics.
- Visualize the confusion matrix using a heatmap.

---

## 🧠 Methodology

### 🔹 Data Preprocessing
- Handle missing values (mean for numerical, mode for categorical).
- Encode categorical variables.
- Normalize features using StandardScaler.

### 🔹 Model Training
- Split dataset into training and test sets (80/20).
- Train a **Logistic Regression** model.

### 🔹 Model Evaluation
- Evaluate using Accuracy, Precision, Recall, F1 Score.
- Visualize confusion matrix using Seaborn heatmap.

---

## 🗂️ Project Structure


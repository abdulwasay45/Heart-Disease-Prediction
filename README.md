# Heart-Disease-Prediction
# ❤️ Heart Disease Prediction Using Machine Learning
#Submisson By DHC-1768
## 📌 Project Overview
This project builds a machine learning model to predict whether a person is at risk of heart disease based on their medical and health-related attributes.  
It uses the **Heart Disease UCI Dataset** and applies classification techniques to support early detection.
---
## 🎯 Objective
- Clean and preprocess medical dataset
- Perform Exploratory Data Analysis (EDA)
- Train a classification model (Logistic Regression / Decision Tree)
- Evaluate model performance using multiple metrics
- Identify important features affecting heart disease risk
---
## 📊 Dataset
- Dataset: Heart Disease UCI Dataset  
- Source: Kaggle  
- Type: Medical tabular dataset
### Target Variable:
- `1` → Presence of heart disease  
- `0` → No heart disease  
---
## 🛠️ Tools & Libraries Used
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
---
## ⚙️ Project Workflow
### 1. Data Cleaning
- Handled missing values
- Checked data types and inconsistencies
- Removed or imputed invalid entries
---
### 2. Exploratory Data Analysis (EDA)
- Distribution of age, cholesterol, blood pressure
- Correlation heatmap
- Relationship between features and heart disease
- Visualization of key risk factors
---
### 3. Feature Selection
- Selected important health indicators such as:
  - Age
  - Chest pain type
  - Cholesterol
  - Blood pressure
  - Maximum heart rate
---
### 4. Model Training
Two classification models used:
- Logistic Regression 📉  
- Decision Tree 🌳  
Model learns patterns between health indicators and disease presence.
---
### 5. Model Evaluation
Performance measured using:
- Accuracy Score  
- Confusion Matrix  
- ROC Curve  
- ROC-AUC Score  
---
### 6. Feature Importance
- Identified which health factors contribute most to prediction
- Visualized important features using bar plots
---
## 📂 Project Structure
heart-disease-prediction/
│
├── dataset.csv
├── model.py / notebook.ipynb
├── README.md
## 🚀 How to Run This Project
### 1. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook

# solubility-prediction-ml
# 🧠 My First Machine Learning Project

Welcome to my first Machine Learning project! 

---

## 🚀 Project Overview

This project aims to predicts the **aqueous solubility of molecules** using molecular descriptors. It's built using Python and common ML libraries like scikit-learn, pandas, and matplotlib.

---

## 📊 Dataset

- **Dataset Used**: delaney_solubility_with_descriptors.csv
- **Source**: (https://github.com/dataprofessor/data/blob/master/delaney_solubility_with_descriptors.csv)
- **Description**: The dataset contains features such as MolLogP, MolWt,	NumRotatableBonds and	AromaticProportion used to predict logS.

---

## 🔍 Problem Statement

Build a regression model to **predict the solubility (logS)** of molecules based on their molecular descriptors.
This involves:
- Data loading amd preparation 
- Exploratory Data Analysis (EDA)
- Model selection, building and training
- Evaluation and validation

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🔍 Workflow
Data Loading & Cleaning

- Load and clean the dataset, handling missing values and selecting relevant features.

Exploratory Data Analysis (EDA)

- Visualize distributions, correlations, and detect outliers.

Modeling

- Train machine learning models like Linear Regression and Random Forest

Model Evaluation

- Evaluate models using metrics like Training MSE,	Training R2,	Test MSE and	Test R2.

Data Visualization

- Data Visualized using libraries like matplotlib and numpy

---

## 📈 Results

| Method            | Training MSE | Training R2 | Test MSE  | Test R2  |
| ----------------- | ------------ | ----------- | --------- | -------- |
| Linear Regression | 1.007536     | 0.764505    | 1.020695  | 0.789162 |
| Random Forest     | 1.007536     | 0.764505    | 1.020695  | 0.789162 |








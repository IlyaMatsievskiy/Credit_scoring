# Credit Scoring Project

This README describes the steps taken for data preprocessing, training machine learning models, and evaluating their performance for a credit scoring project. If you want to read the description in Russian, open README_ru or credit_scoring.ipynb.

---

## Table of Contents

1. Library Installation
2. DataFrame Assembly and Exploration
3. Data Analysis
4. Data Visualization
5. Data Encoding
6. Data Splitting and Scaling
7. Dimensionality Reduction
8. Model Training (RandomForest, XGBoost)

---

## 1. Library Installation

The required libraries for this project were installed and imported, including pandas, NumPy, matplotlib, seaborn, xgboost and sklearn.

---

## 2. DataFrame Assembly and Exploration

- A DataFrame was created from a CSV file.
- Initial exploration was conducted to understand the structure of the dataset.

---

## 3. Data Analysis

- An exploratory data analysis (EDA) was conducted.
- Columns containing more than 80% missing values were removed, as well as columns that do not affect credit decision-making.

---

## 4. Data Visualization

- Various graphs were plotted to visualize relationships in the data.
- Matplotlib and seaborn were used for visualizations.

---

## 5. Data Encoding

- Categorical variables were encoded into numerical values using LabelEncoder, as well as custom functions.
- Special cases, such as missing values, were handled.

---

## 6. Data Splitting and Scaling

- The data was split into training and testing sets for effective model performance evaluation.
- Features were scaled to standardize the data and improve model convergence during training.

---

## 7. Dimensionality Reduction

- PCA (Principal Component Analysis) was applied to reduce the dimensionality of the data while retaining most of the variance.

---

## 8. Model Training (RandomForest, XGBoost)

- Several machine learning models were trained, including:
  - RandomForestClassifier: Hyperparameters such as the number of estimators and max depth were tuned.
  - XGBClassifier: Hyperparameters such as learning rate, max depth, and subsampling were configured.
- Model evaluation was conducted using accuracy, F1 score, and confusion matrices.

---

## Results

- Both models demonstrated competitive performance, with detailed metrics provided.
- Visualizations of confusion matrices and metrics were generated to understand model effectiveness.

---

This project demonstrates a complete pipeline from data preprocessing to model evaluation for a credit scoring system. The workflow can be further extended or refined for deployment in a real-world environment.

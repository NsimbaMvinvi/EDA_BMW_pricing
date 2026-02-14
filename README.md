# 🚗 BMW Pricing Analysis – Exploratory Data Analysis

## 📌 Project Overview
This project explores a BMW vehicle dataset to understand the key factors influencing car pricing. 

The goal is to identify statistically significant variables that impact price and prepare the dataset for future predictive modeling.

---

## 🎯 Problem Statement

Car pricing depends on multiple technical and market-driven factors. 

This analysis aims to:

- Identify the most influential features affecting vehicle price
- Evaluate statistical relationships between variables
- Detect multicollinearity and outliers
- Prepare the dataset for machine learning applications

---

## 📂 Dataset

- Source: BMW vehicle dataset
- Includes attributes such as:
  - Engine size
  - Horsepower
  - Fuel type
  - Mileage
  - Body style
  - Price (Target Variable)

---

## 🧹 Data Preparation

- Missing value imputation
- Outlier detection using statistical thresholds
- Feature standardization where necessary
- Data type corrections
- Exploratory feature transformation

---

## 📊 Exploratory Analysis

### 1️⃣ Univariate Analysis
- Distribution of price (right-skewed)
- Engine size and horsepower distributions
- Categorical feature frequency analysis

### 2️⃣ Bivariate Analysis
- Correlation matrix
- Strong positive correlation between engine size and price
- Negative relationship between mileage and price

### 3️⃣ Statistical Testing
- ANOVA to evaluate categorical variables impact on price
- Pearson correlation for continuous variables
- Identification of statistically significant predictors (p < 0.05)

---

## 🔍 Key Findings

- Engine size and horsepower are strong predictors of price.
- Mileage significantly reduces vehicle value.
- Certain body styles show statistically significant price differences.
- Some variables show multicollinearity, which should be handled before modeling.

---

## 🤖 Machine Learning Readiness

The dataset is now:

- Cleaned
- Structured
- Statistically evaluated
- Suitable for regression modeling (Linear Regression, Random Forest, XGBoost)

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

---

## 🚀 Future Work

- Build regression models
- Compare model performance
- Feature importance analysis
- Cross-validation

---

## 👤 Author
Nsimba Mvinvi  
Aspiring Data Scientist  
Python | SQL | Statistical Analysis | Machine Learning

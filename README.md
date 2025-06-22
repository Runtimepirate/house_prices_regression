# 🏡 House Prices - Advanced Regression Techniques

Predict the final sale prices for homes in **Ames, Iowa** using advanced regression techniques, feature engineering, and model ensembling.  
This project is based on the Kaggle competition: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

---

## 📌 Project Overview

This project demonstrates:

- ✅ Data preprocessing and cleaning  
- 📊 Exploratory Data Analysis (EDA)  
- 🛠️ Feature engineering  
- 🤖 Model building with **Random Forest** and **XGBoost**  
- 🔁 Ensembling and submission generation  

---

## 📂 Dataset

The dataset includes the following files:

- `train.csv` — Training data with features and target variable (`SalePrice`)  
- `test.csv` — Test data to generate predictions  
- `sample_submission.csv` — Submission format for Kaggle  
- `data_description.txt` — Detailed explanation of each feature  

📄 See `data_description.txt` for comprehensive descriptions of all features.

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.7 or higher  
- Jupyter Notebook or Google Colab  
- Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

## 📁 Files to Include
Before running the notebook, ensure that the following files are present in your working directory:

- ✅ train.csv
- ✅ test.csv
- ✅ sample_submission.csv
- ✅ data_description.txt
- ✅ house_prices_regression.ipynb

You can download these from the Kaggle competition page.

## 📒 Running the Notebook
- 1.Open house_prices_regression.ipynb in Jupyter Notebook or Google Colab.
- 2.Run all cells in order to:

-- 📥 Load and preprocess the data
-- 🔍 Perform EDA and feature engineering
-- 🤖 Train Random Forest and XGBoost regression models
-- 📈 Generate predictions on the test data
-- 💾 Create submission.csv in the required Kaggle format

##🌟 Feature Highlights
- Data Cleaning: Handles missing values and encodes categorical variables
- Feature Engineering: Adds new features like TotalSF (total square footage)
- Modeling: Implements regression using Random Forest and XGBoost
- Ensembling: Averages outputs from multiple models for improved accuracy
- Submission: Exports predictions in Kaggle submission format

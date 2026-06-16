# 🏠 House Price Prediction - Machine Learning Project

## 📌 Project Overview

This project predicts house prices using various machine learning techniques. The dataset contains multiple numerical and categorical features describing residential houses. The goal is to build a regression model that accurately predicts the sale price based on these features.

---

## 🎯 Objective

- Analyze housing data and understand key price-driving factors  
- Perform data cleaning and handle missing values  
- Apply feature engineering and encoding techniques  
- Build and compare regression models  
- Evaluate performance using R² score  

---

## 📊 Dataset Description

The dataset includes features such as:

- Overall Quality of house  
- Living area size  
- Garage details  
- Basement information  
- Neighborhood  
- Building type and other structural attributes  

Target Variable:
- **SalePrice**

---

## 🧹 Data Preprocessing

- Handled missing values based on feature meaning:
  - Structural missing values (e.g., no garage, no fireplace) filled with `"None"`
  - Numerical missing values filled using median imputation
- Converted categorical features into numerical form:
  - Ordinal Encoding for ordered features
  - One-Hot Encoding for nominal features
- Applied ColumnTransformer for structured preprocessing pipeline

---

## 📈 Exploratory Data Analysis (EDA)

Key insights observed:

- Overall Quality strongly correlates with Sale Price  
- Larger living area increases house price  
- Garage capacity positively impacts price  
- Several outliers exist in high-value houses  

---

## 🤖 Model Building

Two regression models were trained:

### 1. Linear Regression
- Baseline model
- Captures linear relationships

### 2. Random Forest Regressor
- Ensemble model
- Captures non-linear patterns

---

## 📊 Model Performance

| Model                | R² Score |
|---------------------|----------|
| Linear Regression   | ~0.87    |
| Random Forest       | ~0.89    |

Random Forest performed slightly better due to its ability to capture complex relationships.

---

## 🧠 Key Learnings

- Importance of proper missing value handling  
- Impact of feature engineering on model performance  
- Difference between ordinal and nominal encoding  
- How pipelines make ML workflows clean and production-ready  
- Even simple models can perform well with good data  

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🚀 Future Improvements

- Hyperparameter tuning (GridSearchCV)  
- Try advanced models like XGBoost or Gradient Boosting  
- Feature selection and outlier treatment  
- Log transformation of target variable  

---

## 📌 Conclusion

This project demonstrates a complete machine learning workflow from data preprocessing to model evaluation. It highlights how strong feature engineering can significantly improve model performance even with simple algorithms.

---

## 👤 Author

**Isha Kalra**  
BCA Student | Aspiring AI Engineer 

---

## ⭐ If you like this project

Give it a star ⭐ and feel free to fork it!

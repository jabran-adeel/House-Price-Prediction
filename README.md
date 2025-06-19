# Task: House Price Prediction 🏠

## 🔍 Objective:
Predict housing prices using features like area, garage, number of rooms, and construction year.

## 📊 Dataset:
- Source: [Kaggle - House Prices Advanced Regression](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
- File used: `train.csv`

## 📦 Features Used:
- OverallQual, GrLivArea, GarageCars, GarageArea, TotalBsmtSF, 1stFlrSF, FullBath, TotRmsAbvGrd, YearBuilt, Fireplaces

## 🧠 Techniques Applied:
- Feature Selection based on correlation
- Missing value handling
- StandardScaler
- Linear Regression
- Gradient Boosting Regressor
- Model Evaluation (MAE, RMSE)
- Feature Importance Plot

## 📈 Results:
- **Linear Regression**  
  MAE: _[24774.22]_  
  RMSE: _[39474.54]_

- **Gradient Boosting Regressor**  
  MAE: _[47222.59]_  
  RMSE: _[72520.47]_

## 📁 Files:
- `House_Price_Prediction.ipynb`: Full code notebook
- `README.md`: This summary

## ✅ Tools:
Python, Pandas, Scikit-learn, Seaborn, Matplotlib

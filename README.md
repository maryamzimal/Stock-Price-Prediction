#  Apple Stock Price Prediction – ML Project 📊

Predicting **Apple’s next-day closing stock price** using historical data and **Linear Regression**.  
Demonstrates data cleaning, feature engineering, and regression-based forecasting.

---

## 🔍 Overview
- Loaded and cleaned `Apple Dataset.csv`  
- Removed `Adj Close`, converted `Date` to datetime, and sorted chronologically  
- Created lag features: `Prev_Open`, `Prev_High`, `Prev_Low`, `Prev_Close`, `Prev_Volume`  
- Dropped missing values after shifting  

---

## 🤖 Model & Evaluation
- Split data (**80/20**, no shuffle)  
- Trained **Linear Regression** using scikit-learn  
- Evaluated with: **R²**, **MAE**, **RMSE**  
- Visualized **actual vs predicted** closing prices  

---

## 🧰 Tech Stack
- **Python**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  
- **Scikit-learn**  
- **VS Code / Jupyter Notebook**

---

## 📈 Key Learnings
- Time-series data preparation for ML  
- Lag-based feature engineering  
- Regression model evaluation (R², MAE, RMSE)  
- Visualizing actual vs predicted prices  

---

## 🚀 Future Work
- Add **feature scaling** or **polynomial regression**  
- Try **Random Forest**, **XGBoost**, or **LSTM**  
- Build an **interactive dashboard** for stock trend visualization  

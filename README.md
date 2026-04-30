# CREDIT_CARD_SCORE_PROJECT
# Credit Card Score Prediction 💳

Yeh ek Machine Learning project hai jo user ke financial aur demographic data ke aadhar par unka **Credit Score** predict karta hai. Is project mein Regression techniques ka upyog karke score ki satikta (accuracy) par dhyan diya gaya hai.

## 📌 Project Overview
Is model ka uddeshya financial institutions ki madad karna hai taaki wo customers ke creditworthiness ka andaza laga sakein. Isme Data Preprocessing se lekar Hyperparameter Tuning tak ka pura workflow shamil hai.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / VS Code

## 🚀 Key Features
- **Data Cleaning:** Missing values aur outliers ko handle kiya gaya hai.
- **Feature Engineering:** `One-Hot Encoding` aur `Label Encoding` ka upyog karke categorical data ko process kiya gaya hai[cite: 2].
- **Model Selection:** `RandomForestRegressor` ka upyog kiya gaya hai jo complex patterns ko samajhne mein mahir hai[cite: 2].
- **Optimization:** `RandomizedSearchCV` ke dwara model ke hyperparameters ko tune kiya gaya hai[cite: 2].

## 📊 Model Performance
Model ne testing data par behtareen pradarshan kiya hai:
- **R2 Score:** ~0.83[cite: 2]
- **Error Metric:** Mean Squared Error (MSE) aur RMSE ko minimize kiya gaya hai[cite: 2].

## 📂 Project Structure
```text
├── data/                   # Dataset files (Excel/CSV)
├── Credit_Card_Model.ipynb # Main Jupyter Notebook[cite: 2]
├── requirements.txt        # Required Python libraries
└── README.md               # Project documentation

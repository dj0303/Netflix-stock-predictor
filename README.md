# Netflix-stock-predictor
A machine learning model that predicts stock closing prices using linear regression. Achieves 99% accuracy (R² ≈ 0.998) based on historical features like Open, High, Low, Volume, and Date. Includes trained model saved with joblib.

# Stock Price Predictor

This project uses a **Linear Regression** model to predict stock closing prices based on historical data such as Open, High, Low, Volume, and Date (split into Year, Month, Day). It’s a clean, well-structured machine learning workflow implemented in Jupyter Notebook and trained using `scikit-learn`.

---

## Overview

- **Goal**: Predict the closing stock price given various input features.
- **Model**: Linear Regression
- **Accuracy**: R² score of ~0.998 on the test set
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `joblib`, `matplotlib`, `seaborn`
- **Deployment**: Not deployed – includes saved model (`.joblib`) and a sample prediction in the notebook.

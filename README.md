# Used Car Price Prediction Applet

An end-to-end data science project built to predict used car prices. This project covers data cleaning, visualization, and baseline machine learning modeling.

## The Dataset & Goal
* **Source:** Dataset sourced from Kaggle (included as `used_cars.csv`).
* **Objective:** Build a predictive model and an interactive applet allowing users to input car features and receive an instant price estimation.

##  Modeling & Results
* **Approach:** Started with a baseline **Linear Regression** model using Python in Google Colab.
* **Performance:** The baseline model achieved an **$R^2$ score of 0.76** (explaining 76% of price variance) with a **Root Mean Squared Error (RMSE) of ~$10,000**.

##  Future Improvements
To improve accuracy and reduce the $10,000 margin of error, next steps include:
1. Feature engineering on car conditions and locations.
2. Training more robust models, such as **Random Forest Regressor** and **Gradient Boosting (XGBoost)**.

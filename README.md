# Machine Learning Mini Projects 🤖

Three beginner-friendly ML notebooks covering classification and regression, built in Google Colab with `pandas`, `scikit-learn`, and `matplotlib`.

## Projects

| Project                  | Type           | Models Used                          |
| ------------------------ | -------------- | ------------------------------------ |
| Heart Disease Prediction | Classification | Logistic Regression, Decision Tree   |
| House Price Prediction   | Regression     | Linear Regression, Gradient Boosting |
| Stock Price Prediction   | Regression     | Linear Regression, Random Forest     |

## Heart Disease Prediction ❤️

Predicts whether a patient is at risk of heart disease using clinical data (age, blood pressure, cholesterol, etc.) from the UCI Heart Disease (Cleveland) dataset.

### Features

* Exploratory Data Analysis (EDA) with correlation heatmap
* Logistic Regression vs Decision Tree comparison
* Accuracy, confusion matrix, and classification report

## House Price Prediction 🏠

Predicts house prices from property features such as size, bedrooms, bathrooms, and location.

### Features

* EDA and feature relationships
* Linear Regression vs Gradient Boosting comparison
* Evaluated using RMSE, MAE, and R²

## Stock Price Prediction 📈

Predicts a stock's next-day closing price using historical OHLCV data fetched live via the `yfinance` API.

### Features

* Time-series-aware (chronological) train/test split
* Linear Regression vs Random Forest comparison
* Benchmarked against a naive baseline
* Actual vs Predicted price plots

## Tech Stack 🛠️

* Python
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* yfinance

## How to Run ▶️

1. Open any notebook in Google Colab.
2. Run all cells from top to bottom (**Runtime → Run all**).
3. No setup needed — each notebook installs its own dependencies.

## Project Structure 📁

```text
.
├── Heart_Disease_Prediction.ipynb
├── House_Price_Prediction.ipynb
├── stock_price_prediction.ipynb
└── README.md
```

## Contributing ⭐

If you find these useful, feel free to star the repository!


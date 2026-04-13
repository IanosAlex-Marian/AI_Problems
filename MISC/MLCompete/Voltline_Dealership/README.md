# Voltline Dealership

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on predicting car prices for a dealership using various features of the vehicles. It involves:
1. **Exploratory Data Analysis:** Analyzing the dataset to identify common engine types and calculating average prices based on fuel types.
2. **Regression Modeling:** Using the `CatBoostRegressor` to predict vehicle prices, applying log transformation to the target variable (`price`) to improve model performance.
3. **Data Preprocessing:** Handling categorical features and numerical data, and splitting the dataset into training and evaluation sets.
4. **Automated Submission:** Generating a `submission.csv` file that consolidates results from analysis and the regression model's predictions.

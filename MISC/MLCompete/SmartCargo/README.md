
# SmartCargo

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on predicting delivery times for a logistics company based on various factors like cities, weather, and distance. It involves:
1. **Data Preprocessing:** Cleaning the dataset by removing identifiers like `ID` and preparing the target variable using a log transformation (`log1p`) to handle skewness.
2. **Regression Modeling:** Using the `CatBoostRegressor` to predict `deliver_time`, taking advantage of its built-in support for categorical features such as `City A`, `City B`, and `Weather`.
3. **Hyperparameter Tuning:** Configuring the model with optimal parameters like `iterations`, `learning_rate`, and `depth`, along with `early_stopping_rounds` to prevent overfitting.
4. **Automated Submission:** Generating a `submission.csv` file that includes predictions for multiple subtasks as required by the competition.

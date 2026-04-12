# AutoValue Predicting Car Prices

This project is part of the [NitroAI](https://judge.nitro-ai.org/competitions?page=1) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The solution employs a CatBoostRegressor to predict car prices, leveraging its native support for categorical feature encoding. The target price variable was log-transformed to stabilize variance and improve model convergence, with missing values handled through median imputation for numerical data. This robust gradient boosting approach ensures high predictive accuracy across diverse vehicle specifications.

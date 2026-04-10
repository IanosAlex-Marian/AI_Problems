# The City Problem

This project is part of the [NitroAI](https://judge.nitro-ai.org/competitions?page=1) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

## Documentation

This solution utilizes an ensemble of XGBoost and Random Forest regression models to predict prices based on urban data features. Both models were trained on log-transformed target values to handle non-linear relationships and then averaged to produce the final result. This hybrid approach combines the strengths of gradient boosting and bagging to enhance the stability and accuracy of the predictions.

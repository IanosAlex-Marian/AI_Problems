# Credit Card Fraud Detection

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

## Documentation

The project identifies fraudulent credit card transactions in a highly imbalanced dataset. It employs a multi-step analysis:
1. **Statistical Comparison:** Comparing fraudulent transaction amounts against the average of legitimate ones.
2. **Anomaly Detection:** Using Mahalanobis distance to identify multivariate outliers within fraudulent data points.
3. **Classification:** Training machine learning models to differentiate between fraud and legitimate transactions, focusing on metrics that handle class imbalance effectively.

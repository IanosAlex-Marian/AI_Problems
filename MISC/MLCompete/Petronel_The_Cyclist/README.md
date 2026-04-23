# Petronel The Cyclist

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on analyzing cycling activities and predicting their types based on distance and time. It involves:
1. **Exploratory Data Analysis:** Calculating and analyzing average cycling speeds for each month of the year to identify seasonal patterns.
2. **Activity Classification:** Using the `CatBoostClassifier` to predict activity categories (e.g., COMMUTE, LEISURELY_COMMUTE, PURE_LEISURE) with techniques like balanced class weights and early stopping to prevent overfitting.
3. **Automated Submission:** Generating a `submission.csv` file that consolidates results from both the monthly speed analysis and the activity classification tasks.


# Churn In Telecommunications Services

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project aims to predict customer churn in the telecommunications sector and perform specific data analysis tasks. It involves:
1. **Rule-Based Analysis:** Implementing logic to identify customers with high monthly charges and extra data usage (Subtask 1), as well as those experiencing poor connection quality (Subtask 2).
2. **Binary Classification:** Using the `CatBoostClassifier` to predict whether a customer will churn. The model handles categorical features, implements early stopping, and uses balanced class weights to address potential dataset imbalances.
3. **Data Preprocessing:** Handling missing values in categorical columns by converting them to strings and filling them with a "missing" placeholder to ensure compatibility with the CatBoost algorithm.
4. **Automated Submission:** Consolidating results from the analysis and the machine learning model into a single `submission.csv` file for evaluation.

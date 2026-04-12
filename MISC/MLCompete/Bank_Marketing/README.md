
# Bank Marketing

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on predicting whether clients will subscribe to a term deposit based on marketing campaign data. It involves:
1. **Exploratory Data Analysis:** Analyzing deposit rates across different job categories and identifying common contact patterns (e.g., most frequent month for telephone contacts).
2. **Binary Classification:** Using the `CatBoostClassifier` to predict bank deposit subscriptions, with techniques like early stopping, balanced class weights, and categorical feature handling.
3. **Customer Clustering:** Applying the `KMeans` clustering algorithm to group clients based on their numerical features after standardizing them.
4. **Automated Submission:** Generating a `submission.csv` file that consolidates results from analysis, classification, and clustering tasks.

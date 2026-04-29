# Automated Loan Evaluation

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on automated loan evaluation through various analytical and predictive tasks. It involves:
1. **Age Categorization:** Categorizing clients into 'Young' (< 30), 'Adult' (30-59), and 'Senior' (60+) based on their age.
2. **Risk Categorization:** Assessing financial risk levels ('LowRisk', 'MediumRisk', 'HighRisk') based on the debt-to-income ratio.
3. **Total Debt Assessment:** Calculating a comprehensive debt metric by summing current debt, derogatory marks, and recent delinquencies.
4. **Loan Status Prediction:** Implementing a `CatBoostClassifier` with balanced class weights to predict the probability of loan status, handling categorical features like occupation and loan intent.
5. **Multi-Task Submission:** Consolidating results from categorization, calculation, and classification into a unified `submission.csv`.

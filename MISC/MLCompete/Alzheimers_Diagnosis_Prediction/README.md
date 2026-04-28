# Alzheimer's Diagnosis Prediction

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on predicting Alzheimer's Disease diagnosis based on various patient metrics and medical history. It involves three main subtasks:
1. **Demographic Analysis:** Analyzing the patient database to identify and count individuals within specific age groups.
2. **Behavioral Risk Assessment:** Calculating the percentage of smokers within different age categories to understand lifestyle-related risk factors.
3. **Binary Classification:** Implementing a `CatBoostClassifier` to predict the likelihood of an Alzheimer's diagnosis. The model utilizes balanced class weights, early stopping, and hyperparameter tuning to achieve optimal performance on medical data.
4. **Automated Submission:** Generating a unified `submission.csv` that integrates results from data analysis, risk assessment, and predictive modeling.

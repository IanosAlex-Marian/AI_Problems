
# Fairplay

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 93.97%**

## Documentation

The project focuses on predicting match chaos labels based on football match statistics and team styles. It involves:
1. **Data Preprocessing:** Cleaning the dataset by removing unique identifiers like `MatchID` and preparing features for the model.
2. **Feature Engineering:** Handling categorical features such as `HomeTeam`, `AwayTeam`, `FullTimeResult`, and multi-label strings like `TeamStyles`.
3. **Classification:** Using the `CatBoostClassifier` to predict the `chaos_label`, leveraging its ability to handle categorical variables and provide robust performance.
4. **Automated Submission:** Generating a `submission.csv` file with the predicted labels for the competition evaluation.

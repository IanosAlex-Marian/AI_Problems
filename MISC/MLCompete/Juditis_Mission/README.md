# Juditis Mission

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 96.69%**

## Documentation

The project focuses on analyzing and predicting superhero attributes based on their powerstats and profiles. It involves:
1. **Data Exploration:** Identifying the number of unique publishers and the publisher with the most 'good' aligned superheroes.
2. **Regression Task:** Predicting the `combat` powerstat using an ensemble of `XGBRegressor` and `CatBoostRegressor`, with categorical feature handling and early stopping.
3. **Binary Classification:** Determining if a superhero has `Super Strength` using a `CatBoostClassifier` with overfit detection.
4. **Automated Submission:** Consolidating the results from all subtasks into a final `submission.csv` file.

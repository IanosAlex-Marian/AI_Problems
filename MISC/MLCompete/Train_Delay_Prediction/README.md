# Train Delay Prediction

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on predicting train delays in minutes based on various features. It involves:
1. **Data Preprocessing:** Cleaning the dataset by removing unnecessary identifiers like `SampleID` and preparing the features for regression.
2. **Feature Engineering:** Log-transforming the target variable (`delay_minutes`) using `np.log1p` to handle skewness and improve model performance.
3. **Regression Model:** Utilizing the `CatBoostRegressor` to predict train delays, leveraging its native support for categorical features and robust handling of non-linear relationships.
4. **Model Optimization:** Configuring iterations, learning rate, and early stopping to ensure optimal convergence and prevent overfitting.
5. **Prediction and Submission:** Reversing the log-transformation on predictions using `np.expm1` and generating the final `submission.csv` file.

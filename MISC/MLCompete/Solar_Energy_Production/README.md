# Solar Energy Production

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on predicting solar energy production based on environmental and temporal features. It involves:
1. **Data Preprocessing:** Cleaning the dataset and preparing features for regression analysis.
2. **Target Transformation:** Applying a log-transformation (`np.log1p`) to the `energy_output` to stabilize variance and improve model training performance.
3. **Regression Modeling:** Implementing a `CatBoostRegressor` to capture non-linear relationships between environmental factors and solar output.
4. **Model Optimization:** Using early stopping and standard hyperparameters to ensure efficient convergence and robust predictions.
5. **Final Prediction:** Reversing the log-transformation (`np.expm1`) on model outputs to generate the final `submission.csv` with energy production estimates.

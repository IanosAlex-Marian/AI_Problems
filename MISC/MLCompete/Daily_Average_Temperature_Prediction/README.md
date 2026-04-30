
# Daily Average Temperature Prediction

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on predicting the daily average temperature based on historical weather data. It involves:
1. **Data Preprocessing:** Cleaning the dataset by dropping unnecessary columns like `SampleID` to focus on relevant features.
2. **Target Transformation:** Applying a logarithmic transformation (`log1p`) to the target variable, adjusted by its minimum value, to stabilize variance and normalize the distribution for better model performance.
3. **Regression Modeling:** Utilizing the `CatBoostRegressor` with optimized hyperparameters (depth=6, iterations=3000, learning_rate=0.03) and `RMSE` as the loss function.
4. **Model Training:** Implementing early stopping to prevent overfitting and ensure the model generalizes well to unseen data.

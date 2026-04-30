
# Wine Type Classification

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on classifying wine types based on their chemical properties. It involves:
1. **Data Preprocessing:** Cleaning the dataset by dropping the `SampleID` column to focus on chemical features.
2. **Multi-class Classification:** Utilizing the `CatBoostClassifier` to predict wine categories.
3. **Imbalanced Data Handling:** Applying `auto_class_weights='Balanced'` within the CatBoost model to ensure all wine types are accurately represented during training.
4. **Model Optimization:** Using optimized hyperparameters (depth=6, iterations=3000, learning_rate=0.03) and implementing early stopping to achieve high precision and recall across all classes.

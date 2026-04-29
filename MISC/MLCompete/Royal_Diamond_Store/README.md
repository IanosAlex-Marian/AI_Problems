# Royal Diamond Store

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on diamond valuation and categorization through several analytical and predictive tasks. It involves:
1. **Weight Categorization:** Categorizing diamonds into 'Light' (< 0.5 carat), 'Medium' (0.5-1.49 carat), and 'Heavy' (≥ 1.5 carat) based on their weight.
2. **Geometric Analysis:** Calculating the depth-to-table ratio for each diamond to understand its structural proportions.
3. **Volume Calculation:** Computing the physical volume of diamonds using their dimensional measurements (x, y, z).
4. **Price Prediction:** Implementing a `CatBoostRegressor` to predict diamond prices. The model uses log-transformed targets (`np.log1p`) and handles categorical features like cut, color, and clarity.
5. **Multi-Task Submission:** Consolidating weight categories, geometric ratios, volumes, and predicted prices into a single `submission.csv`.

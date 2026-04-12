# Galactic Wars Winner Prediction

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on predicting the outcome of galactic battles between different factions. It involves:
1. **Data Preprocessing:** Cleaning and converting specialized data formats (e.g., removing unit characters from armor values) into numerical features suitable for machine learning.
2. **Exploratory Analysis:** Answering specific tactical questions through data filtering and aggregation.
3. **Unsupervised Learning:** Applying `KMeans` clustering to identify patterns and group similar battle scenarios based on unit characteristics.
4. **Supervised Learning:** Training a `CatBoostClassifier` to predict battle winners, utilizing its native support for categorical features and optimized gradient boosting.


# Annual Income Prediction

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project aims to predict annual income levels and analyze demographic patterns. It involves:
1. **Exploratory Data Analysis:** Identifying demographic trends, such as the native country with the second highest number of high-income individuals and the occupation with the highest average income.
2. **Binary Classification:** Training a `CatBoostClassifier` to predict whether an individual's income exceeds $50,000 based on various features, utilizing categorical feature handling and overfitting detection.
3. **Text Clustering:** Using `TfidfVectorizer` and the `HDBSCAN` algorithm to cluster individuals based on their profile descriptions.
4. **Automated Submission:** Generating a comprehensive `submission.csv` file that aggregates findings from the analysis, classification, and clustering tasks.

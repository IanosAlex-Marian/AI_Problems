# Classification Of Iris Flower Species

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on classifying iris flowers into three species based on their morphological measurements. It involves:
1. **Data Preprocessing:** Cleaning the dataset by removing irrelevant columns like `SampleID`.
2. **Dimensionality Reduction:** Applying Principal Component Analysis (PCA) to reduce the feature space to two dimensions for visualization.
3. **Clustering/Classification:** Using the `GaussianMixture` model with three components to group the iris samples into their respective species.
4. **Automated Submission:** Generating a `submission.csv` file containing the predicted labels for the test dataset.

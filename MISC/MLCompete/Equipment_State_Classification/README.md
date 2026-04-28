# Equipment State Classification

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project aims to classify the state of various equipment based on sensor data or technical specifications. The approach includes:
1. **Dimensionality Reduction:** Using Principal Component Analysis (PCA) to reduce the feature space to two dimensions for visual exploration of the data clusters.
2. **Unsupervised Learning:** Applying the `KMeans` clustering algorithm with 4 clusters to identify distinct equipment states. The model is configured with multiple initializations (`n_init=100`) and a high number of iterations to ensure convergence.
3. **Automated Submission:** Predicting the state labels for the test dataset and generating a `submission.csv` file for evaluation.

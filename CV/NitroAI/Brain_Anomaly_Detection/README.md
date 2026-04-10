# Brain Anomaly Detection

This project is part of the [NitroAI](https://judge.nitro-ai.org/competitions?page=1) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

## Documentation

The solution involves preprocessing brain scan pixel data and reducing its dimensionality using Principal Component Analysis (PCA) with 200 components. A Linear Support Vector Classification (LinearSVC) model was then trained on these features, utilizing balanced class weights to handle dataset imbalances. This combination provides a computationally efficient yet effective method for anomaly detection.

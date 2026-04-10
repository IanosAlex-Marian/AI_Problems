# Abnormal Cardiac Signal Detection

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

## Documentation

The problem was solved using a pre-trained EfficientNet-B0 model from PyTorch for binary classification. Images were resized to 224x224 and normalized before being fed into the network. The model was trained using the AdamW optimizer over five epochs to achieve high accuracy.

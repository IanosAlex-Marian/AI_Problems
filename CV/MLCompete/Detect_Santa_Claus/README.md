# Detect Santa Claus

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The solution utilizes a pre-trained EfficientNet-B1 model from PyTorch for binary classification. Extensive data augmentation, including color jittering and flips, was applied to the training set to improve model robustness. The network was trained for 20 epochs using the AdamW optimizer to accurately distinguish between Santa Claus and other images.

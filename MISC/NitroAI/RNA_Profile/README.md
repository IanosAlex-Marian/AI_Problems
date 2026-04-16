# RNA Profile

This project is part of the [NitroAI](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on predicting RNA profiles from nucleotide sequences. It involves:
1. **Data Preprocessing:** Converting RNA sequences (A, U, C, G) into numerical representations and padding them for batch processing.
2. **Deep Learning Model:** Implementing a Bidirectional LSTM (Long Short-Term Memory) network with embedding layers to capture sequential dependencies in RNA data.
3. **Training Pipeline:** Using PyTorch with the `AdamW` optimizer and `MSELoss` to train the model, specifically masking padded values during loss calculation to ensure accuracy.
4. **Sequence Prediction:** Generating continuous profile values for each position in the test RNA sequences and formatting them for submission.

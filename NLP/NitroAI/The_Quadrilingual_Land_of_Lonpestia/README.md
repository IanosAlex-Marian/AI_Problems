# The Quadrilingual Land of Lonpestia

This project is part of the [NitroAI](https://judge.nitro-ai.org/competitions?page=1) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

## Documentation

The problem was solved by using character-level Tfidf Vectorization to capture the unique orthographic patterns of four unknown languages. These features were then clustered using the KMeans algorithm, allowing for both language identification and the comparison of text pairs to determine if they belong to the same linguistic group. This unsupervised approach successfully differentiates between languages without requiring pre-labeled training data.

# Sad Squidward

This project is part of the [NitroAI](https://judge.nitro-ai.org/competitions?page=1) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

## Documentation

This solution treats musical sequences as text by representing pitch differences and durations as "words" in a musical sentence. A TfidfVectorizer was used to extract features from these sequences across multiple n-gram ranges, which were then classified using a Logistic Regression model. This approach effectively captures the stylistic signatures of different composers through their melodic and rhythmic patterns.

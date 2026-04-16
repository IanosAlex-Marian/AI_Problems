# What Does The Fox Say

This project is part of the [NitroAI](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 98%**

## Documentation

The project focuses on natural language processing through unsupervised word embedding training and supervised classification. It involves:
1. **Vocabulary Analysis:** Computing the total unique vocabulary size from a large unlabeled corpus to understand the lexical diversity.
2. **Word Embeddings:** Training a `Word2Vec` model on unlabeled data to capture semantic relationships between words in a 32-dimensional vector space.
3. **Sentence Vectorization:** Generating fixed-length sentence representations by averaging the vectors of constituent words and applying L2 normalization.
4. **Supervised Classification:** Implementing a `LogisticRegressionCV` model with cross-validation to classify text samples based on the learned embeddings.

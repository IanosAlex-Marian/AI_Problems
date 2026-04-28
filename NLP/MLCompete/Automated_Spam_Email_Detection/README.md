# Automated Spam Email Detection

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on detecting spam emails using text analysis and machine learning. It involves three main subtasks:
1. **Text Length Analysis:** Calculating the character length of each email in the test set.
2. **Keyword Frequency:** Using regular expressions to count the occurrences of the word "free" (case-insensitive) within each email body.
3. **Spam Classification:** Implementing a `LinearSVC` (Support Vector Classifier) model paired with `CountVectorizer` for feature extraction to classify emails as spam or ham.
4. **Automated Submission:** Generating a unified `submission.csv` that combines text length, keyword frequency, and classification predictions.

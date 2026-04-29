# Text Classification Into Thematic Categories

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on classifying news headlines and short descriptions into thematic categories (e.g., POLITICS, WELLNESS, ENTERTAINMENT). It involves:
1. **Text Vectorization:** Utilizing `TfidfVectorizer` to convert raw text into numerical features, capturing both unigrams and bigrams.
2. **Feature Engineering:** Implementing stop-word removal and frequency-based filtering (`min_df`, `max_df`) to refine the feature set.
3. **Classification Pipeline:** Building a scikit-learn `Pipeline` that integrates TF-IDF vectorization with a `LogisticRegression` classifier.
4. **Handling Class Imbalance:** Applying balanced class weights within the logistic regression model to ensure fair representation across diverse thematic categories.
5. **Model Evaluation and Submission:** Predicting labels for the test set and generating a `submission.csv` file with the final thematic classifications.

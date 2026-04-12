# The Puzzle Guild Archives

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project involves analyzing puzzle guild data to extract insights and predict styles. It consists of:
1. **Data Filtering:** Performing targeted queries to count entries meeting specific criteria, such as location and technical assistance requirements.
2. **Statistical Analysis:** Calculating aggregate metrics (mean skill level and teamwork scores) for specific puzzle categories like Logic and Sequence in designated locations.
3. **Classification Task:** Implementing a `CatBoostClassifier` to predict the 'style' of puzzle rounds, utilizing automated class balancing and categorical feature processing.
4. **Automated Submission:** Consolidating results from data analysis and machine learning predictions into a final `submission.csv` file.

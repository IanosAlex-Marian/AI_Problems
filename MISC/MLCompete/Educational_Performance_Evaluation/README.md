
# Educational Performance Evaluation

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project focuses on evaluating educational performance using school-level data. It involves:
1. **Data Analysis:** Performing specific queries on the dataset, such as counting schools of a certain type in specific counties.
2. **Multiclass Classification:** Using the `CatBoostClassifier` to predict the `Relative Performance Rating` of schools. The model handles categorical features directly and utilizes balanced class weights to address potential dataset imbalances.
3. **Automated Submission:** Consolidating answers from multiple subtasks (analysis and prediction) into a single `submission.csv` file for evaluation.

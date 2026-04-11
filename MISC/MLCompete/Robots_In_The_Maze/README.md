# Robots In The Maze

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

## Documentation

The solution addresses a multi-part challenge involving both statistical analysis and classification of robot behavior in maze environments. The notebook implements five distinct subtasks:

1.  **Arena Analysis**: Calculating the total number of unique arena environments.
2.  **Performance Metrics**: Identifying the peak average speed across all recorded robot runs.
3.  **Environmental Distribution**: Determining the most frequent arena type in the dataset.
4.  **Efficiency Tracking**: Finding the maximum number of items collected in a single run.
5.  **Strategy Classification**: Predicting robot behavior strategies (e.g., 'guardian', 'explorer', 'sprinter') using a **CatBoostClassifier**.

The classification model was trained with balanced class weights and optimized using the TotalF1 metric, achieving a final competition score of **95.95%**.

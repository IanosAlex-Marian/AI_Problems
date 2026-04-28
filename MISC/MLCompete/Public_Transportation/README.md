# Public Transportation

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

The project involves analyzing public transportation GPS data to extract insights and identify key locations. It includes:
1. **Data Statistics:** Calculating basic metrics such as the number of unique vehicles and vehicle types in the dataset.
2. **Geospatial Clustering:** Using the `DBSCAN` algorithm with the Haversine metric to cluster vehicles based on their average geographic coordinates.
3. **Depot Identification:** Analyzing stationary patterns of specific vehicle types during night hours (23:00 - 05:00) and applying `KMeans` clustering to determine the coordinates of main depots or stations.
4. **Automated Submission:** Generating a `submission.csv` file that combines the results from data analysis, vehicle clustering, and depot identification.

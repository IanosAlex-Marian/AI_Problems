# Battlefield Recon

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

## Documentation

The project focuses on spatial analysis of reconnaissance data, representing positions of units in a battlefield. It involves:
1. **Isolation Detection:** Using the `NearestNeighbors` algorithm to calculate an "isolation score" for Team 0 units. Units with an isolation score above a certain threshold (0.017) are flagged.
2. **Spatial Clustering:** Applying the `HDBSCAN` clustering algorithm to group units based on their spatial coordinates.
3. **Automated Submission:** Generating a `submission.csv` file with the final flags and cluster assignments.

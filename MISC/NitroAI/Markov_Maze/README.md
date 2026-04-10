# Markov Maze

This project is part of the [NitroAI](https://judge.nitro-ai.org/competitions?page=1) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

## Documentation

The maze navigation problem was modeled as a Markov Decision Process (MDP) and solved using the Value Iteration algorithm on a 6x6 grid. The solution accounts for stochastic transitions, where actions have an 80% success rate and a 20% chance of drifting sideways. By iteratively updating the value function, the model identifies the optimal policy for reaching the goal cell with maximum expected reward.

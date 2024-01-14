# Random Walks
This is code for simulating and visualizing random walks.

Specifically:

- It imports necessary libraries like numpy, matplotlib, pandas for numerical and visualization operations

- It defines a RandomWalk class to generate random walk data
  - The `__init__` method initializes some attributes like number of points
  - The `fill_walk` method calculates all the random points in the walk
  - The `plot_walk` method plots the walk using matplotlib
  
- It creates an instance of this RandomWalk class

- It generates the random walk by calling `fill_walk`

- It plots the full walk

- It makes some modifications to the display to remove axes, outline etc to clean up the visualization

- It calculates and prints properties like the minimum, maximum distance from home and the final distance from home after the random walk

- It makes multiple random walks, and plots each as a trace on the same set of axes

So in summary, it uses OOP concept to encapsulate generation and plotting of random walks, calculates key statistics on the walks, and generates useful visualizations.

The main purpose is to simulate and visualize random motion using random walk theory and display key properties emerging from such mathematical models.

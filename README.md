# 3D-Bin-packing-problem-using-simulated-annealing

This Python script implements the Simulated Annealing algorithm to solve the 3D bin packing problem.
Given a set of items and a set of bins with fixed dimensions, the goal is to find a packing configuration
that minimizes the wasted space in the bins.

The code consists of several components:

1. Problem Definition:
   - bin_dimensions: Tuple representing the dimensions of the bin (width, height, depth).
   - items: List of tuples representing the dimensions of each item to be packed.

2. Initial Solution Generation:
   - initial_solution(): Function to generate an initial packing configuration of items into bins.

3. Objective Function:
   - wasted_space(bins): Function to calculate the volume of wasted space in the bins.

4. Simulated Annealing Algorithm:
   - simulated_annealing(): Function implementing the simulated annealing algorithm to find the optimal solution.

5. Visualization:
   - visualize_solution(bins): Function to visualize the best solution found by the algorithm.

Main Flow:
- The main block of the script executes the simulated annealing algorithm to find the best solution.
- It then prints the best solution found and visualizes it using a 3D plot.

Usage:
- Run the script to execute the simulated annealing algorithm and visualize the best solution.

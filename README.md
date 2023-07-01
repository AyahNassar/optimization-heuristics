# optimization problem using heuristics 
# Traveling Salesman Problem (TSP)

## Overview
The Traveling Salesman Problem (TSP) is a classic algorithmic problem in the field of computer science and operations research. It focuses on optimization. In this problem, a salesman is given a list of cities, and must determine the shortest possible route that allows him to visit each city once and return to his original location.

## Problem Statement
Formally, the Traveling Salesman Problem can be defined as follows:

Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city exactly once and returns to the origin city?

## Complexity
The TSP is notorious among computational problems for its complexity. It is used as a benchmark for many optimization methods. Even though the problem is computationally difficult (NP-hard), many heuristics and exact algorithms are known so that some instances with tens of thousands of cities can be solved.

## Algorithms
Several algorithms have been proposed to solve TSP. These include:

1. Brute force: This method involves generating all permutations of the cities and calculating the total distance for each permutation. The permutation with the smallest total distance is the solution.

2. Heuristic methods: Various heuristic methods, like the Nearest Neighbor heuristic, or more complex ones like Simulated Annealing, Genetic Algorithms or Ant Colony Optimization, are often used for TSP. 

3. Hill Climbing: A method of solving certain types of optimization problems. The idea is to start with a random solution, make a small change in the solution, and if it improves the solution (i.e., reduces the total distance), to accept the change.


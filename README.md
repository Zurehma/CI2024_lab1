# CI2024_lab1

This repository contains a solution to the Set Cover Problem, solved as Lab 01 for the Computational Intelligence Course.

## Steps followed
- Definition of functions to check validity, cost and fitness of solutions. 
- The fitness function returns the validity of the solution and the negative of the cost. The goal is to maximize the fitness
- For each instance, a random set is generated depending on the universe size and number of sets
- A "dumb" solution using all of the sets gives the "maximum" cost i.e minimal fitness
- An initial solution is generated at random as the starting point.
- A random mutation hill climbing algorithm is used where one bit is randomly mutated (inverted)
- To avoid local minima being reached, a restart threshold value is also set. If after a certain number of steps, the fitness stays constant, a new random solution is generated as a starting point.

## Required libraries
The following libraries must be installed to correctly run the solution
1. numpy
2. icecream
3. matplotlib


# CCPython_Project

Creative Coding: Python
Project Assignment Part 2
11/25/2020

Pseudocode:

The goal of this program is to further develop and revise the Game of Life along with the Genetic Algorithm that I had tried to develop before in order to generate the ideal pattern through times of revolutions. The fitness of the pattern should be best achieved after the practice of the algorithms. 
 
Game of life step using scipy tools:
   From library import selected scipy tool
   Make a move forward according to Game of Life rules
   For x in range
   Return value
 Generating initial population of individual solutions
If random state is defined
Return: initial population as a list of set dimension arrays
Calculate fitness for particular candidate (start configuration of the field)
Define the param start_field (start configuration) and param end_field: (stop configuration) through number of steps to proceed before comparing to stop configuration
Then return: value in range [0, 1] that indicates fractions of cells that match their state
Apply fitness function for each gene in a population
Defining a list of candidate solutions and tried number of steps to revert
Then return: list of scores for each solution
Apply selection operator to the population
First define the variation, number of  population, selection, leftovers and then 
For x in y
If number of random < retained random
Return the selection
Input mutation for the provided field
Define the variation rate and the type of field 
 Return the field 
Take two parents to crossover
 return two children
interchanging half of the alleles of each parent randomly
   Evolution step
In a dimension array that represents field in stopping condition
Solving for delta number of steps to revert
Return: new generation of the same size
     Prepare to draw graphs with matplotlib
Import from library 
Define the figure configuration and color of the patterns to draw
Set x and y ticks and labels for reference purpose
Set minor axes in between the labels 
Return the graph
Prepare to draw graphics in animation format
Run function
Definelife_animation(Xs, dpi=10, frames=10, interval=300, mode='loop',delta=0,gens=[]):
  # Xs: a list of game of life patterns
  Define the figure configuration
Set x and y ticks and labels again
Set minor axes in between the labels to format a grid
Plot the grid 
 Form initialization function: plot the background of each frame
Define the initialization 
Use animation function
Return animation 
Map out the ideal and target Pattern
Layout the pattern first in matrix format
Display the pattern with graph
Define the moves of the pattern
Summarize the result of variation 

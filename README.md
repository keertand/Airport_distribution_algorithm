# Airport_distribution_algorithm
Python - Jupiter Notebooks Interface

/*

Keertan Dakarapu
kxd160830
University of Texas at Dallas

*/

Project Based on: Project concept is based on A-Star Algorithm implementation.

Problem:
Given an undirected weighted graph with weight being the distance factor,
and all the straight-line distances from each node to another are given. 
Find the most efficient number of airports, and their most efficient placement,
given the cost of travel by air, cost of travel by road, and cost of building an airport.

Abstract:
The solution requires us to use A-Star algorithm recursively. We first create our heuristic function, 
based on cost values provided. Then we iterate upon the number of airports to be build starting from 2,
and all the way till n/2, where n is the number of nodes. We calculate and compare the sum of least cost
incurred by all possible paths for travelling, following the most efficient placement of airports in each respective case.
Then we decide upon the no of airports comparing the least cost estimation or each case. Internally,
we should use A-star for determining the shortest path between two nodes, where in we must consider the air routes also.

Inputs: 
airspeed, air cost, road speed, road cost, Graph with connection distances(weights), NxN straight line distance matrix.
Outputs:
No of airports, Airport placements: Array of nodes, where airports are placed.

________________________________________________________________
Runnning the program:

The Graph described in 'graph.jpg' is the base graph used for this implementation.
(The program works irrespective of this, if you change the graph, straightline_distances array values, 
and change the n value for number of nodes.)

the 'Project_spring.ipynb' as a normal python program.
The 'Assignment A-star.ipynb' is the A star Implementation, prior to getting the idea for using it as airport distribution.


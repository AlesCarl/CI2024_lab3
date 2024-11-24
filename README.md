# CI2024-lab3

This project implements  A* Algorithm for solving the Gem Puzzle problem.


### Two primary heuristic approaches:


- **Manhattan Distance** :  This is used to estimate the distance between the current puzzle state and the goal state, summing the number of moves each tile needs to reach its target position.
- **Misplaced Tiles** : This counts the number of tiles not in their goal position, adding additional weight to encourage better intermediate states.

The algorithm dynamically switches between these heuristics when a certain number of iterations are performed without improving the solution. 



### Adaptive Heuristic Switching
To mitigate stagnation in the search, the implementation includes a mechanism to alternate between heuristics after 7000 iterations without improvement.




## RESULTS: 


The table below summarizes the results for different puzzle dimension, derived from a single execution of the algorithm. 

|  **Puzzle dimension**| **Quality**|**Cost** | 
|---|---|---|
| 3 |   20 | 600| 
| 4 | 62 | 123098 | 
| 5 | 130 | 633136 | 
|||





The execution time for a puzzle of dimension 3 is negligible. For a dimension of 4, the execution time ranges between 5 and 12 seconds. 
For a dimension of 5, the execution time is highly variable, can range from a few minutes to several hours.






The exercise was carried out in collaboration with Lorenzo di Rosa  (329169).




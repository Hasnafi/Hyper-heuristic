# Architecture of the Hyper-Heuristic
### Higher Level: ACO
Ants choose heuristics based on pheromones and visibility.
### Lower Level: Construction Heuristics
Three heuristics: Partial Nearest Neighbor, Partial Random Insertion, Partial Farthest City Insertion.
#### Pheromone update based on solution improvements.
<img src="https://github.com/user-attachments/assets/2356a201-48be-449e-8000-113eb493b1d5" >


# Pseudo Code
### Initialization:
##### Ants are distributed randomly.
##### Each ant has a list that will contain the sequence of heuristics.
##### Pheromones for each heuristic are initialized to a positive non-zero constant.

### Local Pheromone Update:
##### After each heuristic selection by an ant, pheromone levels are updated locally to promote diversity.

### Global Pheromone Update:
##### After each iteration, pheromone evaporation occurs.
##### The best solutions add pheromones to reinforce effective heuristics.

### Stopping Condition:
##### Maximum number of iterations reached.

<img src = "https://github.com/user-attachments/assets/f7d41071-ecf5-4ed3-98b5-da79e1b96954" >

# sir-model-net-logo
This NetLogo model simulates the propagation of an infectious disease among a population of agents.

### Requirements
NetLogo version 5.1 and up

### Variables
Several variables can be adjusted to simulate different types of disease and the way the agents are impacted.

num-turtles : The amount of turtles on the grid

init-infected : The number of initially sick individuals 

transmissibility : Contagiousness of the virus, how likely is an infected or sick agent to spread the disease to his nearest neighbors

speed : Agents travel speed on the grid, affects how fast sick agents spread the disease around

recovery-rate : Probability of recovery


### Monitoring the spread
Monitors were implemented to analyse the spread of the disease among the population.

- prop-infected : Proportion of infected agents among the total count of agents 

- prop-uninfected : Proportion of healthy agents among the total count of agents 

- num-deaths : The amount of dead agents

- prop-deaths : Proportion of dead agents among the total count of infected agents

- total-infected : The total of agents who got infected

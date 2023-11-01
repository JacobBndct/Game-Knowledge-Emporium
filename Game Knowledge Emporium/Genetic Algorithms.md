__________________________________________________________________________
#### **Tags:** #Programming/AI 
###### *Date Of Creation: 2023-10-31*
__________________________________________________________________________

Genetic algorithms usually take two parents individuals and they recombine their genetic material to produce a child that inherits genetic material from both parents.

If the child performs well on the evaluation test (evaluating an individual and measuring how well an individual performs is commonly done by the use of a fitness function), it will also be selected for reproduction and in this way the genetic material can again be propagated to new generations. Since the individuals themselves will usually die (they are often replaced by individuals of the next generation). In reference to this the [[Selfish Gene Hypothesis]] was proposed.

A genetic algorithm in pseudo-code may look like:

1. Initialize a population of N individuals
2. Repeat:
	1. Evaluate all individuals in the population using the fitness function.
	2. Repeat N times:
		1. Select two individuals for reproduction according to their fitness values
		2. Recombine these two parent individuals to one offspring.
		3. Mutate the offspring
		4. Inset the offspring in a new population
	3. Replace the population by the new population

Both the population itself and each N individual have a state. After each generation the population makes a transition to a new state.

After sufficiently long the population may contain the optimal solution. Since the optimal solution may get lost, the nest solution found so far is always stored.
## Representation


#### Sources
__________________________________________________________________________
1. 
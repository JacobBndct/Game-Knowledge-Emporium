__________________________________________________________________________
#### **Tags:** #Programming/AI 
###### *Date Of Creation: 2023-11-06*
__________________________________________________________________________

## Think and act separately, in parallel!

- Deliberative control is smart but slow
- Reactive control is fast but inflexible
- Hybrid control combines both reactive and deliberative control in one robot control system
- Need for effective solutions for different
	- Time-scales
	- Representations
- A **hybrid control system** consists of three components, called layers or modules (different from layers in reactive system)
	- Reactive layer
	- Planning layer
	- Middle layer (i.e. a layer to link them)
- Designing the middles layer that controls what type of control to use is hard!
	- Changes in
		- world
		- map
		- task
	- When the reactive layer detects a change, the planning layer should update the representation
	- New plans can be created in the future
	- The robot has to visit a specific room multiple times, should it replan the path every time?
	- A popular solution is to store computed plans
		- Can be used for fast lookup in the future
		- Ideal for frequently occurring situations and/or which require fast decision
#### Sources
__________________________________________________________________________
1. 
Neural networks make use of supervised learning

Forward propagation
- Calculate the activation values for nodes in the first layer
	- Apply the activation function
	- Calculate the activation values for the next layer
- And so on until the network output is correct

Back propagation
- 
#### Example: ALVINN

ALVINN is a robot with a Neural NEtwork
- Objective : autonomous lane following
- Input image of the road ahead
- Output: steering direction

Step by step
- Record human driving angles and camera view
- ALVINN shows how it would steer, given an image
- The human steering angle is presented
- ALVINN computes the difference (output error)
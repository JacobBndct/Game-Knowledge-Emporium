__________________________________________________________________________
#### **Tags:** #Programming/AI
###### *Date Of Creation: 2023-09-24*
__________________________________________________________________________

Learning the relation between input-output pairs. Neural networks are a very popular approach use for supervised learning.

Forward propagation
- Calculate the activation values for nodes in the first layer
	- Apply the activation function
	- Calculate the activation values for the next layer
- And so on until the network output is correct

Back propagation
- Look back at the notes lmao
#### Example: Alvinn

ALVINN is a robot with a Neural NEtwork
- Objective : autonomous lane following
- Input image of the road ahead
- Output: steering direction

Step by step
- Record human driving angles and camera view
- ALVINN shows how it would steer, given an image
- The human steering angle is presented
- ALVINN computes the difference (output error)

#### Sources
__________________________________________________________________________
1. [mataric-primer.pdf (ucsd.edu)](https://pages.ucsd.edu/~ehutchins/cogs8/mataric-primer.pdf)

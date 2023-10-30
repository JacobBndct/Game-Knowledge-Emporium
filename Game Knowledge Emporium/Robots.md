__________________________________________________________________________
#### **Tags:** #Programming/AI
###### *Date Of Creation: 2023-10-06*
__________________________________________________________________________

"A robot is an *[[Autonomous Systems]]* which exists in the *physical* world, can *sense* it's environment, and can *act* on it to achieve some *goals*."

5 Different components that make something a robot are:
- Autonomous
- Physical
- Sense
- Act
- Goal
## Autonomy
Machines that are not autonomous, but are instead externally controlled by humans are called [[Teleoperated]].
## Embodiment 
To exist in the physical world, is to be embodied.
- Capable of maintaining itself in the outside world. 
- Adapting and reacting differently to changing environment which can include learning mechanisms.
## Sensing and Perception
To be situated in the physical world, is to be able to exist in and sense the world.
- Foregoes the necessity of acting.
- Must sense the environment with its own sensors.
- All possible combination of sensory readings that the robot is capable of with all its different sensors is called the sensor space.
- Sensing allows the robot to know it's own internal state and the environment's external state.
	- The state of a robot is not always known and can be observable, partially observable, or hidden.
	- States here are similar to how they are in [[State Machine Pattern]].
## Acting
A robot must be able to act in the physical environment based on the information it senses. This is done with physical components such as motors which are referred to as "actuator".
- Actuators are used for two things
	1. *Locomotion*: moving around, going places
	2. *Manipulation*: handling objects
- Cannot act randomly, uselessly, or without consideration for the environment.
## Goals
A robot must also act with purpose towards a goal or do something useful to itself and/or others.

#### Sources
__________________________________________________________________________
1. [mataric-primer.pdf (ucsd.edu)](https://pages.ucsd.edu/~ehutchins/cogs8/mataric-primer.pdf)
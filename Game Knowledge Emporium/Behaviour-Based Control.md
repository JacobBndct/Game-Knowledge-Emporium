__________________________________________________________________________
#### **Tags:** #Programming/AI 
###### *Date Of Creation: 2023-11-06*
__________________________________________________________________________
In general, Behaviour-Based Controls are networks of internal behaviours that interact (send messages to each other) in order to produce the desired external, obserable, manifested behaviour.

By having behaviours interact with each other, they can be used to store a representation.
## Think the way you act!!
- Biologically inspired
- Grew out of reactive control
- Deliberative systems are too slow
- Reactive systems are too inflexible and incapable of using internal representations, adaptation, or learning
- Hybrid systems require complex interaction among components
- Biology seem to have evolved complexity from simple and consistent components
- Tries to use the best aspects of reactive control, without using a hybrid solution
- It involves the use of behaviors as modules of control
- A Behaviour based controls (BBC) system is implemented as a collection of behaviours
## Behaviours
- more complex than actions
- achieve and/or maintain a goal
	- find-object, follow-target, get-recharged, find-human, ... 
- are not instantaneous, they take time.
- take inputs from sensors and from other behaviours
- send output to effectors and other behaviours
- Behaviours are typically executed in parallel as in a reactive system
- Networks of behaviours are used to store states and to create representations
- Behabiours in one subsystem should operate with similar timescales.
	- Otherwise a hybrid solution is needed
#### Sources
__________________________________________________________________________
1. 
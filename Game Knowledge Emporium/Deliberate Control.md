__________________________________________________________________________
#### **Tags:** #Programming/AI 
###### *Date Of Creation: 2023-11-06*
__________________________________________________________________________

This solution for control is useful when there is a clear goal to reach and all possible "paths" to reach the goal are searchable.

Deliberative control has three main steps performed in sequence;
- Sense,
- Plan,
- Act

**Deliberation**
- Thinking hard
- Thoughtfulness in decision and action

**Deliberative control grew out of early classical AI**
- Playing chess
- Consider possible outcomes
- Without strategy, things go wrong
- Planning is the solution!
## Planning
Planning is the process of  
- Looking ahead at the outcomes of possible actions
- Searching for the sequence of actions that will reach the desired goal
## Drawbacks
- Time scale
	- many sensors combined with a large internal representation models result in a large state space
	- This slows down the search during planning
	- It is also much harder if states are partially observable (e.g., location not completely known)
	- In some cases, it might be better to
		- plan rarely and
		- act as much as possible
- Memory space
	- The robot's representation must contain all information needed for localizing the robot and planning (distances, images, etc)
	- This uses a lot memory!
	- Memory is cheap and there less a problem than time, but memory is finite and running out of it causes problems.
- Information
	- The planner assumes that the used representation is accurate and up-to-date
	- Therefore, the representation must be updated and checked as often as necessary to keep it accurate for the task
- Deliberate control is only useful if
	- The environment is completely known and does not change during the execution of the plan
	- The robot knows what the state of the world is and what the state of the plan is at all times
	- The robot's effectors are accurate enough to execute each step of the plan
		- otherwise, more complex planning algorithms must be used (e.g., Partially Observable Markov Decision Processes - POMDPs)
#### Sources
__________________________________________________________________________
1. 
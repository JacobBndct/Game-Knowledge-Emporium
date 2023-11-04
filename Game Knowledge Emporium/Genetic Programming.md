__________________________________________________________________________
#### **Tags:** #Programming/AI 
###### *Date Of Creation: 2023-11-04*
__________________________________________________________________________

Genetic Programming is a form of evolutionary computation in which the individuals in the evolving population are full **computer programs** rather than binary strings!

- It is an extension of [[Genetic Algorithms]]
- Has demonstrated to produce intriguing results:
	1. Design of electronic filter circuits
	2. Classification of segments of protein molecules

To do this we represent computer programs via a [[Tree]]:
- Each function call is represented by a node in the tree
- The arguments of the function are given by the descendant nodes

In Genetic Programming: 
1. We use the same genetic operators that define Genetic Algorithms
2. However, we need to define the set of primitive functions e.g. $+, \sqrt, sin \dots$ which is not trivial
3. A solution is represented by an entire program tree, which can make their evaluation expressive

## Pros
Among the main benefits we have that:
- The underlying concept is easy to understand
- Can be used for multi-objective optimization
- Support distributed learning
- Same cooking recipe can be used across large variety of tasks
- Work well when the problem is not differentiable
## Cons
Among such limitations we have:
- No convergence guarantees in finite time
- Computing the evaluation function $f(x)$ can be expensive
- Lots of implementation parameters need to be defined
- Termination Criteria?
#### Sources
__________________________________________________________________________
1. 
__________________________________________________________________________
#### **Tags:** #Programming/AI 
###### *Date Of Creation: 2023-11-06*
__________________________________________________________________________

The design of subsumption controllers is called **bottom-up** design. 

Higher layers can use lower layers to achieve their goal by using them while running or by inhibiting them selectively.
- Input of lower layers may be suppressed
- Output of lower layer may be inhibited

![[Subsumption arch picture.png]]

![[Interaction of Layers.png]]

## Advantages
- Very popular due to its simplicity and robustness
- Designing and debugging the system incrementally from bottom-up
- When a higher level layer fails, lower level layers will still continue to work well
- The only connections between layers are those used for inhibition and suppression

Note that best known architecture for [[Reactive Control]] and [[Behaviour-Based Control]] is subsumption architecture.
#### Sources
__________________________________________________________________________
1. 
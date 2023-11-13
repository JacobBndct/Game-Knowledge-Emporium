__________________________________________________________________________
#### **Tags:** #Math/Analysis 
###### *Date Of Creation: 2023-11-13*
__________________________________________________________________________

It is important to note that the NIP requires the intervals to be closed!

**Theorem:**
$$[a_1, b_1] \supseteq [a_2,b_2] \supseteq [a_3,b_3] \supseteq \dots \Rightarrow \bigcap_{n=1}^\infty [a_n, b_n] \not = \emptyset$$
**Proof**: we have to show that $$\exists x \in \Bbb R \;\;\; \text{such that} \;\;\; x \in [a_n, b_n] \;\;\forall n \in \Bbb N$$
define $A = \{a_n : n \in \Bbb N\}$
Every $b_n$ is an upper bound for $A$
[[Axiom of Completeness|AoC]] $\Rightarrow x:= supA$ exists
$A_n \le x \;\;\; \forall n \in \Bbb N$ (since x = upper bound for $A$)
$x \le b_x \;\;\; \forall n \in \Bbb N$ (since x = least upper bound for $A$) 
$x \in [a_n, b_n] \;\;\; \forall n \in \Bbb N$

#### Sources
__________________________________________________________________________
1. 
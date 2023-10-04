__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma 
###### *Date of Creation: 2023-10-04*
__________________________________________________________________________

*We say a partition $P$ of a set $X$ is a set of disjoint subsets of $X$ whose union is $X$.*
0. *If $R$ is an equivalence relation on $X$ then $X \setminus R$ is a partition of $X$.* 
1. *Conversely, if $P$ is a partition of $X$ then we get an equivalence relation on $X$* $$R = {(x, y) ∈ X^2 : \text{there is a } p ∈ P \text{ such that } {x, y} ⊆ p}$$
*Proof:* First if $z \in \bar x \cap \bar y$ then $z \sim x$ and $z \sim y$ so by symmetry and transitivity $x \sim y$ but that means $\bar x = \bar y$. This means that two equivalence classes are either equal or disjoint. Second the union of all equivalence classes is all of X because X = S x∈X x¯. We conclude that X/R is a partition of X. 

For the second part of the theorem we need to verify that the proposed equivalence relation is indeed an equivalence relation in the sense of Definition 3.8. Reflexivity follows because P is a partition, meaning for every x there is some p ∈ P such that x ∈ p so {x, x} ⊆ p. Symmetry is also clear because if {x, y} ⊆ p for some p ∈ P then surely also {y, x} ⊆ p. Finally for transitivity assume that there are p, q ∈ P and {x, y} ⊆ p while {y, z} ⊆ q for some x, y, z ∈ X. Then y ∈ p ∩ q so p = q because unequal sets in P must be disjoint. Therefore {x, z} ⊆ p. $\star$
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
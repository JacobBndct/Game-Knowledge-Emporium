__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma  
###### *Date of Creation: 2023-10-04*
__________________________________________________________________________

*If $A$ and $B$ and $Y$ are sets then*
0. $(A \cup B) \times Y = (A \times Y) \cup (B \times Y)$
1. $(A \cap B) \times Y = (A \times Y) \cap (B \times Y)$
2. $(A \setminus B) \times Y = (A \times Y) \setminus (B \times Y)$

*Proof:* We prove part 0 using the [[double inclusion is equality|double inclusion lemma]]. Suppose $(x,y) \in (A \cup B) \times Y$ then $x \in A \cup B$ and $y \in Y$. There are two possibilities: either $x \in A$ in which case $(x,y) \in A \times Y$ or $x \in B$ in which case $(x,y) \in B \times Y$. This shows that $x \in (A \times Y) \cup (B \times Y)$. Conversely, suppose $s \in (A \times Y) \cup (B \times Y)$ then there are two possibilities: either $s \in A \times Y$ or $s \in B \times Y$. In the first case we have $s = (x,y)
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
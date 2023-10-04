__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma 
###### *Date of Creation: 2023-10-04*
__________________________________________________________________________

*If the disjoint sets $A$ and $B$ are finite then so is $A \cup B$ and* $$\#(A \cup B) = \# A + \# B$$
*Proof:* Set $\# A = m$ and $\# B = n$ so there are invertible functions $\alpha : A \rightarrow [m]$ and $\beta : B \rightarrow [n]$. We will construct an invertible function $f: A \cup B \rightarrow [m + n]$ because this would prove that $\#(A \cup B) = m + n$. Define $$f(x) = \begin{cases} \alpha (x) & \text{if $x \in A$} \\ m + \beta (x) & \text{if $x \in B$} \end{cases}$$
This formula makes sense because all the $x$ in the domain are always in either $A$ or $B$ but *never in both*. Also the output is in the proposed codomain because it is a natural number less than $m$ in case $x \in A$ and if $x \in B$ then $\beta (x) \lt n$   
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
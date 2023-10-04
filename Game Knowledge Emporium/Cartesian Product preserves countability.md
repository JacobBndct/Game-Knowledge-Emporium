__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma 
###### *Date of Creation: 2023-10-04*
__________________________________________________________________________

0. $\Bbb N^2$ is countably infinite.
1. if $X$ and $Y$ are countably infinite then so is $X \times Y$.

The idea of the proof of the first part is shown in Figure 3.3. We propose to order the pairs of natural numbers $(m,n)$ according to their sum $m+n$ and order the pairs with equal sum by their first entry. Enumerating in this order gives$$(0, 0),(1, 0),(0, 1),(2, 0),(1, 1),(0, 2),(3, 0),(2, 1),(1, 2),(0, 3),(4, 0),(3, 1),\dots$$
More geometrically we visualize $\Bbb N \times \Bbb N$ as an infinite array the lower corner of which is shown in Figure 3.3 in black. Above each pair we placed a red number indicating when that pair is counted. Notice we slice the array along the diagonals that run from lower right to upper left.

To give some more detail we start by describing the picture in formulas.

The [[triangular number lemma]] is almost equivalent to part 0. All we need to do is reformulate it a bit in terms of invertible functions.

*Proof:* If we introduce the set $J = \{(x,y) \in \Bbb N^2 : x \ge y\}$, shown in Figure 3.4 then the Triangular number lemma proves that 

***Figure 3.3***
![[Enumerating N x N.png]]
***Figure 3.4***
![[Figure 3.4.png]]
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
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

*Proof:* If we introduce the set $J = \{(x,y) \in \Bbb N^2 : x \ge y\}$, shown in Figure 3.4 then the Triangular number lemma proves that $T: J \rightarrow \Bbb N$ is an invertible function with inverse $F : \Bbb N \rightarrow J$ given by $F(n) = (k,l)$ where the $k,l$ depend on $n$ and are given by the lemma.

To finish the proof of part 0 of the theorem we remark that the function $R: \Bbb N^2 \rightarrow J$ given by $R(x,y) = (x + y,y)$ is invertible with inverse $S: J \rightarrow \Bbb N^2$ given by $S(x,y) = (x-y,y)$. Then $T \circ R : \Bbb N^2 \rightarrow \Bbb N$ is the required invertible function showing that $\Bbb N^2$ is countable.

To prove part 1, assume there are invertible $a : X \rightarrow \Bbb N$ and $b : Y \rightarrow \Bbb N$. Then $c : X \times Y \rightarrow \Bbb N \times \Bbb N$ defined by $c(x,y) = (a(x),b(y))$ is also invertible with inverse $c^{-1}(m,n) =  (a^{-1}(m),b^{-1}(n))$. From part 0 we found an invertible function $f : \Bbb N^2 \rightarrow \Bbb N$ so the composition $f \circ c$ is the soug

***Figure 3.3***
![[Enumerating N x N.png]]
***Figure 3.4***
![[Figure 3.4.png]]
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
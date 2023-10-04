__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma 
###### *Date of Creation: 2023-10-04*
__________________________________________________________________________

*Any $n \in \Bbb N$ can be written as $n = \frac{k(k+1)}{2} + l$* for precisely one pair of numbers $k$, $l \in \Bbb N$ satisfying $l \le k$. 

*Proof:* For convenience we use the notation $T(k,l) = \frac{k(k+1)}{2} + l$.

We start by proving directly that if a number $n$ can be written as $T(k,l)$ then the pair $k \ge l$ is unique. Suppose $n = T(k,l) = T(k^ \prime, l^ \prime)$ for some $k,l,k^\prime,l^\prime \in \Bbb N$ satisfying $l \le k$ and $l^\prime \le k^\prime$. Suppose $k^\prime \gt k$, then $$0 = T(k,l) - T(k^\prime,l^\prime) \gt \frac{(k+2)(k+1)}{2} - \frac{k(k+1)}{2} - l = k +1 - l \gt 0$$
yields a contradiction since $l \le k$. Likewise $k^\prime \lt k$ is impossible (check this yourself!) so we must have $k = k^\prime$
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
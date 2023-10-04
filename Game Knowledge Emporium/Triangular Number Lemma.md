__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma 
###### *Date of Creation: 2023-10-04*
__________________________________________________________________________

*Any $n \in \Bbb N$ can be written as $n = \frac{k(k+1)}{2} + l$* for precisely one pair of numbers $k$, $l \in \Bbb N$ satisfying $l \le k$. 

*Proof:* For convenience we use the notation $T(k,l) = \frac{k(k+1)}{2} + l$.

We start by proving directly that if a number $n$ can be written as $T(k,l)$ then the pair $k \ge l$ is unique. Suppose $n = T(k,l) = T(k^ \prime, l^ \prime)$ for some $k,l,k^\prime,l^\prime \in \Bbb N$ satisfying $l \le k$ and $l^\prime \le k^\prime$. Suppose $k^\prime \gt k$, then $$0 = T(k,l) - T(k^\prime,l^\prime) \gt \frac{(k+2)(k+1)}{2} - \frac{k(k+1)}{2} - l = k +1 - l \gt 0$$
yields a contradiction since $l \le k$. Likewise $k^\prime \lt k$ is impossible (check this yourself!) so we must have $k = k^\prime$. In case $k = k^\prime$ we find $0 = T(k,l) - T(k,l^\prime) = l - l^\prime$ implying $l = l^\prime$ as required.

To finish the argument we use induction to prove the following statements $S_n$. Denote by $S_n$ the statement that $n$ can be written as $n = T(k,l)$ for some $k \ge l \in \Bbb N$. First $S_0$ holds with $k = l =0$. Assuming $S_n$ holds we will prove $S_{n+1}$. using $S_n$ we can assume that there are $k ge l$ such that $n = T(k,l)$ and that means that $n + 1 = T(k,l+1)$. There are two possibilities: either $l + 1 \le k$ so that $n + 1 =T(l + 1, k)$ works. The other possibility is that $l = k$ in which case we can rewrite $n+1 = \frac{k(k+1)}{2} - \frac{2(k+1)}{2} = \frac{(k+2)(k+1)}{2} = T(k + 1, 0)$. In both cases we proved $S_{n+1}$ follows from $S_n$ finishing the proof. $\star$
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma 
###### *Date of Creation: 2023-10-04*
__________________________________________________________________________

*Any subset of a finite set  is finite*.

*Proof:* Before attempting to prove the general case of a finite set we will assume that our finite set is one of the standard ones $[n]$. In this case it is more transparent to do induction so for any $n \in \Bbb N$ we introduce the following statement $S_n:$ $$\text{Any subset of } [n] \text{is finite} \;\;\;\;\;\;\;\;\; (S_n)$$
To proceed by induction we first need to demonstrate $S_0$ is true and second prove that $S_n$ implies $S_{n + 1}$.

First $[0] = \emptyset$ and the only subset of the empty set is $\emptyset$, which finite. Therefore $S_0$ holds.

Next assume that $S_n$ holds and suppose $B \subseteq [n + 1]$. If $B = [n+1]$ then $B$ is finite. If $n \notin B$ then $B \subseteq [n]$ so $S_n$ implies $B$ is finite. The only other option is that $n \in B$ and there is some $k \in [n] \setminus B$. Define the function $f: [n + 1] \rightarrow [n + 1]$ by $f(k) = n, f(n) = k$ and $f(x) = x$ for all other $x \in [n + 1]$. The function $f$ is its own inverse and $n \notin f(B) \text{ so } f(B) \subseteq [n]$. By $S_n$ the set $f(B)$ must be finite. Since $f$ is invertible $B$ must also be finite. 

Finally we return to the statement of the lemma that we aim to prove. If $X$ is a finite set then there must be some $n \in  \Bbb N$ and an invertible function $\alpha : X \rightarrow [n]$. Consider a subset $A \subseteq X$. By the above statement $S_n$ we just proved, we know tha t $\alpha (A) \subseteq [n]$ must be finite. Therefore $A$ is finite too because $\alpha$ gives us an invertible function $A \rightarrow \alpha (A)$. $\star$
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
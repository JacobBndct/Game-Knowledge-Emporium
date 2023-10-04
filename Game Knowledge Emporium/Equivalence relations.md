__________________________________________________________________________
#### **Tags:** #Math/SetTheory 
###### *Date of Creation: 2023-09-24*
__________________________________________________________________________

An equivalence relation $R$ on a set $X$ is a subset relation $R$ is a subset of $X \times X$ with the following properties. 

Using notation $(x, y) \in R$ will be written $x \sim y$
#### Properties
0. *For all $x \in X$ we have $x \sim x$. (Reflexivity)*
1. *For all $x,y \in X$ we have if $x \sim y$ then $y \sim x$. (Symmetry)*
2. *For all $x,y,z \in X$ we have if $x \sim y$ and $y \sim z$ then $x \sim z$. (Transitivity)*

Here is a simple example of an equivalence relation called $R$ on $X = [4]:$ $$R = {(0, 0),(1, 1),(2, 2),(3, 3),(1, 2),(2, 1),(3, 1),(1, 3),(2, 3),(3, 2)} (3.1)$$ We can verify that $R$ is indeed an equivalence relation by checking the three properties of reflexivity, symmetry and transitivity mentioned in the definition. First reflexivity holds because for each $x ∈ [4]$ we see $R$ contains $(x, x)$. Symmetry holds as well as we can see by going over each case $(a, b) ∈ R$ with $a \not = b$ such as $(1, 2)$ and checking that $(b, a)$ is also in $R$. Finally transitivity should also be checked by going over each pair of pairs $(a, b)$ and $(b, c)$ in $R$ and checking whether or not $(a, c)$ is in $R$. In this case we can see that it holds.
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
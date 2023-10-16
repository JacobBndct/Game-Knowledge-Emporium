__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma
###### *Date Of Creation: 2023-10-04*
__________________________________________________________________________

*If $Y$ is a set with more than one element then there does not exist a surjective function $f: X \rightarrow Y^X$. Hence $X$ and $X^Y$ do not have the same cardinality.*

*Proof:* Given a function $f : X → Y^X$ define a new function $C : X → Y$ as follows. For every $x ∈ X$ choose $C(x)$ to be any element of $Y$ that is not equal to $(f(x))(x)$. This is possible since $Y$ has at least two elements. If $f$ was surjective then there must be some $z ∈ X$ such that $C = f(z)$. This is impossible since by construction $C(z) \not = (f(z))(z)$. $\star$
#### Sources
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
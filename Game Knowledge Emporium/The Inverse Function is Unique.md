__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma 
###### *Date of Creation: 2023-10-03*
__________________________________________________________________________

*If $h: Y \rightarrow X$ and $k: Y \rightarrow X$ are both inverses of the function $f: X \rightarrow Y$ then $h = k$.*

*Proof:* We compute as follows (see below for further explanations): $$h = h \circ id_Y = h \circ (f \circ k) = (h \circ f) \circ k = id_K \circ k = k$$
The first and last equalities follow from the property of the identity function. The second equality follows from $k$ being an inverse of $f$, the third equality is an application of the [[Composition is Associative|associativity of composition]] and the fourth equality is because $h$ is an inverse of $f$.
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma
###### *Date Of Creation: 2023-10-03*
__________________________________________________________________________

*If $f: X \rightarrow Y$ and $g: Y \rightarrow Z$ and $h: Z \rightarrow W$ are functions then.* $$(h \circ g) \circ f = h \circ (g \circ f)$$  
*Proof:* To check equality of functions we need to verify that on every input both the left hand side and the right hand side yield the same output. Take any input $x \in X$ and compute the left hand side: $$((h \circ g) \circ f)(x) = (h \circ g)(f(x)) = h(g(f(x)))$$  
Doing the same for the right hand side we find $$(h \circ (g \circ f))(x) = h((g \circ f)(x)) = h(g(f(x)))$$  
proving that the two are the same. $\star$
#### Sources
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
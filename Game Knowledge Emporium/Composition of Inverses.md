__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma
###### *Date Of Creation: 2023-10-03*
__________________________________________________________________________

*The composition of two [[function inverses|invertible functions]] $f : X \rightarrow Y$ and $g: Y \rightarrow Z$ is invertible and $$(g \circ f)^{-1} = f^{-1} \circ g^{-1}$$*  
*Proof:* We will show that the function $f^{-1} \circ g^{-1}$ satisfies all requirements of being an inverse of the function $g \circ f$:

Using [[Composition is Associative|associativity of the compositions]] we can write: $$(g \circ f) \circ (f^{-1} \circ g^{-1}) = g \circ (f \circ f^{-1}) \circ g^{-1} = g \circ g^{-1} = id_Z$$  
and similarly $$(f^{-1} \circ g^{-1}) \circ (g \circ f) = f^{-1} \circ (g^{-1} \circ g) \circ f = f^{-1} \circ f = id_X$$  
proving that $(f^{-1} \circ g^{-1}) = (g \circ f)^{-1}$ $\star$
#### Sources
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
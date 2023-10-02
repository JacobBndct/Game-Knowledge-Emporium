__________________________________________________________________________
#### **Tags:** #Math/SetTheory 
###### *Date of Creation: 2023-09-24*
__________________________________________________________________________

*Imagine any [[sets]] $X$, $Y$ and $Z$. The following is true:*
0. $\emptyset \subseteq X$
1. if $X \subseteq Y$ and $Y \subseteq Z$ then $X \subseteq Z$

*Proof:* To prove part zero it suffices to demonstrate that any element of $\emptyset$ is also an element of $X$. We will provide a proof by contradiction: if it were false then there there would be some element $y \in \emptyset$ such that $y \notin X$ which is absurd since $\emptyset$ does not contain any elements.
For the final part we need to show that any element $x \in X$ is also an element of $Z$. By assumption $x \in Y$ because $X \subseteq Y$. Therefore the assumption $Y \subseteq Z$ implies that also $x \in Z$ because $y$ us an element of $Y$. This completes the proof. $$
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
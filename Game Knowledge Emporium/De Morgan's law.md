__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma 
###### *Date of Creation: 2023-10-02*
__________________________________________________________________________

*For any set $X$, $Y$, and $Z$ we have $(X \cup Y) \cap Z = (X \cap Z) \cup (Y \cap Z)$*

*Proof:* For convenience we introduce the temporary notation $L = (X \cup Y) \cap Z$ and $R = $(X \cup Y) \cap Z = (X \cap Z) \cup (Y \cap Z)$. We aim to prove both $L \subseteq R$ and $R \subseteq L$. 

We start by proving $L \subseteq R$. So choose $l \in L$ then we will prove that $l \in R$. By definition of intersection, $l \in X \cup Y$ and $l \in Z$. In case $l \in X$ we find $l \in R$ because it is in both $X$ and $Z$ so $l \in X \cap Z \subseteq R$. The other possibility is that $l \in Y$ in which case $l \in Y \cap Z$ so again $l \in R$.

Finally, the proof of $R \subseteq L$ is similar. This time we start with an $r \in R$ and are presented two options. Either $r
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
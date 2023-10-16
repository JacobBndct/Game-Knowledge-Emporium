__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma
###### *Date Of Creation: 2023-10-02*
__________________________________________________________________________

*For any set $X$, $Y$, and $Z$ we have $(X \cap Y) \cap Z = X \cap (Y \cap Z)$*.

*Proof:* To prove that the two sets $L = (X \cap Y) \cap Z$ and $R = X \cap (Y \cap Z)$ are equal we use the [[Double Inclusion is Equality|double inclusion lemma]]. First we prove that $L \subseteq R$ and second we prove that $L \supseteq R$.

To prove that $L \subseteq R$ we suppose $l \in L$ and argue that $l$ must also be an element of $R$ as follows. Since $l \in L$ we know that $l \in X \cap Y$ and $l \in Z$. From the first statement we conclude that $l \in X$ and $l \in Y$ so that $l$ is an element of both $X$ and $Y$ and $Z$. To show that $l \in R$ we must show that $l \in X$ and $l \in Y \cap Z$. We already know that $l \in X$ and since $l \in Y$ and $l \in Z$ we also have $l \in Y \cap Z$ so we conclude that $l \in X \cap (Y \cap Z) = R$. This concludes the proof that $L \subseteq R$.

The argument to prove that $L \supseteq R$ is very similar but for completeness sake we will give it anyways: Suppose $r \in R$ then $r \in X$ and $r \in (Y \cap Z)$ which means $r \in Y$ and $r \in Z$. To show that $r \in L$ we have to check that $r \in X \cap Y$ and $r \in Z$. Since we found that $r \in X$ and $r \in Y$ we have $r \in X \cap Y$ proving the first assertion. We also know that $r \in Z$ so we conclude that $r \in L$ so that $R \subseteq L$.

Finally, using the double inclusion lemma we conclude from $L \supseteq R$ and $L \subseteq R$ that $L = R$ finishing the proof. $\star$
#### Sources
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
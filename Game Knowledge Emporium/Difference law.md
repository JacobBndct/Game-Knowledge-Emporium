__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma
###### *Date Of Creation: 2023-10-03*
__________________________________________________________________________

*For any sets $X$, $Y$ and $Z$ we have $X \setminus (Y \cup Z) = (X \setminus Y) \cap (X \setminus Z)$*

*Proof:* By the [[Double Inclusion is Equality|double inclusion lemma]] it suffices to prove that $L \subseteq R$ and $L \supseteq R$ where $L = X \setminus (Y \cup Z)$ and $R = (X \setminus Y) \cap (X \setminus Z)$.

To prove the first inclusion assume that $x \in L$. Then $x \in X$ but $x \notin Y \cup Z$. This means that $x$ cannot be an element of $Y$ of $x$ cannot be in $Z$ either because otherwise it would also be in the union $X \cup Y$. We have thus shown that $x \in X \setminus Y$ and also $x \in X \setminus Z$ proving $L \subseteq R$.

To prove the second inclusion we assume that $x \in R$ so $x \in X$ and $x \notin Y$ and $x \notin Z$. This means that $x$ cannot be an element of the union $Y \cup Z$ because if it would then it would have to be an element of at least one of $Y$ and $Z$. In other words $x \in X \setminus (Y \sup Z) = L$ so $L \supseteq R$ finishing the proof. $\star$ 
#### Sources
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
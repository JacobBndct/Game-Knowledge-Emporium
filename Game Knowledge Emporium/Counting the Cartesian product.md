__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma 
###### *Date of Creation: 2023-10-04*
__________________________________________________________________________

*If $X$ and $Y$ are finite sets then $\#(X \times Y) = \# X \# Y$.*

*Proof:* As a preparation we first prove a special case where $\# X = 1$. If the only element of $X$ is called $p$ then the projection then the projection $\pi _2 : X \times Y \rightarrow Y$ is invertible with $\pi _2 ^{-1} (y) = (p,y)$. This shows that $\# (X \times Y) = \# Y$.

Denote by $S_n$ the statement that the theorem is true when $\# X = n$. We will prove $S_n$ by induction. First when $n = 0$ then $X$ must be the empty set and $\emptyset \times Y = \emptyset$ for any set $Y$. Next for the induction step assume that for some $n \in \Bbb N$ the statement $S_n$ is true. We will prove that in the case $S_{n+1}$ is also true. Since $\# X = n + 1 > 0$ we can find some element $x_0 \in X$. Taking it out we are left with $\# \{x_0 \} ^ c = \# (X \setminus \{ x_0 \}) = n +1 -1 = n$ and since $X \times Y = (\{ x_0 \} \times Y) \cup (\{ x_0 \}^ c \times Y)$ and $(\{ x_0 \} \times Y) \cap (\{ x_0 \}^c \times Y) = \emptyset$ we have $$\#(X \times Y) = \#(\{ x_0 \} \times Y) + \#(\{ x_0 \}^c \times Y) = \#Y + n\#Y = (n +1)\#Y = \#X\#Y$$
$\star$ 
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma 
###### *Date of Creation: 2023-10-04*
__________________________________________________________________________

*If $X$ and $Y$ are both finite then $\#(Y^X) = (\#Y)^{\#X}$.*

*Proof:* We will prove the following sequence of statements $S_n$ by induction: If $\#X = n$ then $\#(Y^ X) = (\#Y )^ {\#X}$. The base case $S_0$ follows from $Y^\emptyset = {\emptyset}$ because $(\#Y )^ 0 = \#{ \emptyset } = 1$. Assuming $S_n$ is true we will prove $S_{n+1}$ holds as follows. Choose a particular element $p ∈ X$ and call its complement $X^\prime = X \setminus \{p\}$. 

We claim there is an invertible function $\beta : Y^ X → Y \times Y^{X\prime}$ is invertible. If that were the case then we are done because by the induction hypothesis $S_n$ and the cardinality of the Cartesian product (Lemma ??) $$\#(Y^X) = (\#Y )\#(Y^{X\prime} ) = (\#Y )\#(Y^ n ) = (\#Y )^ {n+1} = (\#Y )^ {\#X}$$
To finish the proof we introduce the function $\beta$ by $\beta(f) = (f(p), g_f )$, where $g_f : X^\prime → Y$ is defined by $g_f (u) = f(u)$ is just the restriction of f to $X^\prime$ . 

To show $\beta$ is invertible we check it is both injective and surjective: $\beta$ is injective because if $\beta(f) = \beta(h$) then $(f(p), g_f ) = (h(p), g_h)$ means $f(p) = h(p)$ and moreover for all $u ∈ X^\prime f(u) = h(u)$ so in conclusion $h = f$. 

To show $\beta$ is surjective take $(r, h) ∈ Y \times Y^ {X^\prime}$ and notice that $\beta(f) = (r, h)$ where $f : X → Y$ is defined by $f(p) = r$ and $f(u) = h(u)$ for all $u ∈ X^\prime$ .
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
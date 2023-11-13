__________________________________________________________________________
#### **Tags:** #Math/Lemma
###### *Date Of Creation: 2023-11-13*
__________________________________________________________________________

if $s$ is an upper bound for $A$ then$
$$s = sup(A) \iff \forall \;\epsilon \gt 0 \;\;\; \exists \; a \in A \;\;\; s.t. \;\;\; s - \epsilon < a$$
**Proof ($\Rightarrow$):** let $\epsilon \gt 0$  be arbitrary
$$\begin{align} s - \epsilon \lt s \Rightarrow s - \epsilon \text{ is not an upper bound for } A \\  \Rightarrow \exists a \in A \;\;\; s.t. \;\;\; s - \epsilon \lt a \end{align}$$
**Proof ($\Leftarrow$):** let $b$ be any upper bound for $A$
- if $b \lt s$ then for $\epsilon = s - b$ there exists $a \in A$ such that $$b =s - \epsilon \lt a$$
- so $b$ is not an upper bound: contradiction!
- hence $s \le b$, which implies that $s = sup(A)$
#### Sources
__________________________________________________________________________
1. [Analysis (rug.nl)](https://brightspace.rug.nl/content/enforced/243292-WBMA012-05.2023-2024.1/pdfs/Analysis-2324-lecture01.pdf)
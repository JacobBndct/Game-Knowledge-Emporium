__________________________________________________________________________
#### **Tags:** #Math/SetTheory 
###### *Date of Creation: 2023-09-24*
__________________________________________________________________________

*A **function** $f$ from [[Sets|set]] $X$ to set $Y$ is a rule that assigns to each [[Elements|element]] of $X$ precisely one element of $Y$. Notation: $f:X \rightarrow Y$*

*Two functions $f : X \rightarrow Y$ and $g : A \rightarrow B$ are equal iff $X = A$ and $Y = B$ and for every $x \in X$, $f(x) = g(x)$.*

**Identity function:** Maps a set to itself, for example the identity function of $A$ is $id_A : A \rightarrow A$ given by $id_X(x) = x$ for  all $x \in X$.

**Constant function:** Whenever we have sets $X$ and $Y$ and some fixed $z \in Y$ we define the constant function $C_z : X \rightarrow Y$ by $C_z (x) = z$ for all $x \in X$.

**Indicator functions:** for any subset $A \subseteq X$ of a set define a function where if x is contained by A it returns a 1 or a 0 if it is not contained. Example $\Bbb I_A:X \rightarrow [2]$ by $$\Bbb I_A(x) = \begin{cases}1 & \text{if $x \in A$} \\ 0 & \text{if $x \notin A$} \end{cases}$$
The special case where $A$ contains one element is often called the **[[Kronecker delta function]]** with the alternative notation: $\delta _ i = \Bbb I_{\{i\}}$ and sometimes $\delta _ i (j)$ is abbreviated as $\delta _{ij}$.

A [[Function Inverses|function is invertible]] if there exists a function $g : Y \rightarrow X$ such that their [[Composition of Functions|composition]] $g \circ f = id_X$ and $f \circ g = id_Y$

When you see a function $f: X \rightarrow Y$ you should always be careful to check that it is *well-defined*, by which we mean that the following three things are true:
0. $f(x)$ is defined for *every* possible input $x$ in the domain $X$.
1. For each $x\in X$ there is no ambiguity in obtaining $f(x)$ from $x$.
2. For each $x\in X$ the value $f(x)$ belongs to the codomain $Y$.

Remark that $sin^{-1}$ is not a function on the reals and neither is $\sqrt x$

#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
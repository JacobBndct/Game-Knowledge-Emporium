__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/SetTheory 
###### *Date of Creation: 2023-10-04*
__________________________________________________________________________

0. *The composition of two injective functions is injective*. 
1. *The composition of two surjective functions is surjective.*

*Proof:* Suppose we have functions $f : X → Y$ and g : $Y → Z$. 

For part 0) we assume both $f$ and $g$ are injective and try to prove that $h = g \circ f$ is also injective. To prove this, suppose that there are $x_1, x_2 ∈ X$ such that $h(x_1) = h(x_2)$. Set $y_1 = f(x_1)$ and $y_2 = f(x_2)$. Then $h(x_1) = g(y_1$) and $h(x_2) = g(y_2)$. Since $g$ is injective and $g(y_1) = g(y_2)$ we have $y_1 = y_2$. Recalling that $y_1 = f(x_1)$ and $y_2 = f(x_2)$ we can use the injectivity of $f$ to conclude that $x_1 = x_2$. This proves that $h = g \circ f$ is injective. 

For part 1) we assume that both $g$ and $f$ are surjective and prove that $h = g \circ f$ is also surjective. To this end take some $z ∈ Z$. Then there exists a $y ∈ Y$ such that $g(y) = z$ because $g$ is surjective. Since $f$ is also surjective there is also an $x ∈ X$ such that $f(x) = y$. Putting these together we find that $h(x) = z$ because $h(x) = (g \circ f)(x) = g(f(x)) = g(y) = z$. This concludes the proof that h is surjective. $\star$
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
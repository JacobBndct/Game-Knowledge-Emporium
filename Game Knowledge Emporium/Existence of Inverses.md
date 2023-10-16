__________________________________________________________________________
#### **Tags:** #Math/SetTheory #Math/Lemma
###### *Date Of Creation: 2023-10-04*
__________________________________________________________________________

*The function $f: X \rightarrow Y$ is invertible if and only if $f$ is a bijection*

*Proof:* We need to prove two things: First, if $f$ has an inverse then $f$ is a bijection and second if $f$ is a bijection then $f$ has an inverse. 

First assume there exists an inverse $f^{−1}$ . So $f^{−1} \circ f = id_X$ and $f \circ f^{−1} = id_Y$. Bijective means both surjective and injective. $f$ is surjective because for any $y ∈ Y$ we have $f(f^{−1}(y)) = y$ so $f(X) = Y$ . To show $f$ is injective, suppose $f(x_1) = f(x_2)$ for some $x_1, x_2 ∈ X$. Apply $f^{−1}$ to both sides of this equation to find $f^{−1} (f(x_1)) = f^{−1} (f(x_2))$ which implies $x_1 = x_2$. This concludes the proof that if $f$ has an inverse then $f$ is a bijection. 

Now assume $f$ is a bijection. We will show that there exists an inverse $g : Y → X$. Take any $y ∈ Y$ . Since $f$ is surjective there exists at least one $x ∈ X$ such that $f(x) = y$. In fact, since $f$ is injective there exists precisely one $x$ such that $f(x) = y$. We can therefore define $g(y) = x$. In other words, $g(y) = x$ where $x$ is the unique $x ∈ X$ satisfying $f(x) = y$. 

It remains to check that $f \circ g = id_Y$ and $g \circ f = id_X$ with the above definition of $g$. Take $y ∈ Y$ and $x$ the unique $x ∈ X$ such that $f(x) = y$. By definition of $g$ we have $(f \circ g)(y) = f(g(y)) = f(x) = y$. This proves $f \circ g = id_Y$ . Likewise $(g \circ f)(x) = g(f(x)) = g(y) = x$ showing $g \circ f = id_X$. This completes the proof that if f is a bijection then it has an inverse. $\star$
#### Sources
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
__________________________________________________________________________
#### **Tags:** #Math/Numbers 
###### *Date Of Creation: 2023-11-05*
__________________________________________________________________________

*For integers $a,b$ with $(a,b) \not = (0,0)$ the following method computes $gcd(a,b)$:*
- *If one of $a$ or $b$ is zero, $gcd(a,b)$ equals the absolute value of the other one.*
- *If both are nonzero, replace them by their absolute value. Then replace the larger one by its remainder upon division by the smaller one. Repeat this until a situation is reached where one of the numbers equals 0, in which case the gcd equals the nonzero number.*

## Extension
Using what was learned from [[Bézout's identity]] we can extend Euclid's Algorithm.

*For integers$a,b$ with the property $(a,b) \not = (0,0)$ the following method computes $g = gcd(a,b)$ as well as integers $x,y$ satisfying $ax+by=g:$*
- *Interchange $a,b$ if necessary, so that $|b| \le |a|$. *
- *If $b=0$ then $g = |a|$ and $a \; \cdot \; (\pm 1) + b \; \cdot \; 0 = g$ for a suitable choice of $\pm 1$.*
- *If $b \not = 0$ then write $|a| = q|b| + r$ for integers $q,r$ with $0 \le r \le |b| - 1$ and start from equalities $\{ \begin{start}$*
#### Sources
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
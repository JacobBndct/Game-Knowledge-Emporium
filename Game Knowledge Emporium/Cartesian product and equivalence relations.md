**Tags:**  #Math 

Definition: If X and Y are sets then X * Y is the set of all (ordered) pairs (x, y) where x e X, y e Y.  X * Y = {(x, y), x e X, y e Y}

Projection functions: PI: X * Y -> X is defined by PI((x, y)) = x and like wise PI2: X * Y -> Y

Goal: If X and Y are finite then #(X * Y) = (#X)(#Y)

also if X and Y are countably infinite then so is X * Y

### Lemma: 
If A, B, Y are sets then,
0. (A u B) * Y = (A * Y) u (B * Y)
1. Empty set = Empty set * Y = {(x, y) : y e Y, x e Empty set} 
2. (A n B) * Y = (A * Y) n (B * Y)

##### Proof of part 0 
To prove L = R where L = (A u B) * Y and R = (A * Y) u (B * Y)

We will prove two things: 

a) L is a subset of R
b) R is a subset of L

Proof of a): take l e L so l = (x, y) where x e A u B and y e Y. so either (x e A and then l = (x, y) e A * Y) or (x e B then l = (x, y) e B * Y) so in every case l e (A * Y) u (B * Y) = R therefore l e R.

Proof of b): Pick r e R so r e A * Y or r e B * Y. In the case where r e A * Y we have r = (a, y) where a e A and y e Y. therefore r = (a, y) e (A u B) * Y = L because a e A u B. In the case where r e B * Y we have r = (b, y) where b e B and so r = (b, y) e L. By the double inclusion lemma we conclude L = R.

##### Proof of part 1
We can prove this by proving that the cardinality of the cartesian product is the product of the cardinality of the sets. #(X * Y) = #(X) * #(Y)

For the special case where \#X = 1. In the case where the function PI2:  X * Y -> Y is an invertible function. Say X ={:smile:}. PI2((:smile:, y)) = Y has inverse F : Y -> X * Y given by function F(y) -> (:smile:, y). So #(X * Y) = \#Y because of the invertible PI2.

Now the general case by induction: Say Sn is : If \#X = n then #(X * Y) = #(X) * #(Y) is true.
To prove S0 : If \#X = 0 then (exercise) X = Empty set, so #(X * Y) = #(X) * #(Y) holds. Assume Sn holds for some n e Natural numbers then we can prove Sn+1 : Recall lemma 2.9 : If A n B are disjoint and finite then #(A u B) = \#A + \#B, #(Complement of A) = \#X - \#A

Assume \#X = n + 1: and take x0 e X. #(X * Y) = #(({x0} u {x0}^c) * Y) from part 0 we know that this

#### Sources:
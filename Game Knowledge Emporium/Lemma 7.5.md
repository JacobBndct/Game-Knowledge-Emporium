__________________________________________________________________________
#### **Tags:** #Math/Numbers 
###### *Date Of Creation: 2023-11-05*
__________________________________________________________________________

Suppose a, b, q, r ∈ Z satisfy (a, b) ̸= (0, 0) and a = qb + r. Then gcd(a, b) = gcd(b, r). 

Proof. We show a stronger statement, namely Dvs(a) ∩ Dvs(b) = Dvs(b) ∩ Dvs(r). If this is the case, then the maximal element of these intersections will be the same and that is what the lemma asserts. 

Proving the equality of sets will be done using Lemma ??. If c ∈ Dvs(a) ∩ Dvs(b), then Theorem 7.1 shows c ∈ Dvs(r) as well, so Dvs(a) ∩ Dvs(b) ⊆ Dvs(b) ∩ Dvs(r). Vice versa, given d ∈ Dvs(b)∩Dvs(r), Theorem 7.1 implies d ∈ Dvs(a), hence Dvs(b)∩Dvs(r) ⊆ Dvs(a)∩Dvs(b). The desired equality of sets follows, and this finishes the proof of the lemma.

How do the properties listed above together with Lemma 7.5 help us to compute gcd(a, b)? First of all, we are allowed to replace a by |a| and b by |b|. This means we are reduced to the situation where a, b ≥ 0. Moreover we may swap a, b. Hence we can assume a ≥ b ≥ 0. If here b = 0 then we know the gcd, so what remains is the case a ≥ b ≥ 1. Here Lemma 7.5 helps: it tells us that gcd(a, b) = gcd(b, a − qb) regardless of the choice of q ∈ Z. In other words, we are allowed to subtract a convenient multiple of b from a, and replace a by the result. In this way one ends up with a gcd of two smaller nonnegative integers. Repeating this process sufficiently often results in a situation we can easily handle (for example because the smaller one of the two integers is 0). 

The next result, and for practical purposes its proof, indicates the existence of a ‘good’ q resulting in an as small as possible nonnegative r = a − qb.
#### Sources
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
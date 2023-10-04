__________________________________________________________________________
#### **Tags:** #Math/SetTheory 
###### *Date of Creation: 2023-10-03*
__________________________________________________________________________

*Given functions $f:X \rightarrow Y$ and $g: Y \rightarrow Z$ define the function $g \circ f: X \rightarrow Z$ by $(g \circ f)(x) = g(f(x))$ and will be pronounced as "$g$ on $f$".*
### Properties of composition of functions
1. [[Composition is Associative|Composition is associative]]
2. [[Properties of composition|The composition of two injective functions is injective]] (one-to-one)
3. [[Properties of composition|The composition of two surjective functions is surjective]] (onto)

An important special case is where we have a single function $f: X \rightarrow X$. Without worrying about brackets we can compose $f$ with itself many times and many interesting problems can be reformulated as the question: what happens to the functions $f \circ f \circ f \dots \circ f$ eventually as the number of compositions grow? For later use we introduce the special notation for any $n \in \Bbb N$ for repeated composition: $$f^{(n)} = f \circ f \circ f \dots \circ f$$
where we compose $n$ copies of f and by convention we set $f^{(0)} = id_x$ 
#### Sources:
__________________________________________________________________________
1. [Sets_and_Numbers.pdf (rolandvdv.nl)](https://www.rolandvdv.nl/Sets_and_Numbers.pdf)
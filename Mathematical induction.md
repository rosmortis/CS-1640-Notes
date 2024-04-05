# Three Types of Induction
1) Induction (a.k.a weak induction)
2) Strong induction
3) Structural Induction

For types one and two, they are used to prove statements based on consecutive integers starting at a specific integer.

# General Format 
**Statement to be proved**

**Base case:** Show the statement is true for the smallest integer

**Inductive Step:** prove the conditional if the statement is true for a specific integer, then i must be true for the next consecutive integer value. 

**Conclusion**

## Example:

$S(n)$ is the statement to prove, where $n \in \mathbb{Z}^+$

Base case: verify $S(1)$ is true

| n:   | 1    | 2    | 3    | 4    | 5    | 6    | 7    |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| S(n) | S(1) | S(2) | S(3) | S(4) | S(5) | S(6) | S(7) |
**Thus:**
$S(k) \to S(k + 1)$
$S(1) \to S(2)$
$S(2) \to S(3)$
$S(3) \to S(4)$
$S(4) \to S(5)$

## Example 2

$P(n) = 1^2 + 2^2 + 3^2 + 4^2 + ... n^2$

**Where:**
$P(3) = 1^2 + 2^2 + 3^2 = 16$
$P(7) = 1^2 + 2^2 + 3^2 + ... + 7^2= 140$

**Proof:**
We shall prove $P(n) = {n(n+1)(2n+1) \over 6}$ Where $P(n) = 1^2 + 2^2 + 3^2 + 4^2 + ... n^2$ for $n \in \mathbb{Z}^+$

**Base Case:** $n =1$ 
$P(1) = 1^2$ 
$P(1) = {1(1+1)(2(1)+1) \over 6}$

**Inductive Step:** Prove if true for $P(k)$ for some $k \in \mathbb{Z}^+$ then  it is true for $P(k+1)$ (IH)

Want to show $P(K + 1) = {(K + 1)((K + 1)+1)(2(K + 1)+1) \over 6}$

**Starting with the LHS:**
$P(k+1) = 1^2 + 2^2 + 3^2 + 4^2 + ... + k^2 + (k+1)^2$

$$= {k(k+1)(2k+1) \over 6} + (k+1)^2$$ 

$$= {k(k+1)(2k+1) \over 6} + {6(k+1)^2 \over 6}$$

$$= {k(k+1)(2k+1) + 6(k+1)^2 \over 6}$$

$$= {(k+1)k(2k+1) + 6(k+1) \over 6}$$

$$= {(k+1)(2k^2 + 7k + 6) \over 6}$$

$$= {(k+1)(k+2)(2k+3) \over 6}$$ 
$$= {(k+1)((k+1)+1)(2(k+1)+1) \over 6}$$

Which is the RHS of the equation therefore $P(n)$ is true for $n \in \mathbb{Z}^+$.

**Note:** At the common denominator set you can choose to brute force expand the polynomial, and if it matches the first step then you are done.

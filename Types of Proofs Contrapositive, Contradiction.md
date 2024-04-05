Monday - direct proof of $p \to q$ : assume p is true and q us true

indirect proof methods of $p \to q$
- proof by contrapositive
- proof by contradiction

# Proof by Contrapositive
Contrapositive of $p \to q$ is $\lnot q \to \lnot p$ 
This method proves $\lnot q \to \lnot p$, which proves $p \to q$ indirectly.

Assume: $\lnot q$ is true
Show: $\lnot p$ must therefore be true

## Example
**Theorem:** for $a,b \in \mathbb{Z}^+$ if n = ab then $a \leq \sqrt{n} \space or \space b \leq \sqrt{n}$ 

contrapositive: if $a > \sqrt{n} \space or \space b >  \sqrt{n}$ then $n \neq a \times b$

# Proof by Contradiction
Assume: $(p \to q)$ is false ( assume $p$ is true AND $q$ is false)
Show: there is a contradiction (there are conflicting facts)

## Example
Given $w, x, y, z \in \mathbb{Z}$ if $w|z$ and $y|z$ then $wy|xz$ 

What do we assume, and what do we need to show for: 

**Direct Proof**
- Assume: $w|x$  and $y|z$
- Show: $wy|xz$

**Contrapositive**
- Assume: $wy \nmid xz$
- Show: $w \nmid x$ or $y \nmid z$

**Contradiction**
- Assume: $w|x$ and $y|z$ and $wy|xz$
- Show: There is a problem somewhere 

---
# Other Proof Methods

## Proof by Cases
If a domain is involved in a proof by cases what you do is you partition the domain into subsets and theses are your cases. Then you prove the statement for each case. that means that you are writing more than one proof in one or mare than one argument but that can meant that it is easier overall. 

$\forall n \in \mathbb{Z}, n^2 \leq n$
if $n \in \mathbb{Z}$ then $n^2 \leq n$

**Case 1: $n > 0$**
since n is positive then we can multiply both sides by n

**Case 2: $n = 0$**
since n is only on value in this case we can directly apply it to the assumed. 

**Case 3: $n < 0$**

## Example 2
Given $x , y$ are integers if x < y and they are consecutive then they have opposite parity(even oddness)

**Case 1: x is even**
Since x is even $x = 2k$ for some integer k. since $x<y$ are consecutive $y = x + 1$ and thus $y = 2k + 1$ and is odd.

**Case 2: x is odd**
Since x is odd x = 2k + 1 for some integer k, since $x < y$ are consecutive $y = x + 1$ and thus equals $y = (2k + 1) +1$ Combining we get $y = 2k + 2$ factoring out the 2 we get $y = 2(k+1)$ and is even. 

# Proof by Exhaustion
Can only be used on a finite domain. Verify the statement you are proving by applying it to every element in the domain. 

## Example 1
prove $(n+1)^3 \geq 3^n$ for $n \in \mathbb{Z}^+, n \leq 4$
$(1+1)^3 \geq 3^1$
$(2+1)^3 \geq 3^2$
$(3+1)^3 \geq 3^3$
$(4+1)^3 \geq 3^4$

# Vacuous Proof
When proving $p \to q$ and p is always false. 

ex. $if \space 0 > 1 \space then \space 0^2 > 0$

While this is false mathematically it is proven true

# Trivial Proof
When proving $p \to q$ and q is always true

ex. if pigs can fly then 1 = 1
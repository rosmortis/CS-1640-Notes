
# Inverse Functions
## Examples of functions that need inverses.

1) Encoding Functions
Need to be able to go both ways so you can encode and decode data

- Data transmission of digital messages (can be errors in transmission)
	- F(011010) = 000 111 111 000 111 000
	- This function multiples by a factor of three and looks at the resulting so it easer to 

- Encryption Functions
	- Assuming you have some thing you want to encrypt than you need to encrypt and be able yo decrypt thus a function that needs an inverse.

## Examples of functions that shouldn't have inverses

1) A hash function
	- A hash function that takes an input of variable length and has an output of fixed length (called a hash)
	- Database stores username and the hash of your password
	- Thats why you have to reset your password, because they don't store it


# Intro. to Proofs 

We have done partial proofs already on logic 
- Using [[Rules of Inference]]
- Using laws of compound propositions .

Proofs are a form of writing
- Introduce 
- Body proof
- Conclusion
use complete sentences (except with algebra)

Usually will be proving conditional statements or can be worded as conditional statements (if-then)

# Proofs in CS
- Verify correctness of a program/system
- Establish that an OS or Network is secure
- Show system specifications are consistent

Proofs of statements(theorems) - many of these are: 
- quantified statements
- conditional statemnets

rewriting a statement with quantifiers / conditional 

**Example:** 
$x+y = y+x \text{ for real numbers}$ $x$ and $y$

**Reworded:** 
For all real numbers $x$ and $y$, $x + y = y + x$

**Rewritten as a Conditional Statement:**
$\forall x \forall y (((x \in \mathbb{R}) \land (y \in \mathbb{R}) \to x + y = y + x))$

We will start out by proving a conditional statement.

Start a proof by clearly stating what will be proved.
may include:
- quantifiers
- variables
- math (algebra) symbols
- logic symbols

# Proofing Quantifyers
## Existential statement ($\exists$) 
to prove true:
- give one example the statement is true for
to prove false:
- prove the universal statement of the negative
	- $\lnot (\exists p(x)) \equiv \forall x \lnot p(x)$


## Showing an algebraic statement is even or odd:
Even int: 2k where $k \in \mathbb{Z}$
Odd int: 2m+1 where $m \in \mathbb{Z}$

**ex.** Show $2m^2 - 4m + 3$ is odd, where $m \in \mathbb{Z}$

rewrite as 2(     )+1 

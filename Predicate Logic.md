# Predacites 

predicates = logic functions

**Logical statement:** 
$$
\text{p : red is a primary color}
$$

**Predicate:**
$$
\text{P(x) : "x is a primary color"}
$$ 

**Example:**
$$
\begin{align*}
&\text{P(red) : is true}\\
&\text{P(orange) : is False}\\
\end{align*}
$$
**The domain of the predicate (or Domain of Discourse)**
- The set of all possible inputs of a predicate

**Common domains for numbers**
- integers( $\mathbb{z}$)
- positive integers
- rational numbers

# Example
$$\text{P(x) : "2 x > x", where x} \in \mathbb{z}$$
P(1) = is true
P(2) = is true
P(0) = is false
P(-1) = is false

**Quantifiers of a predicate:**
$\forall$ universal quantifier "for all"
$\exists$ existential quantifier "there exists"

$$\forall \text{x P(x) : "2 x > x", where x} \in \mathbb{z}$$
Quantified predicate means: "for all passible values in the domain , P(x) is true"

$\forall \text{x P(x)}$ has a truth value, $\forall \text{x P(x)} \equiv T$

# Example 2

$$\text{Q(x): "2 x - 1 > 0", where x} \in \mathbb{z}$$

$\forall \text{x Q(x)}$ is false since Q (- 1) is False.
"Counterexample" is one input that entirely dis proves the statement.

$\exists \text{x Q(x)}$ is true an example is Q(2)
means "there exists (at least) one value x in the domain , where Q(x) is true"

**In General:**
Easy to prove:
	$\forall \text{x P(x)}$ is False 
	$\exists \text{x Q(x)}$ is True 
Hard to prove:
	$\forall \text{x P(x)}$ is True 
	$\exists \text{x Q(x)}$ is False 

# DeMorgan's Laws for Quantified Statements

 DeMorgan's Laws for propositional logic
$$
\begin{align*}
\lnot (p \lor q) \equiv \lnot p \land \lnot q \\
\\
\lnot (p \land q) \equiv \lnot p \lor \lnot q \\
\end{align*}
$$
 DeMorgan's Laws for Quantified statements
$$
\begin{align*}
\lnot (\forall \text{x P(x)}) \equiv \exists x \lnot P(x) \\
\\
\lnot (\exists \text{x P(x)}) \equiv \forall x \lnot P(x) \\
\end{align*}
$$
# Translating from English to Quantified Statements  


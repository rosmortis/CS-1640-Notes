In the following , the domain is the set of all employees at a company. One of the employees is named sam. Define the following predicates:

T(x): x is a member of the executive team
B(x): x received a large bonus

**Format:** quantifier variable predicate

1) Someone did not get a large bonus
	$\exists x \lnot B(x)$
2) Everyone got a large bonus
	 $\forall x B(x)$
3) Sam did not get a large bonus even though he is a member of the executive team
	$\lnot B(sam) \land T(sam)$
4) Someone who is not on the executive team got a large bonus
	$\exists x(\lnot T(x) \land B(x))$
5) Every executive team member got a large bonus
	$\forall x (T(x) \to B(x))$

With $\forall$ use the conditional operator not  $\land$ because T(x) is a sub set of the full domain you have to use the conditional. Otherwise "Every executive team member got a large bonus" would mean "All employees are members of the executive branch and got a raise"

# Nested Quantifiers
- quantifier nested with in the scope of another 

## Example 

Set domain to all real numbers $x,y \in \mathbb{R}$ $\forall x \exists y(x + y = 0)$

For each real number x, there exists a real number y where x + y = 0

different quantifiers $\to$ order matters 

same quantifiers $\leftrightarrow$ order does not matter 

$\forall x \forall y P(x,y) \equiv \forall y \forall x P(x,y)$

## DeMorgans law with nested quantifiers:
(same idea)

$\lnot (\forall x \exists y \forall z P(x,y)) \equiv \forall x \exists y \forall z \lnot P(x,y)$


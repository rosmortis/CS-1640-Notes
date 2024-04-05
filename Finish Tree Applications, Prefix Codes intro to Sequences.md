# Sequences and Recurrence Relationships

sequence = an ordered list of values or a function where the domain is a set of consecutive integers (usually starting at one)

**Example**
A sequence 1, 4, 9, 16, 25, 36,...

Function a<sub>n</sub> = n<sup>2</sup> for n = 1,2,3,4,...

A sequence always has a "first term" or "first value"

In a sequence the order is immutable, and they are labeled with a subscript 

# Definitions
**Increasing:**
 $\forall$ k , a<sub>k + 1</sub> > a<sub>k</sub>

**Decreasing:** 
 $\forall$ k , a<sub>k + 1</sub> < a<sub>k</sub>

**Non-increasing:** 
 $\forall$ k , a<sub>k + 1</sub> $\leq$ a<sub>k</sub>

**Non-decreasing**
 $\forall$ k , a<sub>k + 1</sub> $\geq$ a<sub>k</sub>

Note: non-increasing is not the same as not increasing! negating increasing we get $\exists$ k , a<sub>k + 1</sub> $\leq$ a<sub>k</sub> 

**Examples:**
1) 1,2,3,4,5,...  (increasing, non-decreasing)
2) 1,2,2,3,4,4,5,6,6...   (non-decreasing)
4) 1,2,3,5,6,5,8,9,10,...  (none of the four)
6) 2,1,-1,-2,-2,-2,-3,-5,...  (non-increasing)

# Defining a Sequence
1) Closed formula **ex:** $a_k = k^2$ for $k \in \mathbb{Z}^+$
2) Recurrence relation: a sequence is defined where a term of the sequence is defined as a function of one or more previous terms. 
**ex:** 2, 4, 8, 16, 32, 64,... representing this a recurrence relationship 
$$
\begin{align*}
&a_1 = 2 \\
&a_k = 2 \times a_{k-1} \text{ for } k = 2, 3, 4,...
\end{align*}
$$
**Note:** its much easier to find terms for higher order values of k if you can use a closed formula

**EX** of a sequence that does not  have closed formula: Pingola-Fibonacci 
$$
\begin{align*}
&p_1 = 1 \\
&p_2 = 1 \\
&p_k = p_{k - 1} + p_{k - 2} \text{ for } k = 3, 4, 5, ...\\
\end{align*}
$$

## Application of Recurrence Relations: Discrete Time Dynamical Systems
- Finite steps in time when things actually happen(for example 1/2 second, 30 seconds, 1 hour)
- The terms of the sequence represent the state of (some kind of value of measurement) at that particular step in time

## Recurrence Relations and Recursive Definitions
- Both based on the same idea: defining something in terms of previous or smaller values

1) Recurrence relation
	- a sequence that is defined recursively (by a function of one or more previous terms)
2) Recursive definitions - 3 types
	
	1) **Recursively Defined Function**
	- The output of the function is based on one or more outputs of the same function
	- The Factorial: $n! = n(n-1) \times (n-2) \times ... 1$  for $n \geq 0$
		- recursive definition of factorial
		- base case $0! =1$
		- recursive rule $n! = n(n-1)!$ for $n \geq 1$
	
	2) **Recursively defined set**
	- Elements of the set are built / constructed based on other elements of the set
	- Define set **A** as follows:
		- Base Case : $5 \in a$
		- recursive rule: if $x \in A$ then $x + 5 \in A$
		- if $5$  then $5 + 5 \in A$
		- A = {5, 10 , 15, 20, 25,...}
	- Define set **B** as follows:
		- Base case: $4 \in b$
		- Recursive rule: if $x \in B$ and $y \in B$ then $x+y \in B$
		- B = {4, 8, 12, 16, ...}
	- A function thats based on a recursively defined set
		- Where the set is the domain of the function.
		- 
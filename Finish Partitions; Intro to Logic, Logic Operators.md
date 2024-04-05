#CS1640 

# Logic

## Propositional  Logic
- More basic
- Proposition is a statement that is true of false / has a truth value
- Cant be a question
- Cant be a matter of opinion
- Usually denoted by lowercase letters (p & q) but others can show up
- Make more advanced propositions via logical operators

$$
\begin{array}{|c|c|}
\hline
\text{Operation} & \text{Symbol(s)} \\
\hline
\text{Not / Negation} & \sim, \neg \\
\text{And / Conjunction} & \land, \wedge, \& \\
\text{Or / Disjunction} & \lor, \vee, \| \\
\text{Implication} & \rightarrow, \Rightarrow \\
\text{Biconditional} & \leftrightarrow, \Leftrightarrow \\
\hline
\end{array}
$$
## **Conditionial operators:**
Read "if p than q"
$$
p \rightarrow q
$$
**p** = You mow Mr. smiths lawn.
**q** = he will pay you. 
"If you mow Mr. Smith lawn then he will pay you" = True 
"You don't mow Mr. Smith's lawn he doesn't pay you" = True
"You mow Mr. Smith's lawn and he doesn't pay you" = False

## **Biconditional Operators**
**p:** I finish my CS1640 Homework
**q:** I will go to the movies

$$
p \leftrightarrow q
$$

the difference here is in meaning,

| p | q | Value |
| ---- | ---- | ---- |
| T | T | T |
| F | T | F |
| T | F | F |
| F | F | T |

**Converse:** $$ q \rightarrow p $$
**Inverse:**$$ \neg p \rightarrow \neg q $$
**Contrapositive:** $$ \neg p \rightarrow \neg q$$

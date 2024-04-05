
**Satisfiability:** A compound proposition is called satisfiable if is true for at least one set of inputs (truth table has at least on "T"). 

We can reright in the system specifications example (consistency) to be a Satisfiability problem.

$$
(\lnot L \to Q)\land(\lnot L \leftrightarrow N) \land (\lnot Q \to B) \land (\lnot L \to B) \land \lnot B
$$
satisfiable? Yes, Because its the same problem. 

## logical Equivalence

Two propositions are logically equivalent when they have the same truth values (same truth table).

$$
(p \to q) \equiv (\lnot q \to \lnot p)
$$
There are multiple ways to show logical equivalence:
1) Show truth tables mach
2) Use laws of propositional logic

### Example

**Show:** $(p \to q) \lor (p \to r) \equiv p \to (q \lor r)$

**Truth Table:**

| P | Q | R | $p \to q$ | $p \to r$ | $(p \to q) \lor (p \to r)$ | $q \lor r$ | $p \to (q \land r)$ |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| T | T | T | T | T | T | T | T |
| T | T | F | T | F | T | T | T |
| T | F | T | F | T | T | T | T |
| T | F | F | F | F | F | F | F |
| F | T | T | T | T | T | T | T |
| F | T | F | T | T | T | T | T |
| F | F | T | T | T | T | T | T |
| F | F | F | T | T | T | F | T |
Because the rows with the final propositions exactly match they are logically equivalent. 

**Laws of Propositional logic:**

$(p \to q) \lor (p \to r) \equiv p \to (q \lor r)$

| $(p \to q) \lor (p \to r)$ | Idenity |  |
| ---- | ---- | ---- |
| $(\lnot p \to q) \lor (\lnot p \to r)$ | conditional |  |
|  |  |  |

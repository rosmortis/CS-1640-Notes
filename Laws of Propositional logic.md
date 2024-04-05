
# Proof Example

$(p \to q) \lor (p \to r) \equiv p \to (q \lor r)$

**What We Want:** $\lnot p \lor (q \lor r)$

| $(p \to q) \lor (p \to r)$ | **Identity** |
| ---- | ---- |
| $(\lnot p \lor q) \lor (\lnot p \lor r)$ | Conditional |
| $(q \lor \lnot p) \lor (\lnot p \lor r)$ | Communative |
| $q \lor \lnot (p \lor \lnot p) \lor r$ | Associative |
| $q \lor \lnot p \lor r$ | idempotent |
| $\lnot p \lor (q \lor r)$ | Communative & Associative |
| $p \to (q \lor r)$ | Conditional  |

# Predicate logic

A predicate is basically a function in logic. 

A proposition (p,q) has a truth value.

A predicate does not have a truth value, unless:
1) an input us plugged in 
2) if a quantifier is placed in front of it. 
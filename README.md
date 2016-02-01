# dismathportfolio-darylloveros

#WEEK 1
- The professor narrated his awesome background to us, and we also introduced ourselves, our hobbies and goal for the subject.
- The Truth Table is a list of possible logical inputs with corresponding output.
- This subject course is important because the concepts will be used when we study Logic Circuits.
- We learned the various types of logical connectives such as negation, conjunction, disconjunction, and exclusive or.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |

#WEEK 2
- We learned the two remaining logical connectives, the conditional and biconditional implications.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

- We also learned another way of proving propositions, which is by using the logical equivalences.

| Laws | Logical Equivalences |
| :-----: |:-------:|
| Identity Laws | p v F = p; p ∧ T = p |
| Domination Laws | p v T = T; p ∧ F = F |
| Negation Laws | p v ¬p = T; p ∧ ¬p = F |
| Double Negation Law | ¬(¬p) = p |
| Idempotent Laws | p v p = p; p ∧ p = p |
| Commutative Laws | p v q = q v p; p ∧ q = q ∧ p |
| Associative Laws | (p v q) v r = p v (q v r) |
| Distributive Laws | p v (q ∧ r) = (p v q) ∧ (p v r) |
| De Morgan's Laws | ¬(p ∧ q) = ¬p v ¬q |
| Absorption Laws | p v (p ∧ q) = p; p ∧ (p v q) = p |

- Using these logical equivalences, we have proven that  ¬(p v (¬p ∧ q)) ≡ (¬p ∧ ¬q).
- We have learned new terms such as the converse, inverse, and contrapositive.
- Tautology is the statment that is always true.
- Predicate logic is concerned not only with logic relations between propositions as wholes (propositional logic), but also their internal structures (subject and predicate).
- Quantifiers indicate the generality of the open sentence in which a variable occurs.
- Existential quantifier means that there exists a true value in the possible values for a statement.
- Universal quantifier means that the statement is true for all possible values.




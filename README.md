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

#WEEK 3
- We have learned the concept of Rules of Inference.
- We have also defined different related terms such as an argument, validity and fallacy.
- The validity of an argument comes with the pattern of premises.
- The truth of conclusion depends on the truth of the premises.
- I have noted that all valid premises does not always lead to a true conclusion.
- There is a variety of rules of inference, with their corresponding tautology and names.

#WEEK 4
- We have used the concept of using rules of inference to build arguments.
- We use atomic propositions to specify different logics of premises.
- We have also learned the basic concept of Proof; an argument that demonstrates why a conclusion is true.
- A Direct Proof is tested to assume p to be true, and show that q is true using the first assumption.
- An Indirect Proof/ Proof by Contraposition is used by assuming the negation of q to be true, and then showing that the negation of p is also true using the first assumption.
- A Vacuous Proof shows that the antecedent p is false, because p → q must be true when p is false.
- A Trivial Proof shows that the consequent q is true because p → q must also be true.

#WEEK 5
- In Proof by Contradiction, one must show that assuming the negation of a premise is true leads to a contradiction.
-  We have tested different conditions and premises using this kind of proof.
-  In this proof, according to Sir Arthur Conan Doyle, "When you have eliminated all which is impossible, then whatever remains, however improbable, must be the truth."
-  In Proof by Equivalence, it is a combination of a direct and indirect proof.



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
- We also studied the Mathematical Induction, first having a Basis Step, and then an Inductive Step using the Direct proof.
- Ina Recursive/ Inductive Definition, we first have a Basis step (specifying the value of function at zero), and then the recursive step, giving a rule for finding its value at an integer from its values at smaller integers.
- For example, if f(0)=3, and f(n+1)=2f(n)+3, then f(1)=9, f(2)=21, f(3)45, and f(4)=93, using the recursive method.
- You need an initial assertion, final assertion, and a segment to prove a program correctness.

#WEEK 6
- We had an introduction to Set Theory, and it somewhat refreshed our learnings from our highschool mathematics.
- We discussed the definitions of set, empty set, membership, set-builder notations, and venn diagrams.
- We had also distinguished the properties of union, intersection, subtraction, and symmetric difference.
- The Set Identities have very similar inputs with the Logical Equivalences properties.
- Subsets and power sets were also discussed thoroughly.
- The Power Series also has similar notations with the Geometric Series.
- We could identify patterns from previous discussions that are helpful to us in understanding the concepts of this chapter.

#WEEK 7
- We have discussed the properties of functions.
- We assign exactly one element to set B to say that it is a function.
- The domain, co-domain and range were discussed with proper distinctions.
- There three types of functions: one-to-one function, onto function, and one-to-one correspondence.
- One-to-one function (injective) is a function that never assign the same value to two different domain elements.
- Onto function (surjective) is a function that have equal range and codomain.
- One-to-one correspondence (bijective) is the mixture of injective and surjective functions.
- In  a venn diagram, the intersection of an injective function and surjective function is a bijective function.


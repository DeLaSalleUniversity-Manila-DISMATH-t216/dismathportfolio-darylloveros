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

#WEEK 8
- An algorithm is a finite set of precise instructions for performing a computation or for solving problems.
- We could use an algorithm to find the maximum number in a given set of numbers.
- Concepts in programming are very much helpful in constructing algorithms.
- Pseudocodes are the building blocks of an alogrithm.
- It is important to determine the precondition, procedure, and post condition in writing algorithms.

#WEEK 9
- We have learned the different types of algorithms.
- For Searching Algorithms, we can use a) Linear Search or b) Binary Search Algorithms.
- A Linear Search is concerned in finding a particular value in a list that checks each element in sequence until the desired element is found.
- A Binary Search is concerned in comparing the middle values of a list then repeated until the desired output is found.
- For Sorting Algorithms, we can use a) Bubble Sort or b) Insertion Sort Algorithms.
- Bubble Sort compares the first two elements then interchanging them if they are in the incorrect order.
- Insertion Sort compares the second element with the first and inserts it before the first element if it is less; otherwise, it is inserted after the first element.
- A Greedy Algorithm is an algorithm that make what seems to be the "best" choice at each step.

#WEEK 10
- We have learned the concept of Growth of Functions.
- Two functions can be compared through Big-O Notations.
- Big-O Notation is the upper bound of a given function.
- Big-Omega Notation is the lower bound of a given function.
- Big-Theta Notation can be both the upper and lower bound of a given function.
- Constants C and k (witnesses) are important in determining the growth of functions.
- Algorithm Time Complexity can be expressed in terms of the number of operations used by the algorithm when the input has a particular size.
- we could describe the time complexity of an algorithm by counting the comparisons done.

#WEEK 11
- We have learned the concept of Graph Theory.
- A graph is a discrete structure consisting of vertices and edges that connect these vertices.
- A degree is considered as the number of connections in a graph.
- We use the Handshaking Theorem to determine the number of edges, given the number of vertices and degree.
- A path is a sequence of edges.
- An Euler path is a simple path containing every edge of a graph.
- An Euler circuit is a simple circuit containing every edge of a graph.
- For us to have an Euler circuit, we should have even degrees for all the nodes.
- It is a Euler path if we have exacctly two nodes that have odd degrees.
- A Hamilton path is a simple path that passes through every vertex exactly once.
- A Hamilton circuit is a simple circuit that passes through every vertex exactly once.
- Two graphs are isomorphic if they have the same number of nodes.
- Planar graphs are graphs that can be drawn in the plane with edges not crossing each other.
- We use the Euler's Formula to determine the number of regions, given the number of edges and vertices.
- Kuratowski's Theorem states that a graph is nonplanar if and only if it contains a subgraph homeomorphic to a k,3,3 and k,5.

#WEEK 12
-   Graph Coloring is the assignment of a color to each vertex of the graph so that no two adjacent vertices are assigned the same color.
-   The chromatic number is the least number of colors that are assigned in a graph.
-   The Four Color Theorem states that the chromatic number of a PLANAR graph is no greater than four; if NON-PLANAR, it could be more than four.
-   A Tree is a connected undirected graph with no simple circuit.
-   Some terminologies like roots, parent, and children are used in this concept.
-   A forest is a connection with two or more trees.
-   M-ary trees are trees with no more than m children.
-   A binary tree is an m-ary tree with two children.
-   Several properties are needed to be considered in determining the internal vertices and leaves of a given tree.

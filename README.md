# dismathportfolio-miko-mendoza

## My DISMATH weekly portfolio 

# **Week 1**

- I was introduced to a new subject called **Discrete Mathematics** or *DISMATH*
- I learned about logical connectives. The logical connectives are shown in the table below.

| Operator | Symbol | Usage | Java/C++ |
| :---: | :---: | :---: | :---: |
| Negation | ¬ | not | !
| Conjunction | ∧ | and | &&
| Disjunction | v | or | \|\|
| Exclusive-or | ⊕ | xor | (p\|\|q&&!p\|\|!q)
| Conditional | → | if,then | p?q:true
| Biconditional | ↔ | if & only if, iff | (p&&q)\|\|(!p&&!q)

- I learned about mathematical proofs, propositional statements, logical deductions and axioms.
- I learned about propositional variables.
- I also learned about truth tables. The truth table for conjuction is shown below.

| P | Q | P∧Q |
| :---: | :---: | :---: |
| T | T | **T** |
| T | F | **F** |
| F | T | **F** |
| F | F | **F** |

- I learned about propositional logic. These are: *Converse logic*, *Inverse logic*, and *Contrapositive logic*.
- I learned about logical equivalences.
- I also learned that Superman does not logically exist.

# **Week 2**

- I was introduced to a new lesson called **Predicate Logic**
- I learned about quantifiers. 
  * **Existential Quantifier** (∃x) - "There exist" is true iff P(x) is true for at least one value in the x domain.
  * **Universal Quantifier** (∀x) - "For all" states that a predicate is true for any value in a particular domain.
- I also learned about terminologies for **Rules of Inference**
  * **Argument** - A sequence of statements that end with a conclusion (p<sub>1</sub>∧p<sub>2</sub>∧p<sub>3</sub>∧...∧p<sub>n</sub>) → q
  * **Valid** - The conclusion, or final statement of the argument, must follow from the truth of the preceding statements, or premises, of the argument.
  * **Fallacy** - Common form of an incorrect reasoning that leads to an invalid argument.
  * **Tautology** - Statement that is always *TRUE*.

# **Week 3**

- I learned about the rules of inference

| Rule of Inference | Tautology | Name |
| ----- | :---: | :---: |
| p<br>p→q<br>____<br>∴ q | (p∧(p→q))→q | Modus Ponens |
| ¬q<br>p→q<br>____<br>∴ ¬p | (¬q∧(p→q))→¬p | Modus Tollens |
| p→q<br>q→r<br>_____<br>∴ p→r | ((p→q)∧(q→r))→(p→r) | Hypothetical Syllogism |
| p∨q<br>¬p<br>____<br>∴ q | ((p∨q)∧¬p)→q | Disjunctive Syllogism |
| p<br>_____<br>∴ p∨q | p→(p∨q) | Addition |
| p∧q<br>____<br>∴ p | (p∧q)→p | Simplification |
| p<br>q<br>_____<br>∴ p∧q | ((p)∧(q))→(p∧q) | Conjunction |
| p∨q<br>¬p∨r<br>_____<br>∴ q∨r | ((p∨q)∧(¬p∨r))→(q∨r) |

- We had exercises about the Rules of Inference
- I learned how to use the Rules of Inference in arguments and premises
- I learned the difference between If-Then statements & If and only If (iff) statements.

# **Week 4**

- I learned about the different **Methods of Proof**.
  - Direct Proof
    * Steps:
      1. Assume p is true
      2. Show that q is also true, using (1).
  - Proof by Contraposition (Indirect Proof)
    * Steps:
      1. Assume ¬q is a hypothesis
      2. Show that ¬p must be true using definitions, and previously defined theorems.
  - Vacuous Proof
    * Steps:
      1. Show that p is false
      2. p→q must be true when p is false
      3. ¬p→(p→q)
  - Trivial Proof
    * Steps:
      1. Show that q is true
      2. p→q must also be true
      3. q→(p→q)
  - Proof by Contradiction (Indirect)
    * Steps:
      1. Assume ¬p
      2. Show that (1) ends up in a contradiction
      3. ∴ p is proven to be true
  - Proof by Equivalence (p↔q)↔\|(p→q)∧(q→p)\|
    * Steps:
      1. Show that p→q is true
      2. Show that q→p is also true
 
# **Week 5**
- We went back to recursive algorithms this week.
- We also discussed about power sets.

# **Week 6**
- I learned about functions this week.
    * A function 'f' is an assignment of exactly one element of its **range** to a **domain**
    * A **one-to-one** function or the **injection** function is a function where every element of the range of the function corresponds to exactly one element of the domain.
    * **Onto** function or **subjection** is a function where the functions have **equal** range and domain.
    * **One-to-one** correspondence or **bijective** is **both** one-to-one and onto.

# **Week 7**
- We did not meet this week.

# **Week 8**
- We discussed about algorithms this week.
    * **Algorithms** are a finite set of precise instructions for performing a computation or for solving a problem.
    * **Pseudocodes** are a high-level description of an algorithm that uses the structural conventions of a programming language, but is intended for human reading.
    * Some of the algorithms we learned are:
       * **Searching Algorithms**:
          * Linear Search
          * Binary Search
       * **Sorting Algorithms**:
          * Bubble Sort
          * Insertion Sort
       * Greedy Algorithm 

# **Week 9**
- In the first meeting of the week, I learned about **Growth of Functions**.
- 

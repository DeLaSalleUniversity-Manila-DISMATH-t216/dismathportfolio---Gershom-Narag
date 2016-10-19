# dismathportfolio---Gershom-Narag

##Week 1
- I was introduced to the subject DISMATH and professor Cabatuan

- We talked about propositions and proofs

- A proposition is any question answerable by a "True" or a "False", and a proof is a set of deductions that prove whether the proposition is true or not

- A list of logical connectives I learned:

| Logical Symbol  |  Logical Operator     | Shorthand | Formula                                       | Logical Expression             |
| :-------------: |:---------------------:|:---------:|:---------------------------------------------:|:-----------------------------:|
| ¬               | Negation              | not       | val(¬p) = 1 - val(p)                          | ¬p                           |
| ∧               | Conjunction           | and       | val(p ∧ q) = min(val(p), val(q))              | p ∧ q                          
| v               | Disjunction           | or        | val(p v q) = max(val(p), val(q))              | p v q                        |
| ⊕              | Exclusive disjunction | xor       | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| →               | Conditional           | if, then  | if val(p)  ≤ val(q) = 1 , otherwise  0        | p → q ≡  ¬p v q              |
| ↔               | Biconditional         | iff       | if val(p) equals val(q) = 1 , otherwise  0    |  p ↔ q ≡ (p → q) ∧ (q → p)    |

-I found the lessons relatively easy to understand

##Week 2

- I was introduced to Logical Equivalences

- Logical Equivalences are propositions that are, well, logically equivalent, i.e. they have the same values but have different forms
- list:

|         Name        |                           Equivalence                                 |
|:-------------------:|:--------------------------------------------------------------------: |
|    Identity laws    |                      p ∧ T ≡ p <br> p v F ≡ p                         |
|   Domination laws   |                       p v T ≡ T <br> p ∧ F ≡ F                        |
|   Idempotent laws   |                       p v p ≡ p <br> p ∧ p ≡ p                        |
| Double negation law |                            ¬(¬p) ≡ p                                  |
|   Commutative laws  |                   p v q ≡ q v p <br> p ∧ q ≡ q ∧ p                    |
|   Associative laws  |       (p v q) v r ≡ p v (q v r) <br> (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)        |
|  Distributive laws  | p v (q ∧ r) ≡ (p v q) ∧ (p v r) <br>  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r)  |
|   De Morgan's laws  |              ¬(p ∧ q) ≡ ¬p v ¬q <br> ¬(p v q) ≡ ¬p ∧ ¬q               |
|   Absorption laws   |                 p v (p ∧ q) ≡ p <br> p ∧ (p v q) ≡ p                  |
|    Negation laws    |                     p v ¬p ≡ T <br> p ∧ ¬p ≡ F                        |

- these can be used for proving or disproving the validity, contingency, or unsatisfiability of arguments

-I have a relatively hard time with remembering stuff like this, but I still understand

##Week 3

- We continued the lesson on Logical Equivalences

- we did some exercises on Logical Equivalences. Aside from some minor errors, I think I did relatively well.

- we also begun our lesson on quantifiers, predicates and first-order logic

- we use the symbol Ɐ to denote a universal quantifier -  that is, a proposition is true for all possible values of the domain; meanwhile, the symbol Ǝ denotes an existential quantifier, where a proposition is true as lone as at least one value of the domain is true for the given proposition

-We learned about the Rules of Inference as well, which can be used in proving first-order logic


|          Name          |   Rule of Inference       |            Tautology           |
|:---------------------: |:-------------------------:|:-----------------------------:|
|      Modus ponens      |       p<br>p→q<br>∴q      |        (p ∧ (p → q)) → q       |
|      Modus tollens     |     ¬q<br>p→q<br>∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |
| Hypothetical syllogism |     p→q<br>q→r<br>∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) |
|  Disjunctive syllogism |      p∨q<br>¬p<br>∴q      |       ((p ∨ q) ∧ ¬p) → q       |
|        Addition        |       p<br>∴p ∨ q         |           p → (p ∨ q)          |
|      Simplication      |       p ∧ q<br>∴p         |           (p ∧ q) → p          |
|       Conjunction      |      p<br>q<br>∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |
|       Resolution       | p ∨ q<br>¬p ∨ r<br>∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |

##Week 4

- This week we learned about the strategies used for proving

-first we learned about Direct Proof: to prove p → q, then first we prove p to be true, and q will follow suit.
-next up is proof by contraposition: Since the proposition is logically equivalent to its contrapositive, we can prove the validity of its contrapositive, and therefore the original statement itself.

-There is also proof by contradiction: we can prove the validity of a statement by disproving its negation.

-and finally there is proof by cases, where we prove that the possible cases for an arugment are true to prove the argument itself.


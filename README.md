# dismathportfolio---Gershom-Narag

##Week 1
- I was introduced to the subject DISMATH and professor Cabatuan
- We talked about propositions and proofs
- A proposition is any question answerable by a "True" or a "False", and a proof is a set of deductions that prove whether the proposition is true or not
- A list of logical connectives I learned:
| Logical Symbol  |  Logical Operator     | Shorthand | Formula                                       | Logical Expression            |
| :-------------: |:---------------------:|:---------:|:---------------------------------------------:|:-----------------------------:|
| ¬               | Negation              | not       | val(¬p) = 1 - val(p)                          | ¬p                            |
| ∧               | Conjunction           | and       | val(p ∧ q) = min(val(p), val(q))              | p ∧ q                         |
| v               | Disjunction           | or        | val(p v q) = max(val(p), val(q))              | p v q                         |
| ⊕               | Exclusive disjunction | xor       | if val(p) not equal val(q) = 1, otherwise 0   | p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q)  |
| →               | Conditional           | if, then  | if val(p) ≤ val(q) = 1, otherwise 0           | p → q ≡  ¬p v q               |
| ↔               | Biconditional         | iff       | if val(p) equals val(q) = 1, otherwise 0      | p ↔ q ≡ (p → q) ∧ (q → p)     |
-I found the lessons relatively easy to understand

##Week 2
- I was introduced to Logical Equivalences
- Logical Equivalences are propositions that are, well, logically equivalent, i.e. they have the same values but have different forms
- list:
|  **LAW**  |  **EQUIVALENCE**  |
| :------: | :-----------------------------:|
|  _Identity Laws_  |  p ∨ F ≡ p  ;;  p ∧ F ≡ p  |
|  _Domination Laws_  |  p ∨ T ≡ T  ;;  p ∧ F ≡ F  |
|  _Negation Laws_  |  p ∨ ¬p ≡ T  ;;  p ∧ ¬p ≡ F  |
|  _Double Negation Law_  |  ¬(¬p) ≡ p  |
|  _Idempotent Laws_  |  p ∨ p ≡ p  ;;  p ∧ p ≡ p  |
| _Distributive Laws_  |  p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (p ∨ r)  ;;  p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r)  |
|  _Commutative Laws_  |  p ∨ q ≡ q ∨ p  ;;  p ∧ q ≡ q ∧ p  |
|  _Associative Laws_  |  (p ∨ q) ∨ r ≡ p ∨ (q ∨ r)  ;;  (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)  |
|  _De Morgan's Laws_  |  ¬(p ∧ q) ≡ ¬p ∨ ¬q  ;;  ¬(p ∨ q) ≡ ¬p ∧ ¬q  |
|  _Absorption Laws_  |  p ∨ (p ∧ q) ≡ p  ;;  p ∧ (p ∨ q) ≡ p  |
- these can be used for proving or disproving the validity, contingency, or unsatisfiability of arguments
-I have a relatively hard time with remembering stuff like this, but I still understand

##Week 3
- We continued the lesson on Logical Equivalences
- we did some exercises on Logical Equivalences. Aside from some minor errors, I think I did relatively well.
- we also begun our lesson on quantifiers and predicates
- we use the symbol Ɐ to denote a universal quantifier -  that is, a proposition is true for all possible values of the domain; meanwhile, the symbol Ǝ denotes an existential quantifier, where a proposition is true as lone as at least one value of the domain is true for the given proposition

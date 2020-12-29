# Propositional Logic
### What is propositional logic?
	identifying a statement as  true or false
- must be clearly defined and factional

### Joining Propositions together

*Propositional Forms*
- Conjunction: $P \land Q$ T = when *P* and *Q* are **true**
- Disjunction: $P \lor Q$ T = when *P* or *Q* is **true**
- Negation: $\neg P$ T = when *P* is **false**
- Implication: $P \implies Q$ "If P then Q" $\equiv \neg$ P $\lor$Q
	- False only when P = T and Q = F
	- Contrapositive: $\neg$Q $\implies \neg$ P
	- Converse: Q $\implies$ P
	- Thus: P $\implies$ Q $\equiv \neg$ Q $\implies \neg$ P

**Law of the excluded middle** 
	For any proposition *P*, P or $\neg$P is true (but not both)
	- tautology: P $\lor  \neg P$ **ALWAYS TRUE**
	- contradiction: P $\land \neg P$ **ALWAYS FALSE**

Useful tool
- All possible values of propositional form = **truth table**

### Quantifiers
- *universal quantifier* = $\forall$
	- all
	- $\land$ comparisons
- *existential quantifier*= $\exists$
	- at least one
	- $\lor$ comparisons 

### Negation 
***De Morgan's Laws*** (negating conjunctions + disjunctions)
- $\neg (P \land Q) \equiv (\neg P \lor \neg Q)$ 
- $\neg (P \lor Q) \equiv (\neg P \land \neg Q)$

Concept:
- Flip as you go
	- $\neg (\forall x \exists y P(x,y)) \equiv \exists x \neg (\exists y P(x,y)) \equiv \exists x \forall y \neg P(x,y)$
- For conditional items
	- **at most**
		- use existential quantifiers and limit through implication
			- "there are at most three distinct integers satisfying P(x)"
				- $\exists x \exists y \exists z \forall d (P(d) \implies d = x \lor d = y \lor d = z$
				- OR $\forall x \forall y \forall z \forall v

*Example*
- U = {1, 2, 3, 4}
- P(x) = "$x^2 > 10$"
	- $\exists x \neg P(x) \equiv \neg (\forall xP(x))$
	- same truth value

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTYxNDU2MTAzMSwxMTQ3NDQwMjM0LC0yNT
g3ODIwMTMsMTY1NTE1MTQyLDIwMTkyNTA3NzBdfQ==
-->
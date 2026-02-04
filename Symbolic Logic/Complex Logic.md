---
aliases: []
---

2022-09-12 | 17:14
Status: #coursenote 

Class: [[CPSC121 Index|CPSC121]]
Subject: [[000 Symbolic Logic|Logic]]
Topics: [[Basic Logic]]


# Complex Logic
### Statements
A statement (or proposition) is a sentence that is *true **or** false* but not both
- A sentence must have a truth value to be a statement
##### Statement Variables
- A statement variable is a placeholder statement that has no truth value

### Compound Statements
A compound statement is a combination of multiple statements and logical connectives

### Statement Forms 
#### (Propositional forms)
*see [[Evaluating Statement Forms]]*
A statement form is an **expression** made up of statement variables (p, q, r) and logical connectives ($\lor, \land, \neg$)
- A statement form becomes a statement when actual statements are substituted for the statement variables
- Two statement forms may be equivalent
	- *see [[Logical Equivalence]]*

### Logical Connectives (Symbols)
see [[Truth Tables]] for more info
- **Negation** ($\neg$)
	- If p is true, ~p is false
- **Conjunction** ($\land$)
	- The statement p^q is true only when both p **and** q are true
- **Disjunction**
	- **Inclusive** or ($\lor$)
		- The statement pvq is true when p **and/or** q are true
	- **Exclusive** or (($p \lor q)\land \neg (p \land q)$)
		- p or q but not p and q
- **Conditional** ($\implies$)
	- The statement $p \implies q$ is false only when p is true and q is false

##### Interactions Between Logical Connectives
**Double negation property**:
	- $\neg(\neg p) \equiv p$
		- The statement forms $p$ and $\neg(\neg p)$ are **logically equivalent**
			- *see [[Logical Equivalence]]*

**De Morgan's Laws:**
(negations of and and or)
- The **negation** of the **conjunction** of two statements is equivalent to the disjunction of their negations
	- $\neg(p\land q) \equiv \neg p \lor \neg q$
	- ![](images/Pasted_image_20220912192521.png)
- The **negation** of the **disjunction** of two statements is equivalent to the **conjunction** of their negations
	- $\neg(p\lor q) \equiv \neg p \land \neg q$
- *Note: when applying De Margan's laws to language, be sure to have complete statements on both sides of and/or*


##### Order of Operations
- (Parantheses) overrites the normal order of operations
- $\neg$ first
	- e.g. $\neg p \lor q = (\neg p) \lor q$
- $\lor$ and $\land$ are considered equal in order, so paranetheses must be used to determine order
- $\implies$ and $\iff$ are done last
- **use brackets, dont rely on order of operations**

### Symbol Translation
###### English to Symbols
- but is used in place of $\land$ when the following clause is unexpected
- neither a nor b mean ~a and ~b

##### Inequalities to Symbols
- $x \leq a \equiv x \lt a \lor x = a$
- a<=x<=b ---- x>=a and x<=b
- $a \leq x \leq b \equiv a\leq x \land x\leq b$


## Relevant Links





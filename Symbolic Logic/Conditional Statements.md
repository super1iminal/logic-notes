---
aliases: []
---

2022-09-18 | 17:39
Status: #coursenote 

Class: [[CPSC121 Index|CPSC121]]
Subject: [[000 Symbolic Logic|Logic]]
Topics: [[Conditional Statements]] [[Logical Equivalence]] [[Simplifying Statement Forms]]

## If-then statements
# Conditional Statements
- Logical inference
	- one reasons *from* a hypothesis *to* a conclusion

### Basics
- Let $p$ and $q$ be statement variables
- $p \implies q$
	- The conditional of *q* by *p* is "If *p* then *q*" or "p implies q" or "*q* if *p*" or "*p* only if *q*"
	- *p* is the hypothesis (or antecedent) of the conditional and *q* is the conclusion (or consequent)
- $\implies$ is a connective
- Meaning is not quite the same as normal language


##### Deeper Explanation
- P takes place ONLY IF Q takes place
- Conclusion holds more value that the hypothesis, which is why:
		- converse and inverse are not true
		- if x then y is equivalent to x only if y
		- contrapositive makes sense
	- conclusion covers a larger scope
	- p is simply a meager 'attachment' to q
	- e.g. if you live in Los Angeles, then you live in California
		- inverse: if you don't live in Los Angeles, then you don't live in California
			- FALSE
		- converse: if you live in California, then you live in Los Angeles
			- FALSE
		- only if: you live in Los Angeles only if you live in California
			- TRUE
		- contrapositive: If you don't live in California, you don't live in Los Angeles

### Truth Table
- Since $p \implies q$ is a statement, p and q may be given truth values
- The only combination of truth values in which the conditional sentence would be false occurs when the **hypothesis** is ***true*** and the conclusion is ***false***
	- ![](images/Pasted_image_20220918174843.png)
		- the conclusion does not depend on the hypothesis being true
			- *i.e. "If I sleep in I'll be late for school"*
			- it is possible for me to be late for school for other reasons as well
	- Explanation
		- ![[Pasted image 20221001204207.png|500]]

### Interesting cases
##### Case One
$p \lor q \implies r \equiv (p\implies r) \land (q \implies r)$
- outcome is only false if (p or q) is true and r is false
	- if all are false, result is true
- in the first one that is clear
- in the second one, if one of the p or q is true and r is false, then one of the terms will be false, which will end if all around falseity

##### Equivalence
$\neg p \lor q \equiv p \implies q$
- Let $\neg p$ be **you get to work on time**
	- $p$ is therefore **you do not get to work on time**
- Let q be **you are fired**
- Therefore: 
	- $\neg p \lor q$: Get to work on time or you are fired
	- $p \implies q$: If you do not get to work on time you are fired

##### Negation
$\neg (p \implies q) \equiv p \land \neg q$
- Can be derived from case two
- Or:
- Let $p$ be **you get to work on time**
- Let $q$ be **you are not fired**
	- $\neg q$ is therefore **you are fired**
- Therefore:
	- $\neg (p \implies q)$: not (If you get to work on time, you are not fired)
	- $p \land \neg q$: You get to work on time and you are fired

##### Contrapositive
- Fundamental laws of logic
- A conditional **statement** is **logically equivalent** to its **contrapositive**
	- they will always have the same truth value
- $p \implies q \equiv \neg q \implies \neg p$
	- Some problems may be easier if the conditional statement is replaced with its cotnrapositive
- 

##### Converse
- The converse of $p \implies q$ is $q \implies p$
- They are only logically equivalent in a biconditional

##### Inverse
- The inverse of $p \implies q$ is $\neg p \implies \neg q$
- They are only logically equivalent in a biconditional

##### Converse and Inverse
- Are logically equivalent
- using contrapositive:
	- $\neg p \implies \neg q \equiv q \implies p$

****
## Other conditional statements
##### Only If
- p only if q means that p can take place only if q also takes place
	- that means that if not q, then not p
	- that means that if p, then q
- Another way to say this is that if p occurs, then q must also occur
- p only if q is equivalent to:
	- if not *q* then not *p*
	- if *p* then *q*
- Note that p only if q does not mean p if q

##### Biconditionals
- The biconditional of p and q is "p if, and only if, q"
	- denoted $\iff$
	- abbreviated iff
- The statement form is true if p and q are both true or both false
	- ![](images/Pasted_image_20220918184744.png)
- $p \iff q \equiv (p \implies q) \land (q \implies p)$![](images/Pasted_image_20220918185226.png)

****
## Necessary and Suffiecient Conditions
- *r* is a **sufficient** condition for *s*
	- if *r* then *s*
	- *r* **only if** s
	- conditional
		- r = is a square
		- s = is a quadrilateral
		- r is sufficient to know s
- *r* is a **necessary** condition for *s*
	- if *s* then *r*
	- if not *r* then not *s*
	- only if r then s
		- r = is a square
		- s = is a quadrilateral
		- s is a necessary condition for r
- *r* is a **necessary** and **sufficient** condition for *s*
	- *r* if, and only if, *s*


# Tips
- Cannot be or must be just mean that the output is false and true, respectively
- Always make a truth table to see what's possible
- "Assume that" means that the next conditional/biconditional
	- If you H/C, then did you C/H? means that you take H/C to be true

## Relevant Links





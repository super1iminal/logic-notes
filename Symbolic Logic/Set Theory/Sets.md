---
aliases: []
---

2022-11-11 | 00:06
Status: #coursenote 

Class: [[CPSC121 Index|CPSC121]]
Subject: [[000 Symbolic Logic|Logic]]
Topics: [[Set Theory]]

# Sets
- A set is a collection of definite and seperate objects
	- e.g. T = {k, p, m, h}
- The objects within the set are called **elements**


## Symbols
##### Basic
- Have truth values
- $a \in S$ means that *a* is an element of *S*
- $a \not\in S$ means that *a* is **not** an element of *S*

##### Equality
- These have truth values
- Only works between sets
- $A \subseteq B$ means that all elements in A are in B (**subset**)
	- $\forall x, x\in A \implies x \in B$
	- ![](images/Pasted_image_20221111001254.png)
- $A \nsubseteq B$ means that there are element(s) in A that are not in B
	- $\exists x, x \in A \land x \not\in B$
	- ![](images/Pasted_image_20221111001346.png)
- $A \subset B$ means that A is a **proper subset** of B, but there's at least one element in **B** that isn't in A
	- ![](images/Pasted_image_20221111001441.png)
- $A = B$ means that every element of A is in B and every element of B is in A

##### Logic
- $A \cup B$ means the union of A and B
	- This is the set of all elements that are in at least one of A or B
	- $A \cup B = \{x \in U | x \in A \lor x \in B\}$
	- ![](images/Pasted_image_20221111002012.png)
- $A \cap B$ means the intersection of A and B
	- This is the set of all elements that are commond to both A and B
	- $A \cap B = \{x \in U | x \in A \land x \in B\}$
	- ![](images/Pasted_image_20221111002112.png)
- $B - A$ means the difference of B minus A
	- This is the set of all elements that are in B and not in A
	- $B - A = \{x\in U | x \in B \land x \not\in A\}$
	- ![](images/Pasted_image_20221111032026.png)
- $A^c$ means the complement of C
	- The set of all elements in U that are not in A
	- $A^c = \{x\in U | x\not\in A\}$

## Common Sets
![](images/Pasted_image_20221111002546.png)


## The Empty Set
- A set with no elements
- **Denoted as** $\{\}$ or $\emptyset$
- Specifics: (assume A is any set)
	- The empty set is a subset of any set
		- $\forall A, \emptyset \subseteq A$ 
	- The union of A with the empty set is the set A
		- $\forall A, A \cup \emptyset = A$
	- The intersection of A with the empty set is the empty set
		- $\forall A, A \cap \emptyset = \emptyset$
	- For every element of the empty set, any property is true (Vacuous Truth)
		- $\forall x \in \emptyset, P(x)$
	- There is no element of the empty set for which property  P is true
		- $\neg \exists x \in \emptyset, P(x)$ 

## The Universal Set
- The set $U$ is the set containing **all elements** and of which **all other sets are subsets**

## The Power Set
- Given a set A, the power set of A, denoted $P(A)$, is the set of all subsets of A
	- There are A.size()! sets generated
- The power set of $U$ gives all sets that can exist


****
## Relevant Links





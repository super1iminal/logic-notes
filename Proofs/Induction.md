---
aliases: []
---

2022-12-06 | 18:49
Status: #coursenote 

Class: [[CPSC121 Index|CPSC121]]
Subject: [[000 Symbolic Logic|Logic]]
Topics: [[]]

# Induction
- Weak Mathematical Induction is used when you can substitute something in the next row with something in the previous row
- Strong Mathematical Induction is used when you can substitute something in the next biggest row with something or many things in the previous rows 

## Weak Induction
![](images/Pasted_image_20221206185237.png)
- This is why we need the base case (lowest possible case)

#### Tips
- For base case, don't assume equality


## Strong Induction

#### Tips
- Choose k that will result in k + 1 being able to use the full formula for the sequence
	- e.g. if the sequence's formula needs k-1 and k-2 and the sequence begins at 0, then choose k >= 1, since k + 1 >= 2, so we can use the full formula
	- ![](images/Pasted_image_20221206195744.png)
	- If the full formula is valid for all k, then simply use k >= lowest index in sequence
- Base cases are simply the first element or all elements that are given without a formula
****
## Relevant Links





---
title: Week D-3. Independence of random variables
date: 2018-12-20 03:21:03
tags: Independence, iid, sum of random variables
---
### Definition 
\\( X_1, \cdots, X_n\\) are **indepdendent**
iff for all \\(x_1, \cdots, x_n \in R\\) 
$$ f_{X_1, \cdots, X_n}(x_1, \cdots, x_n)= \Pi_{i=1}^n f_{X_i}(x_i).$$
iff for all \\(x_1, \cdots, x_n \in R\\) 
$$ F_{X_1, \cdots, X_n}(x_1, \cdots, x_n)= \Pi_{i=1}^n F_{X_i}(x_i).$$
### Implications   
* Probability $$ P(X_1 \in A_1, \cdots, X_n \in A_n)= \Pi_{i=1}^n P(X_i \in A_i).$$

* For any functions \\( g_i, \ i=1, \cdots, n\\) 
 $$E(\Pi_{i=1}^n g_i(X_i))= \Pi_{i=1}^n E( g_i(X_i)$$
provided  the expectations on the right-hand side exist.  

## Homework
Textbook: Sec. 8.6: 8.1, 8.5, 8.6, 8.9; Sec 9.7: 9.1, 9.3, 9.5, 9.10, 9.11, 9.12. Sec 10.5: 10.2, 10.6, 10.8, 10.16.

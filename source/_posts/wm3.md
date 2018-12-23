---
title: Week D-3. Independence of random variables
date: 2018-12-20 03:21:03
tags: Independence, iid, sum of random variables
---
![Independence](https://usercontent2.hubstatic.com/13814085_f520.jpg)
### Definition 
#### Independence
\\( X_1, \cdots, X_n\\) are **indepdendent**
iff for all \\(x_1, \cdots, x_n \in R\\) 
$$ f_{X_1, \cdots, X_n}(x_1, \cdots, x_n)= \Pi_{i=1}^n f_{X_i}(x_i).$$
iff for all \\(x_1, \cdots, x_n \in R\\) 
$$ F_{X_1, \cdots, X_n}(x_1, \cdots, x_n)= \Pi_{i=1}^n F_{X_i}(x_i).$$
#### iid (independently identically distributioned)
We say \\( X_1, \cdots, X_n \\) are **iid** if
1.  \\( X_1, \cdots, X_n\\) are indepdendent 
2. They have the same distribution, ie, \\( F_{i}(x)=F(x), f_{X_i}(x)=f(x)\\) for all i and where  \\( F_{i}(x),  f_{X_i}(x) \\) is the (marginal) cdf and pdf/pmf of \\(X_i \\) respectively.  

### Implications   
If  \\( X_1, \cdots, X_n\\) are indepdendent then
* Probability $$ P(X_1 \in A_1, \cdots, X_n \in A_n)= \Pi_{i=1}^n P(X_i \in A_i).$$

* For any functions \\( g_i, \ i=1, \cdots, n\\) 
 $$E(\Pi_{i=1}^n g_i(X_i))= \Pi_{i=1}^n E( g_i(X_i)$$
provided  the expectations on the right-hand side exist.  

* It is much easier to work out what \\( Y=g(X_1, \cdots, X_n )\\) is (ie, find out what its cdf or pdf/pmf or mgf is) or at least some snapshots such as expectation, variance or moments of \\( Y\\).

### Illustrations
* Let \\( X_1, \cdots, X_n \sim_{iid} Bernoulli(p), p \in (0,1)\\) then
$$ \sum_{i=1}^n X_i \sim Bin(n, p).$$ 
* Let \\( X_1, \cdots, X_n \sim_{iid} N(\mu, \sigma^2))\\) then
$$ \bar{X}=\frac{1}{n}\sum_{i=1}^n X_i \sim N(\mu, \frac{\sigma^2}{n}).$$ 
* Even when the distribution is only known to expectation and variance, we can still get some "pictures" of it. In the sense, 
 if \\( X_1, \cdots, X_n \sim_{iid}\\) with \\( \mu=E(X_i), \sigma^2=Var(X_i)\\) then
 $$ E(\bar{X})= \mu, Var(\bar{X})=\frac{\sigma^2}{n}.
$$
Note that this is consistent with our Bernoulli and normal cases. 

### Homework 7
Textbook: Sec. 8.6: 8.1, 8.5, 8.6, 8.9; Sec 9.7: 9.1, 9.3, 9.5, 9.10, 9.11, 9.12. Sec 10.5: 10.2, 10.6, 10.8, 10.16. To be discussed in class 12/27.

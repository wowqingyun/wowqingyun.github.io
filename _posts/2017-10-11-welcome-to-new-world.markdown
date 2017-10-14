---
layout: post
title:  "A Introduction to Steiner Tree"
date:   2017-10-14 10:15:01 +0800
categories: algo
---

In the Steiner Tree problem, the input is a graph G(V,E), with a set of terminals S <img src="http://latex.codecogs.com/gif.latex?\subseteq V" />, and a cost c(e). The target is to find a minimum-cost tree which connects all terminals.
The Steiner Tree problem is NP-Hard, and APX-Hard[1].


References:
[1] M.Bern and P.Plassmann. The Steiner problems with edge length 1 and 2. Infomation Processing Letters 32, 171-176, 1989. [link](https://dl.acm.org/citation.cfm?id=69689)
# <img src="http://latex.codecogs.com/gif.latex?" />
# <img src="http://latex.codecogs.com/gif.latex?\frac{\partial J}{\partial \theta_k^{(j)}}=\sum_{i:r(i,j)=1}{\big((\theta^{(j)})^Tx^{(i)}-y^{(i,j)}\big)x_k^{(i)}}+\lambda \theta_k^{(j)}" />



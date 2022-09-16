---
title: "Dual Basis for Polynomials"
published: false
---

Recall that a vector space $\mathcal{V}$ over a field $F$ has a corresponding dual space $\mathcal{V}^*$ that consists of all linear maps $\varphi: \mathcal{V} \to F$.

Consider that polynomials of degree $n$ form a vector space. The basis consists of the polynomials $\left \\{ x^i \right\\}_{i=1}^n$. For example, I can form any quadratic with a linear combination of $1$, $x$, and $x^2$. In general, then, an element of this vector space is an expression of the form $\sum\_{j=1}^n \alpha_j x^j$ with coefficients $\alpha_j$.

Here's the question: what's the dual basis?

We will need to find functions $\varphi_1, \dots, \varphi_n$ such that 

$$
\varphi_k\left(\sum_{j=1}^n \alpha_j x^j\right) = \alpha_k.
$$

See if you can assemble the operations. 

* Differentiation applied $k$ times will allow us to discard all terms higher than degree $k$.
* But we have to correct for the factors that come out of the monomial, so we have to divide by $k!$
* We also don't care about the variable $x$, so we want to evaluate it at 0.

That yields

$$
\varphi_k = \frac{D^k}{k!}\Bigg\vert_{x=0},
$$

which, if you'll notice, is nothing but the Maclaurin series! Neat.
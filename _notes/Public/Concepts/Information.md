---
title: "Information"
feed: hide
---

Information is [[Meaningness]] in a signal. How to properly and usefully define information is another question entirely. Aaron Sloman, for instance, [points out](https://www.cs.bham.ac.uk/research/projects/cogaff/misc/austen-info.html) the distinction between [[Shannon]] and Austen's view of information. 

## Shannon

In _A Mathematical Theory of Communication_, Claude Shannon creates information theory, but he uses 'information' in a specific context. 


For Shannon, the information $I(x)$ of event $x$ is given by


$$
I(x) = \log \left(\frac{1}{\Pr(x)}\right)
$$

Notice the following properties.
* Information is always non-negative, i.e. $\forall x: I(x) \geq 0$.
* Inevitable events have no information, i.e. $\Pr(x) = 1 \iff I(x) = 0$
* $I(x)$ monotonically increases as $\Pr(x)$ decreases.



## Reading List

* James Gleick's _Information_
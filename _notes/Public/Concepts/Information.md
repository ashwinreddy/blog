---
title: "Information"
feed: hide
---

In this wonderful little [post](https://www.cs.bham.ac.uk/research/projects/cogaff/misc/austen-info.html), Aaron Sloman distinguishes between two 
Claude Shannon's conception of information and Jane Austen's. 

## Shannon

In _A Mathematical Theory of Communication_, Claude Shannon creates information theory, but he uses 'information' in a specific context. 

> The fundamental problem of communication is that of reproducing at one point either exactly or approximately a message selected at another point. Frequently the messages have meaning; that is they refer to or are correlated according to some system with certain physical or conceptual entities. These semantic aspects of communication are irrelevant to the engineering problem. The significant aspect is that the actual message is one selected from a set of possible messages. The system must be designed to operate for each possible selection, not just the one which will actually be chosen since this is unknown at the time of design.

For Shannon, the information $I(x)$ of event $x$ is given by

$$
I(x) = \log \left(\frac{1}{\Pr(x)}\right)
$$


<!-- TODO -->

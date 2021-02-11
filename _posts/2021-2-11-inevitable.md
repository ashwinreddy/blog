---
title: "The Logic of Inevitability"
layout: post
tags: [philosophy]
---

> Dread it, run from it, destiny arrives all the same. - Thanos

Is the concept of fate or destiny rational?


---

Ten dominoes are lined up right next to each other, and the first is knocked over. What happens to them?

Our physical intuition makes the answer obvious: they fall down one by one, assuming every domino falls within knocking distance of the next. In fact, many of us would feel that this result is inevitable. The anticipation, brought on by knowing the result in advance, is part of the fun of watching domino effect videos online.

What's more, we can build a logical argument to justify this intuition:

When any of the dominoes is knocked over, it brings the subsequent domino down with it. Since the first one gets knocked down, they all get knocked down. This logic is the mathematical [principle of induction](https://www.wikiwand.com/en/Mathematical_induction).[^induction] The feeling of inevitability here can be described as a physical chain of events as well as a watertight argument.

[^induction]: This logic holds even if we had the distinctly non-physical situation of an infinite line of dominoes.

The more exciting version of the domino effect is a [Rube Goldberg machine](https://www.wikiwand.com/en/Rube_Goldberg_machine), but the principle is the same, fundamentally. 

How do we come to obtain this sense of inevitability? And what can it say about the way that we understand the world?

### The Hume-And Brain

Suppose you're sitting in your car in front of a traffic light, currently red. There's a cafe 100 feet away from you. At the exact moment the light turns green, a man exits the cafe. Here's a question: did the light cause this?

Most of us would say no. There's no reason to think that these events are associated.

Scottish philosopher David Hume suggests that we come to acquire our sense of causality through inductive reasoning. Inductive reasoning is a different concept than mathematical induction -- it just refers to the use of arguments that tell us that some things are more or less likely rather than what must logically follow, which is deductive reasoning. 

It may be possible, for example, that the man was waiting for a car to start moving before he steps outside the cafe. But since most of us have never been in or seen anyone in such an odd scenario, the chances are low that there is any causal connection.

Hume is saying that when we get this feeling that event _A_ causes event _B_, it is based on our previous experience that whenever _A_ has happened in the past, _B_ has always been sure to follow. Apart from that, we can't really locate causality in something concrete in the world. Hume's ideas challenge philosophical thinkers who supposed the **principle of sufficient reason** -- the idea that everything that has a cause. Causality, according to Hume, is some sort of Pavlovian mental anticipation, not a fundamental structure of the universe.

Hume makes a good point, but he's a little too reductive. He's missing something about the way that we, as humans, come to acquire that sense of anticipation, because sometimes we can _prove_ it to ourselves.

### Math is the science of inevitability

In _Godel, Escher, Bach_, Douglas Hofstadter presents two modes which we typically use to do math problems. The first mode is called Mechanical mode (M-mode) for short. M-mode is when you apply formulas or techniques that you understand well. It's called Mechanical because you're not doing all that much thinking in this mode -- it's just recognizing that you want to use a certain formula or shuffling some symbols mindlessly. The second mode is called Intelligent mode (I-mode) where you're trying to look for patterns or hypothesize about possible answers to a question at hand. 

One needs to be able to alternate between both modes to be an effective mathematician. For example, say you are computing the limit of some function $\lim_{x \to a} f(x)$. In the Intelligent mode, you have some guess for whether this limit exists or not, based on lots of past examples of limits. However, the proof will have to appeal to the Mechanical definition since the intuition is not rigorous.

The limit example is a little abstruse, so we can also consider another example.

### The Halting Problem


Algorithms are the lifeblood of computer science -- we're interested in finding out the answers to concrete problems through computation. Naturally, we want our algorithms to converge and halt on an answer (if your program tumbles on forever, you don't really have an answer, do you?).

Here's a question: is there some general procedure (that halts) to tell whether a program will halt or not? Alan Turing showed the answer is no. However, this does not mean that it is impossible for humans to read a piece of code and deduce whether it halts or not -- in fact, programmers do it all the time.

```python
i = 0
while i < 10:
    i += 1
    if i > 3:
        i -= 1
```

The snippet above won't halt, and you can tell quite easily. However, as the code grows more and more complicated, it takes more mental effort to be able to perform these deductions.

While you're in the process of figuring whether it halts or not, the answer is not obvious, otherwise, you wouldn't need to do all the work. You may have an inkling of the result, but it's just a gut feeling until you finish the proof. However, once you've found the answer, there's no way of going back to that feeling of ambiguity. The answer is _inevitable_ since you just worked out the metaphorical "domino steps" that led you to that conclusion.

### Power of Probability

This feeling of inevitability can even be attached to "random" events. This is the study of probability. By using the framework of Mechanical math formulas and Intelligent reasoning about chance events, we can show that certain kinds of random events follow patterns. 

If even uncertainty falls under the purview of rules, then we might reasonably wonder if _everything_ that has happened and will happen in the world is also inevitable.

## Free Will

In a classical mechanics class, you determine what happens to all sorts of physical contraptions like boxes on inclined planes, penguins sliding down spherical domes, or a system of complicated pulleys. Because you've never experienced these situations for yourself, Hume would say that you lack an understanding of causality here. But here's the catch: you can start by writing a few equations that capture the situation. Then, using the principles of physics, you can determine the outcome without actually needing to set up an experiment. And the answer will be correct, since you can verify it afterward.

This process is subtle, but it demonstrates that we can acquire a weaker sense of inevitability for physical situations without raw empirical experience through mathematical proofs.

Now we have all the ingredients that make us start to question our free will:

1. Humans are made up of atoms, the same stuff that makes up everything else.
2. We have models of the physical world that make predictions that can be experimentally verified.
3. These models are mathematical, meaning that they deal with inevitabilities.
4. Even so-called "randomness" falls under the purview of mathematical models. If you don't like this idea, that is fine -- the point is that the randomness is not part of any concept of "human conscience."

With all this in mind, we start to doubt what it would even mean for someone to freely choose to do something. A domino doesn't get to decide what causes its fall or what happens after its fall, so where would a human acquire this ability? If our axioms are right, then the future will depend only on the past and present and randomness. 

> Nowhere is there a space for human intervention.


## Conclusion

We know how limited human intelligence is, so it is clear that if we were smarter, then more things would seem inevitable to us. What's remarkable is that the universe has a structure that allows us to see that things will fall exactly the way that they will.

---

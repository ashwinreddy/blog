---
title: "You're Mostly Rational"
date: 2020-06-01
layout: post
description: "People fundamentally believe in reason without needing logic."
published: true
---

When studying decision making, we can choose to model _Homo sapiens_ or _Homo economicus_. Psychologists, advertisers, and behavioral economists all study _H. sapiens_, observing how actual humans make choices, regardless of how rational those choices seem. Philosophers, computer scientists, and mathematicians are more likely to focus on _H. economicus_, the imagined species of humans that are perfectly rational.

Even if we aren't perfectly rational, there's still value in aiming to think as clearly as possible. In this post, I'll propose a definition of rationality, and we'll see some of the interesting implications that arise.

## A Working Definition

Can a rock be rational? What about a plant? The answer is no. For rationality to make sense, we need to look at scenarios where a decision has to be made, and some choices are more logical than others. So rationality can only apply to a thing which has choices, and some choices are more logically justified because they lead to some result. 

An agent is something or someone that makes decisions. Humans are clearly agents, but so are many computer programs. A _rational_ agent uses reason to make decisions that lead it toward a goal (which is allowed to change over time). The agent is allowed a list of axioms, beliefs that it can take for granted. The goal and the axioms together comprise the agent's _values_.

In this construction we are free to ask the agent to explain its decision-making procedure. The explanation for its procedure would be something akin to a mathematical proof. Each step can cite the goal, invoke an axiom, or use the tools of logic and mathematics. 

Many animals would fit the definition if not for their inability to explain their decisions to us; they are thus uninteresting from the standpoint of rationality. Our definition does capture the notions we need to set up problems involving _H. economicus_. For example, we can imagine a prisoner's dilemma situation in which we pit two rational players against each other and then reason about how each player makes decisions. Or, when you notice that your friend is eating only leafy greens for lunch, you might ask them why. Checking the following conditions will allow you to confirm their decision to become a vegan is rational:

* Their goal is to give themselves enough energy to last the day.
* They want to cause as little suffering to animals as possible. 
* They argue that they can achieve both of their goals by being a vegan.

A couple notes here. It's worth noting that the world places limitations on what rational agents can do. Part of the agent's job is to understand these limitations if he or she is going to accomplish their goal. 

## Primacy of Values

The objects of highest importance in this framework are values as they determine what actions need to be taken. If we observe the kinds of actions people take, we can get a sense for what their values are. In this way, we can see that humans are mostly rational. We are continually performing actions, which tells us that there must be _some_ goal in mind.  As long as someone generally believes in the value(s) of logic, they are participating in rationality.

This should be a little discomforting. Let's say Irene believes that coconuts are mammals because they have hair and produce milk. Irene spends all of her time on online forums, ranting about how people fail to recognize her truth about coconuts. By most people's standards, Irene is behaving irrationally. I'm saying that Irene is rational, and she just has some very exceptional values. For some reason, this is a stance that matters to her. She's under no obligation to justify this if she takes it to be a value.

This may explain why debates between, for example, atheists and theists, often go nowhere. Each can justify their own thinking and actions under the banner of rationality, but the debate is a stalemate unless one of them changes their values.

By the time of each of us realizes the basic facts about the world, we already have some values. Some of those values come from raw empirical experience, some come from family, etc. As we experience more of life, we can adjust our values. The joys and difficulties of being human stem from the same fact: there's no preferred set of values. You're free to pick your values, but there are lots of values to choose from. The freedom to choose values can be terrifying.

## Hyperrationality

We usually picture a rational person as being unemotional. This idea too collapses under scrutiny. Consider Horatio and Alice. Horatio is a stoic man with no need for emotion while Alice has typical emotional responses. Alice values art that provokes compelling responses. Alice may go to the museum, watch movies, and read fiction. Horatio may do none of these things. They are both still rational. Alice simply values emotion in a way that Horatio does not. 

But there is something distinct about people like Horatio. Let's call him hyperrational, what the ordinary person thinks of as stereotypically rational. Hyperrationals are distinct in that they have values _about_ values. For example, they might have a value like "all my other values will be based, as much as possible, on empirical evidence" or "I don't believe in values which are inherited culturally and cannot be justified through other values."

The benefit of having hyperrational values is that it puts more emphasis on logic and reasoning. Consequently, it is easier to reason with such values. It is also easier to convince others to adopt one's beliefs. Finally, it means that one's thinking is very flexible; as the facts change, so too do one's beliefs.

## Rationality as Optimization

This section is just a cute aside more than anything. Let's say an agent's goal is to maximize its notion of utility $U_t(\cdot)$, a function that assigns each action a value indicating its preference for the resulting outcome. The subscript tells us that it is time-varying. Let's assume that axioms and limitations can be incorporated into the program for $U_t$ or can be formulated as a constraint , $f_i(x) \leq0$ on the agent's resources $x$. Then the agent's actions are given by

$$
a_t = \arg\max_a U_t(a), \qquad f_i(x) \leq 0
$$



For example, the vegan's utility could be inversely related with animal suffering and they are constrained by needing enough energy to exist. 

## Problem of Rationalization

Rationalization means justifying one's actions, and it has the connotation that such justification may not line up with the truth. The Problem of Rationalization is this: Two people with different values can take the same action in the same scenario. More broadly,

> For any action, there exists a number of values that could explain why the action was taken.

This poses a problem when we ask agents about their values. A malicious agent can make bad decisions using bad values and then justify it later by claiming to have more innocuous values. We call their bad values "ulterior motives."

However, it's just as likely that an agent, in good faith, could act similarly. Humans are prone to many cognitive biases. If we take an action that confuses us, we might then start to look for values that would explain our behavior.

## Irrational Agents

The Problem of Rationalization makes it even harder to pin down what makes somebody like Irene irrational. If we asked his parents what they mean by irrational, they might say something like "Irene's actions don't seem coordinated with any values." But as we've just seen, her parents _could_ justify her actions. If Irene's actions were completely random, they could argue her goal is just to maximize the entropy of her actions. What we mean by irrationality is unclear, but maybe it means something like, "Irene's values are very far removed from the typical person's," or "Irene's values change so rapidly as to have discontinuities."

## Why Rationality?

What does all of this mean, practically? It means that we should be very careful about retrospective justifications. Rationality is an engine for determining your actions when you're clear about your values.

$$
\text{Values} \longrightarrow \boxed{\text{Rationality}} \longrightarrow \text{Actions}
$$


Rationalization is the inverse process of generating values from actions. Rationalization is useful if you're unclear about your ideal values and want to know what values you implicitly hold. But, it is also possible to misuse rationalization to justify bad actions and convince other people of the same actions.


$$
\text{Values} \longleftarrow \boxed{\text{Rationalization}} \longleftarrow \text{Actions}
$$

Rationalization is tricky business. Actions are more concrete than values; observers will agree on the actions a person took more readily than the values of that person. If you are, indeed, unsure about your values, looking at your actions is a good place to start. From there, you may need to add, edit, or delete values. Then, adjust behavior accordingly. On the second point regarding justifying bad actions, I think this is a serious problem. For example, I'm wary of billionaires who might fund social projects to harbor good will if funding these projects also happens to allow them to keep more of their wealth.

We find ourselves in a world where we constantly have to make decisions. When humans were much closer to animals, it was sufficient to act in accordance with instincts and think no more of it. Today, however, we live in a much more complex and interconnected world, and each of our actions and inactions has consequences for ourselves and others. 

Rationality is a framework that will solve the problem of not knowing how to act if you can be clear about what your motivations are and what you want.[^f1] That's no easy task either; part of growing up is getting a sense for your motivations. But you can learn about the motivations of people from the past and present and you can experiment with values by iteratively reflecting and acting.

 

----------



[^f1]: Of course, many of our decisions depend on other people. Here, our decision making **must** assume that other people are rational. 

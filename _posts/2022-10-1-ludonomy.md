---
title: "Ludonomy"
---

Game
: A game $G$ consists of agent(s) in a play space $S$ trying to reach a goal $\Omega(G) \in S$ under certain constraints, which they follow for fun.

The definition is a paraphrase of Bernard Suits' "a game is the voluntary attempt to overcome unnecessary obstacles."[^suits] The four components are the players, the goals, constraints, and playfulness. Even an optimization problem can be a game.


\begin{aligned}
\min_{x \in X} f(x)\quad \text{s.t.}\quad \big\\{ g_i(x) \leqslant 0 \big\\}_{i=1}^n
\end{aligned}


It has a goal and constraints in a space, and we, the players, can try to solve it for fun. A very different game is making social conversation. In this game, interlocuters take turns saying things that keep them interested simply for its own sake. The difficult task is figuring out the rules. The philosopher Paul Grice has distilled them into four maxims:

1. Be informative.
2. Be truthful.
3. Be relevant.
4. Be clear and brief.

Like _Alice in Wonderland_, it's easier to see the rules in the transgression. When someone gives a knowingly obtuse answer to a question, lies about something banal, abruptly changes the conversation, or rambles incoherently, we are confused, annoyed, or taken aback. 

The optimization problem is highly formalized, while conversations are not. A formalized game is characterized by written rules, which articulate the objectives and rules and do so in a clear, unambiguous fashion. Formalized games put forward logical propositions as constraints and tend to involve deduction, where we figure out what those constraints entail. Then, it may be possible to solve it, which means to provide an agent with a ready-to-go plan that is optimal in some way. Solving games is the domain of the formal sciences -- game theory, mathematics, logic, and computer science, to name a few. 

The play space, formally represented, can be a [game tree](https://en.wikipedia.org/wiki/Game_tree) or graph, or a [normal-form matrix](https://en.wikipedia.org/wiki/Normal-form_game), or a [manifold](https://en.wikipedia.org/wiki/Manifold). When agents are playing, they are moving freely in this space, exploring or exploiting possibility. A solution acts like a map, singling out and charting paths that take us to a desired destination. But by definition, an agent following a planned solution is not playing. 

Life isn't, can't be a game. We don't always have agency, it doesn't come with a goal, we don't know all the constraints, and we're often not having fun. But if we can frame a part of it as a game, we'll have a manifold that shows us what's relevant.

Professor Yi Ma is thinking of intelligence in these terms. 

1. Discovering a simple manifold that extracts what's relevant for the game. (Information Theory)
2. Playing the game well and in an adaptive manner. (Game Theory)

---

[^suits]: He elaborates, "To play a game is to attempt to achieve a specific state of affairs [prelusory goal], using only means permitted by rules [lusory means], where the rules prohibit use of more efficient in favour of less efficient means [constitutive rules], and where the rules are accepted just because they make possible such activity [lusory attitude]."
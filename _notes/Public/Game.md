---
title: "Game"
feed: hide
---

Game
: A game $G$ is a [[System]] that consists of player(s) $A_1, \dots, A_n$ in a play space $S$, each trying to reach a goal $\Omega_{A_i}(G) \in S$ under certain constraints/rules/restrictions in $S$ that they follow for fun. The rules dictate what players can do as well when and where.[^suits]

The four components are the players, the goals, constraints, and [[Play]]. Examples of games include [[Conversation]]s and [[Optimization problem]]s. 

If a game is formalized, characterized by having written rules which articulate the objectives and rules in a clear, unambiguous fashion, then we may be able to solve it using [[Formal science]]. To solve the game means to provide the [[Computation]] of plan for an agent that is optimal in some way. Games with written rules are games of deductions because we must figure out what the constraints as logical propositions entail.

When the game is formalized, we can navigate its play space more easily. In [this computational essay](https://writings.stephenwolfram.com/2022/06/games-and-puzzles-as-multicomputational-systems/), Stephen Wolfram describes the structure of games in depth. Even simple games can have complex play spaces as he shows below.

![](https://content.wolfram.com/uploads/sites/43/2022/06/multiway-hero-final-2.png)

We might use [game trees](https://en.wikipedia.org/wiki/Game_tree) like the one below. The root is the starting node, and terminal nodes mark the game's end.

![](https://content.wolfram.com/uploads/sites/43/2022/06/sw060722tttimg2.png)

It may turn out to be a graph.

![](https://content.wolfram.com/uploads/sites/43/2022/06/sw060722tttimg21.png)

We can even take the games away from a discrete into a continuous structure and then think about them as a [[Manifold]]. But whatever the play space, players move freely, exploring or exploiting possibility.

If in the formalized game we are able to find a solution and if we hand this solution to agents, we have effectively given them a map that singles out paths toward the desired destination. But an agent following a planned solution is not playing.

Intelligence is related to being able to play [[Game]]s. 

---
[^suits]: The definition is a paraphrase of Bernard Suits' "a game is the voluntary attempt to overcome unnecessary obstacles." He elaborates, "To play a game is to attempt to achieve a specific state of affairs [prelusory goal], using only means permitted by rules [lusory means], where the rules prohibit use of more efficient in favour of less efficient means [constitutive rules], and where the rules are accepted just because they make possible such activity [lusory attitude]."
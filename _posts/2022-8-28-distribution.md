---
title: "Know Thy Distribution"
---

Jorge Luis Borges’ 1941 short story “The Library of Babel” explores a mythical library housing every possible book. It’s a work of pure genius precisely because the library contains more nonsense, falsehoods, and half-nonsense-half-falsehood than truth. To see what's going on, we must detour into the realm of probability, which becomes relevant once you notice a librarian might as well roll dice to generate a book's letters.

In probability, a distribution captures our assumptions about the generation of a dataset. Many ordinary processes are associated with a well-known distribution. For example, the binomial distribution models the number of heads in a sequence of coin flips. In simple cases like these, there is only one distribution we could reasonably apply. But when we don't know how exactly the data was generated, we must exercise caution. The wrong distribution gives way to confusion. Precisely this confusion is at play.

In Babel, a librarian is as likely to pick up one book as any other. Each letter is sampled uniformly from the alphabet and independently from the rest. Babel is full of gibberish because this distribution makes no distinction between letters, words, or any linguistic concept for that matter. 

In 1948, Claude Shannon, interested in the amount of information contained in writing, used a better model in which letters are sampled at the same rate as in printed English. That is, he samples _e_ roughly 11% of the time, and so on. He calls this first-order approximation, and the Babel distribution he calls zero-order approximation. At any rate, neither looks like English, so the second-order approximation samples a letter conditioned on the previous one. For example, if the previous letter was _q_, then we'd give a 99% chance to sampling a _u_ next. He tries third-order approximation, then switches to sampling words since these approximations give little of interest.

Ultimately, what these experiments, literary and technical, point to is that meaning is sampled, not from the space of language, but from authors. The only guarantor of a text's sensibility is the knowledge that the words were first sampled from a human.
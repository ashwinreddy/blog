---
title: "Achilles and the Tortoise"
---

Years ago, I heard about Achilles and the Tortoise, one of Zeno's paradoxes It's a cute bit of sophistry that is capable of tripping up a math major.

It goes like this: Achilles, swift of foot, and the Tortoise have a race. Achilles' speed is clearly greater than Tortoise's: $v_a > v_t$. Thus, in fairness, Tortoise gets a headstart of distance $h$. Who wins the race?

Zeno notes Achilles will take some time to catch up to the headstart line. In that time, the Tortoise will have moved some amount. Achilles will therefore have to catch up again, by which time the Tortoise will move again. Repeat _ad infinitum_. Therefore, Achilles can never catch up the tortoise. 

Your spidey sense is probably telling you something is wrong here. And there is. That's because Zeno doesn't know that an infinite sum can converge.

Let's take Richard Hamming's suggestion in the _The Art of Doing Science and Engineering_, to do a back-of-the-envelope calculation. Suppose $h = 10\,\mathrm{m}$, $v_a = 10 \frac{\mathrm{m}}{\mathrm{s}}$ and $v_t = 1\frac{\mathrm{m}}{\mathrm{s}}$.

It will take 1 second for Achilles to reach the 10 meter line where Tortoise started. However, in that time, Tortoise will have moved 1 meter, so Achilles will have to take 0.1 seconds to make up the distance. Tortoise moves 0.1 meters, which takes Achilles 0.01 seconds. The terms in this sum seem to decrease with a fixed ratio. To cut to the chase, the time that they reach each other $t_{eq}$ is given by
\\[
t_{eq} = \sum_{n=0}^\infty \frac{1}{10^n}.
\\]
Evaluating the geometric series, it takes $10/9 \approx 1.11$ seconds. Most of Achilles' catching up is done in that first second, but it becomes easier and easier to catch up afterward.


In general, the time it takes Achilles to catch up to the Tortoise when the Tortoise has had $t$ amount of time to move is given by $t\frac{v_t}{v_a}$. The initial time the Tortoise gets is $\frac{h}{v_a}$. Thus, we yield

\\[
t_{eq} = \frac{h}{v_a} \sum_{n=0}^\infty \left(\frac{v_t}{v_a}\right)^n = \frac{h}{v_a - v_t}.
\\]
Does this line up with normal intuition? We can write functions of position with time for each runner:
\begin{gather\*}
x_a(t) = v_a t, \\\\\
x_t(t) = h + v_t t.
\end{gather\*}
These imply that
\\[
t_{eq} = \frac{h}{v_a - v_t}.
\\]
Everything makes sense! Zeno is a fool! We should do more back-of-the-envelope calculations!
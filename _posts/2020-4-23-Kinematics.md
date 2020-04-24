---
layout: post
mathjax: true
title: "An Interesting Kinematics Problem"
categories: misc
---

I was review kinematics (for fun, of course) because its my favorite physics topic because of its extreme relevance to the real world. After all, who hasn't dropped something or pushed something off a table. I was grinding some problems and came across a really interesting one.

## Problem
A rabbit begins at the origin and a fox begins at (0, -a). At $t=0$, the rabbit begins moving with velocity $\boldsymbol{v}_r = v \boldsymbol{\hat{x}}$. Simultaneously, the fox begins running directly after the rabbit with speed $v$. Find the distance betwen the animals after a long time.

## Diagram
It's important to make a diagram in these kinds of problems, as you can easily get lost in the coordinates, directions, etc.
We therefore draw a diagram using Asymptote, mostly because it looks nice.
This diagram shows the system at some point in time $t$.



We also need to do some geometry (see next section).
Let $O$ be the origin.
Let $A$ be the position of the fox.
Let $B$ be the position of the rabbit.
Let $C$ be the intersection of the velocity vectors when extended outwards (this isn't really physically relevant, but we use it later).
Let $D$ be the interesection of the horizontal and vertical components of the fox's velocity.

## Some Geometry
We start with some angle-chasing. 
Let $\angle ABC \equiv \theta$.
By definition of components, $\overline{DB} \perp \overline{AD}$, so $\angle ABD = \theta - \frac{\pi}{2}$.
By complementary angles, $\angle BAD = \frac{\pi}{2} - \angle ABD = \pi - \theta $
Let $\alpha \equiv \pi - \theta$.
Let $r \equiv \overline{AB}$, 

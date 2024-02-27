---
title: Three-Body Problem (TV Series) - A Chinese Sci-fi Perspective
author: Li Shen
category: sci-fi
layout: post
---

*Imagine you're trying to hold a cup of coffee in one hand, this is a relatively straightforward task. You and the coffee have a simple relationship as long as you walk smoothly, the coffee stays in the cup in a predictable manner. Now imagine the introduction of a demon cat on your head, the situation becomes much more out of control. Each random movement from the cat warrants a new strategy to keep the coffee in the cup and in cases where the cat is asleep, you retain some stability but when it wakes up again, the chaos ensues..*

The idea behind the 2-body problem is a very elegant theory going all the way back to Newton. For two objects in 3-dimensional space, each object has a spatial coordinate $(x,y,z)$, 3 numbers that define its position in space. Additionally, we know how fast each object is moving, so another coordinate $(u,v,w)$ to know its velocity in space. This gives $3+3=6$ variables for a single object, and thus $12$ variables in total for a 2-body system.

To help us solve this system, we observe some interesting facts about this motion. Firstly, Newton noted in his book *Philosophiæ Naturalis Principia Mathematica* published in 1678 that 

> Mutationem motus proportionalem esse vi motrici impressae, et fieri secundum lineam rectam qua vis illa imprimitur.

 This roughly translates to "*The change of motion is proportional to the motive force impressed; and is made in the direction of the right line in which that force is impressed.*", known more famously as *Newton's Second Law*. In more mathematical terms, this means the force impressed $F$, is equal to the change in momentum $p$, which is the product of its mass $m$ and velocity $v$. Put together, this means that $F=dp/dt$. In a 2-body system with no external forces, i.e. $F=0$, then it must follow that the change in momentum $dp/dt=0$. This is the statement that linear momentum is conserved if no external forces are acting on the system. 

 Back to our 2-body system, the conservation of linear momentum ensures that the momentum of one body is equal and opposite to the momentum of the other ($p_1+p_2=0$, so $p_1=-p_2$). Hence, rather than tracking both objects with 12 variables (6 each), we can reduce our problem to only tracking 1 object since we can derive the motion of the second via the first. This means we can focus just on the relative motion of the 2-body, effectively halving the number of variables to 6 (3 for relative motion and 3 for relative velocity).

 Newton's second law has another consequence when applied to rotational motion. Suppose angular momentum $\mathbf{L}=\mathbf{r}\times\mathbf{p}$ is the vector product of position $\mathbf{r}$ and linear momentum $\mathbf{p}$
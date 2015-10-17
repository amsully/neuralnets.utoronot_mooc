# Why the learning works

Proof of perceptron learning

Consider the squared distant

![squared distance](../resources/squared_distance.gif)

between any feasible weight vector and current weight vector.


We want to show that each time it gets a training case wrong, it gets closer to every feasible weight vector.

**Hopeful Claim:**: Every time the perceptron makes a mistake, the learning algorithm moves the current weight vector closer to all feasible weight vectors.

This claim may not always hold.

SO. We consider a 'generously feasible' weight vectors that lies within the feasible region by a margin at least as great as the length of the input vector that defines each constraint plane.


## Informal Sketch of Proof of Convergence

- Each time the perceptron makes a mistake, the current weight vector moves to decrease its squared distance from every weight vector in the 'generously feasible' region.
- The squared distance decreases by at least the squared length of the input vector.
- After a finite number of mistakes, the weight  vector must lie in the feasible region, if this region exists.







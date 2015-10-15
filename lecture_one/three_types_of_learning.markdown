
# Types of learning task

- Supervised Learning
	- Lear to predict an output given an input

- Reinforcement
	- Learn to select max payoff

- Unsupervised Learning
	- Learn something new

### Two types of supervised learning

- Each training case consists of an input vector x and a target output t

- Regression: the target output is a real number or a whole vector

How supervised learning typically works

- We start bychoosing a model-class: y = f(x; W)
	- A model class, f is a way of using numerical parameters, W, to map each input vector x, into a predicted output y.

- Learning usually means adjusting parameters to reduce discrepancy between the target output t, on each training case and the actual output, y, produced by the model

For regression

1/2 (y - t)^2 is often a sensible measure of discrepancy

## Reinforcement Learning

- The goal in selecting each action is to maximize the expected sum of the future rewards
- We usually use a discount factor for delayed rewards so that we don't have to look too far into the future

- Reinforcement learning is difficult
	- The rewards are delayed so its hard to know where we went wrong 
	
- NOT COVERED IN COURSE

## Unsupervised Learning

- 40 years, unsupervised learning was largely ignored by the machine learning community
- One major aim is to create an internal representation of the input that is useful for subsequent supervised or reinforcement learning
- Compute distance to a surface by using the disparity between two images. But you dont want to learn repeatedly

- Provide compact, low dimensional representaiton of the input
	- High dimensional inputs live in low-dimensional manifold
	- move from many pixel to degree of manifold
	- Principal Component Analysis is a widely used linear method for finding a low dimensional represntation

- It provides an economical high-dimensional representation of the input of learned feature
	- Binary features are conomical
	- So are real-vealued features that are nearly all zero

- It finds sensible clusters in the input
	- Very sparse code in which only one feature of a problem












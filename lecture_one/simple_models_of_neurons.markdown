
# Simple models of Neurons

Idealized neurons
- Model things we have to idealize them
	- removes complicated details that are not essential for understanding the main principles
	- It allows us to apply mathematics and to make analogies to other, familiar systems
	- Once we understand the basic principles, its easy to add complexity to make model for faithful

## Linear Neurons

Simple but computationally limited

![alt tag](../resources/lecture_one_linear.gif)


y is the output, of b, bias, plus the sum over all input connection of the ith input times the weight on the ith input
- results in a linear graph

- bias + weighted values we get a straight line

## Binary Threshold Neuronsvalue

- influenced by Von Neumann

- First compute weighted sum of inputs
- Send out a fixed spike of activity if the weighted sum exceeds a threshold
- each spike is the truth value of a proposition and each neuron combines truth values to compute the truth value of another proposition!

- Graph has 0,1 input output

Writing equation in two equivalent ways

![alt tag](../resources/lecture_one_binarythresholdneurons_one.gif)

![alt tag](../resources/lecture_one_binarythresholdneurons_two.gif)

Equivalence is threshold is negative of the bias..

## Rectified Linear Neurons

- The compute a linear weighted sum of their inputs
- The output is a non-linear function of the total input

We get convenience of binary threshold when 0, and linear when z > 0

![alt tag](../resources/lecture_one_rectifiedlinearneurons.gif)

## Sigmoid Neurons

- These give a real-valued output that is a smooth and bounded function of their total input
	- Typically use logistic function

- Look at limite..
- Smooth derivatives .. 
![alt tag](../resources/lecture_one_sigmoidneurons.gif)



## Stochastic binary neurons

- Same equations as logistic units but treat output of logistic as the probability of producing a spike in a short time window.

- We can do a similar trick for rectified linear units - the output is treated as the poisson rate for spike

equation is same as above only p(s=1) = 1/1+e^(-z)
































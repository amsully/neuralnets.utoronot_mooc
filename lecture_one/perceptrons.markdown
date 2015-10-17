# Perceptrons: The First Generation of Neural Networks

Studied in the 1960s, but fell into disfavor because show they were restricted.

The standard paradugm for statistical pattern recognition

1. Convert raw input vector into a vector of feature activations
2. Learn how to weight each of the feature activations to get a single scalar quantity.
3. If this quantity is above some threshold, decide that the input vector is a positive example of a target class.

The standard perceptron architecture

```
[] [] [] []  input units
->	     hand-coded weights or programs
[][][][][]   feature units
->	     learned weights
[]	     decision unit
```

'Principles of Neurodynamics' - Frank Rosenblatt Early 1960s

1969 - Minsky and Papert published 'Perceptrons;

	- Showed limitations
	- Many people thought these limitations applied to all neural network models

## Binary Threshold Neurons (Decision units)

	- First compute a weighted sum of the inputs from the inputs from other neurons (plus a bias)
	- Output one if the weighted sum exceeds 0

![binary threshold neuron equation](../resources/binary_threshold_neurons_equation.gif)

How to learn biases using the same rule as we use for learning weights.

- A threshold is equivalent to having a negative bias
- Goal: Avoid having to figure out a separate learning rule for the bias
	- A bias is equal to an extra input line that has an activity of 1
	- This allows us to treat it as a weight

### The perceptron convergence procedure: Training binary output neurons as classifiers

- Add an extra component with value 1 to each input vector.
	- This bias will be -(threshold)
	- Allows us to forget threshold
- PIck training cases using any policy that enures that every training case will keep getting picked
	- If the output unit is correct, leave its weights alone
	- Else if the output unit incorrectly outputs a zero
		- Add input vector to the weight vector
	- Else if the output unit incorrectly outputs a one
		- Subtract the input vector from the weight vector

This is guaranteed to find a set of weights that get the right answer for all training cases (if any such set exists)

Difficult issues is using the appropriate features. A lot of the work is finding those features we need to learn
























# Recognize handwritten shapes

- Consider a neural network with two layers of neurons
	- Neurons in the top layer represent known shapes
	- Neurons in the bottom layer represent pixel intensities
- A pixel gets to vote if it has ink on it
	- Each inked pixel can vote for several different shapes
- Shape that gets the most votes wins

**How to display the weights?**

- Given each outputs units its own map of the input image and display the weightt coming from each pixel in the location of that pixel in the map

- Use a black or white blob with the area representing the magnitud of the weight and color representing the sign

- Show the network an image and increment the weights from active pixels to the correct class
- Decrement weights from active pixels to whatever class the network guesses

- The winner is the template that has the biggest overlap with the ink
- The ways in which digit s vary are much too complicated to be captured by simple template matches of whole shape
	- We must extract features










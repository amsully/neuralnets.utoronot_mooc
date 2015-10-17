# Neural Network Architectures

## Feed Forward Neural Networks

- Most common
- First layer is the input, last is output
- If there is more than one hidden layer, we call them 'deep' neural networks

They compute a series of transformations that change the similarities between cases.

In speech recognition we want same thing by different speakers to be more similar.

- The activities of the neurons in each layer are a non-linear function of the activities in the layer below.

## Recurrent Networks

- These have directed cycles in their connection graph
	- You can sometimes get back to neuron you started at

- Complicated dynamics
	- There is a lot of interest at present in finding ways of training recurrent nets

Recurrent nets with multiple hidden layers are just a special case that has some of the hidden -> hidden connections missing

### Recurrent neural networks for modeling sequences

- Connections with hidden units... 

- Each time step determines unit of next time step.
- Except they use same weights at every time slice and they get inputs at every time slice

- They have the ability to remember information in their hiden state for a long time.
	- Very hard to train them to use this potential
	- 2011 paper trained on 1/2 billion wiki character for char sequences
	- 2011 Ily Sutskever
		- It generates by predicting the probability distribution for the next character and then sampling a character from this distribution!

## Symmetrically Connected Networks

- Connections between units are symmetrical (same weight in both directions)
	- Much easier to analyze then recurrent
	- John Hopfield 
	- More restricted - obey an energy function (cannot model cycles)

Symmetrically connected nets without hidden units are called **hopfield nets**











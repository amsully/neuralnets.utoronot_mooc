

# Intro

- A log of genetics is done on fruit flies
	- They are convenient because they breed fast
	- We know a lot about them

- The MNIST database of hand-written digits is the machine learning equivalent of fruit flies
	- They are publicly available


- Beyond MNIST: The ImageNet task
	- 1000 different object classes in 1.3 million high res training images from the web
	- Best system in 2010 got 47% for top 10, 25& for top 5
	- A very deep neural network gets less than 40% error now

- Speech recognition task:
	- Sever stages
		- Pre-processing: Convert sound wave into a vector coefficients: extract a new vector about every 10 ms
		- The acoustic model: Use a few adjacent vectors of acoustic coefficients to place bets on which part of which phoneme is being psoken
		- Decoding: Find the sequence of bets that does the best job of fitting the acoustic data and also fitting a model of the kinds of things people say

Phone Recognition on TIMIT Benchmark

- After standard post-processing using a bi-phone model, a deep net with 8 layers get 20.7% error vs the best of 24% error

- Microsoft showed that neural network work better, IBM showed its highly tuned system at 18.8% ... Googl etested on 5,8070 hours and got a 12.3% error rate  ... Latest android uses a Deep Neural Network

## What are Neural Networks?

Overview of neural networks

- Reasons to study neural computation
	- To understand how the brain actually works
		- We need to simulate it
	- To understand a style of parallel computation inspired by neurons and their adaptive connections
		- Very different from sequential computaiton
			- Good for things that brains are good at (vision)		
			- Bad at multiplications
	- Solve practical problems by using novel learning algorithms inspired by the brain

**Cortical Neuron**

- One axon that branches
- Dendritic tree that collect input from other neurons
- Axons typically contact dendritic trees at synapses
	- A spike of activity in the axon causes a charge to be injected in the post synatic neuron

**Synapses**

- When a spike of activity travels along an axon and arraives at a synapse it causes vesicles of transmitter chemical to be released
	- Trnasmetter
- Transmitter diffuses chemical

Effectiveness of synapse can be changed
	- number of vesicles of transmitter
	- vary number of receptor molecules

- Synapses are slow but they have advantages

How it works:

Each neuron receives input from other neurons

- few neurons also connect to receptors
- Cortical neirons use spikes to communicate

- The effect of each input line on the neuron is controlled by a synaptic weight
	- weight can be +  - 
- The synaptic weights adapt so that the whole network learns to perform useful computations
	- Recognizing object


Modularity of brain

- Different bits of the cortex do differn tthings
- Cortex looks pretty much the same all over
- Cortex is made of general purpose stuff that has the ability to turn into special purpose hardware in response to experience
	- Ferrets --- if you reroute auditory cortex with visual input it will be taylored to visual system
	- This gives rapid parallel computation plus flexibility
 

























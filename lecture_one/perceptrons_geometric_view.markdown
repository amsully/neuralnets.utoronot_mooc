# A Geometric View of Perceptrons

Lecture 2c

(Mathematically 'intense')

Weight-Space

- This space has one dimension per weight
- A point in the space represents a particular setting of all the weights
- Assuming that we have eliminated the threshold, each training case can be represented as a hyperplane through the origin
	- The weights must lie on one side of this hyperplane to get the correct answer

Each training case defines a plane and this plane goes through the origin and is perpendicular to the input vector

```
Amazing artist
good weight vector
		    \ | <- input vector 
    		     \|  <good side>
		----------------  <--- Hyper plane
		     /   <bad side>
   		    /
bad weight vector
```

Above we see that the angle between the good weight vector and input vector will be less than 90 degrees and the scalar product will be positive

The angle between the input vector and bad weight will be greater than 90 and the scalar product will be negative.

Due to result above, all vectors on one side of the hyper plane are correct and those on the other side are wrong

Now if we imagine many hyperplanes jutting out from the origin we want to find a point that is on the good side of all of these planes. It could be that this point doesn't exist

- If there are any weight vectors that works for all cases, they lie in a hyper cone with its apex at the origin.
	- The average of two good weight vectors is a good weight vectors
	- Convex problem



# What Perceptrons Can't Do

### The limitations of Perceptrons

- If you are allowed to choose the features by hand and if you use enough features, you can do almost anything.
	- For binary input vectors, we can have a separate feature unit for each of the exponentially many binary vectors so we can make any possoble discrimination on binary input vectors.
	- This type of table look-up won't generalize
- One you determine hand-coded features, very limited in what they can do.

## What binary threshold neurons cannot do

- A binary threshold output unit cannot even tell if two single bit features are the same!

Positive cases (same): (1,1) -> 1; (0,0) -> 1

Negative Cases (different): (1,0) -> 0; (0,1) -> 0

The four input-output pairs give for inequalities that are impossible to satisfy






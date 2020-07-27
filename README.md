# perceptron

Implemented one perceptron for each letter, for a total of 26. Each perceptron learns to output 1 for its assigned letter and 0 for all other letters. It begins with weights and biases initialized to random values (rather than zero) for each perceptron, and apply the perceptron learning algorithm until all items in the training set are classified correctly or until it becomes clear that the weights will not converge.
As each item in the training set is classified by each perceptron, it records whether the output was correct or not. At the end of each pass through the training set by a perceptron, it also records the error rate (number of misclassified items) of that perceptron for that epoch.

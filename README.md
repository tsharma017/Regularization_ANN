# Regularization_ANN
Regularization in General:

Regularization is like adding a "penalty" to your neural network to prevent it from becoming too complex and overfitting (memorizing the training data instead of learning patterns). It encourages the model to keep its weights (parameters) small and simple.

 L1 Regularization:

Think of L1 as a strict teacher who says, "Don’t use too many features! Focus on the most important ones."
It adds a penalty equal to the absolute value of the weights.
Effect: It pushes some weights to exactly zero, effectively removing less important features (sparse model).

L2 Regularization:

Think of L2 as a gentle coach who says, "It’s okay to use many features, but don’t let any single feature dominate too much."
It adds a penalty equal to the square of the weights.
Effect: It keeps all weights small but rarely pushes them to zero (dense model).

 L1 + L2 Regularization (Elastic Net):

Think of this as a combination of the strict teacher and the gentle coach.
It adds penalties from both L1 and L2.
Effect: It balances between removing unimportant features (L1) and keeping the remaining weights small (L2).

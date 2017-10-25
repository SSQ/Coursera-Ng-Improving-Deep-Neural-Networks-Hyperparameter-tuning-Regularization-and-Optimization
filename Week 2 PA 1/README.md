# Optimization

# Goal
- Understand the intuition between Adam and RMS prop

- Recognize the importance of mini-batch gradient descent

- Learn the effects of momentum on the overall performance of your model

# File Description
- `.ipynb` file is the solution of Week 2 program assignment 1
  - Optimization+methods.ipynb
- `.html` file is the html version of `.ipynb` file.
  - Optimization+methods.html
- `.py` file
  - Optimization+methods.py
- file
  - Optimization+methods.md
  
# Snapshot
- computer view. open .html file via brower for quick look.
- **Recommend** brower view. Optimization+methods.md


# Implementation
- Gradient Descent
- Mini-Batch Gradient descent
- Momentum
- Adam
- Model with different optimization algorithms
  - Mini-batch Gradient descent
  - Mini-batch gradient descent with momentum
  - Mini-batch with Adam mode

# What you should remember from this notebook:
## Gradient Descent
- The difference between gradient descent, mini-batch gradient descent and stochastic gradient descent is the number of examples you use to perform one update step.
- You have to tune a learning rate hyperparameter  α .
- With a well-turned mini-batch size, usually it outperforms either gradient descent or stochastic gradient descent (particularly when the training set is large).
## Mini-Batch Gradient descent
- Shuffling and Partitioning are the two steps required to build mini-batches
- Powers of two are often chosen to be the mini-batch size, e.g., 16, 32, 64, 128.
## Momentum
- Momentum takes past gradients into account to smooth out the steps of gradient descent. It can be applied with batch gradient descent, mini-batch gradient descent or stochastic gradient descent.
- You have to tune a momentum hyperparameter  ββ  and a learning rate  αα .
# Conclusion
optimization method	| accuracy | cost shape
--|--|--
Gradient descent |	79.7%	| oscillations
Momentum	| 79.7% |	oscillations
Adam	| 94%	| smoother

# Reference
Adam paper: https://arxiv.org/pdf/1412.6980.pdf


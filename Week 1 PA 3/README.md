# Gradient Checking

# Goal
- Implement gradient checking from scratch.

- Understand how to use the difference formula to check your backpropagation implementation.

- Recognize that your backpropagation algorithm should give you similar results as the ones you got by computing the difference formula.

- Learn how to identify which parameter's gradient was computed incorrectly.

# File Description
- `.ipynb` file is the solution of Week 1 program assignment 3
  - Gradient+Checking.ipynb
- `.html` file is the html version of `.ipynb` file.
  - Gradient+Checking.html
- file
  - Gradient+Checking.md
  
# Snapshot
- computer view. open .html file via brower for quick look.
- **Recommend** brower view. Initialization.md


# Implementation
- 1-dimensional gradient checking
- N-dimensional gradient checking

# What you should remember from this notebook:
- Gradient checking verifies closeness between the gradients from backpropagation and the numerical approximation of the gradient (computed using forward propagation).
- Gradient checking is slow, so we don't run it in every iteration of training. You would usually run it only to make sure your code is correct, then turn it off and use backprop for the actual learning process.


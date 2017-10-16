# Initialization

# Goal
- see how different initializations lead to different results
- Understand that different regularization methods that could help your model.

# File Description
- `.ipynb` file is the solution of Week 1 program assignment 1
  - Initialization.ipynb
- `.html` file is the html version of `.ipynb` file.
  - Initialization.html
- file
  - Initialization.md
  
# Snapshot
- computer view. open .html file via brower for quick look.
- **Recommend** brower view. Initialization.md


# Implementation
- Zeros initialization -- setting initialization = "zeros" in the input argument.
- Random initialization -- setting initialization = "random" in the input argument. This initializes the weights to large random values.
- He initialization -- setting initialization = "he" in the input argument. This initializes the weights to random values scaled according to a paper by He et al., 2015.

# What you should remember from this notebook:
- Different initializations lead to different results
- Random initialization is used to break symmetry and make sure different hidden units can learn different things
- Don't intialize to values that are too large
- He initialization works well for networks with ReLU activations.

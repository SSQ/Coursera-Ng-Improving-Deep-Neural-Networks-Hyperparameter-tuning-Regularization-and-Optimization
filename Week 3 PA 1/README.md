# Tensorflow

# Goal
- Initialize variables
- Start your own session
- Train algorithms
- Implement a Neural Network
# File Description
- `.ipynb` file is the solution of Week 3 program assignment 1
  - Tensorflow+Tutorial.ipynb
- `.html` file is the html version of `.ipynb` file.
  - Tensorflow+Tutorial.html
- `.py` file
  - Tensorflow+Tutorial.py
- file
  - Tensorflow+Tutorial.md
  
# Snapshot
- computer view. open .html file via brower for quick look.
- **Recommend** brower view. Tensorflow+Tutorial.md


# Implementation
- Exploring the Tensorflow Library
  - Linear function
  - Computing the sigmoid
  - Computing the Cost
  - Using One Hot encodings
  - Initialize with zeros and ones
- Building your first neural network in tensorflow
  - Problem statement: SIGNS Dataset
  - Create placeholders
  - Initializing the parameters
  - Forward propagation in tensorflow
  - Compute cost
  - Backward propagation & parameter updates
  - Building the model


# What you should remember from this notebook:
## Writing and running programs in TensorFlow has the following steps:
1. Create Tensors (variables) that are not yet executed/evaluated.
1. Write operations between those Tensors.
1. Initialize your Tensors.
1. Create a Session.
1. Run the Session. This will run the operations you'd written above.
## To summarize, you how know how to:
1. Create placeholders
1. Specify the computation graph corresponding to operations you want to compute
1. Create the session
1. Run the session, using a feed dictionary if necessary to specify placeholder variables' values.
## What you should remember from this notebook:
- Tensorflow is a programming framework used in deep learning
- The two main object classes in tensorflow are Tensors and Operators.
- When you code in tensorflow you have to take the following steps:
  - Create a graph containing Tensors (Variables, Placeholders ...) and Operations (tf.matmul, tf.add, ...)
  - Create a session
  - Initialize the session
  - Run the session to execute the graph
- You can execute the graph multiple times as you've seen in model()
- The backpropagation and optimization is automatically done when running the session on the "optimizer" object.


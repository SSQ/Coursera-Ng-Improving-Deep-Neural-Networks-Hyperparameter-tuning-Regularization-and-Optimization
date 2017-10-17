# Regularization

# Goal
- Understand that different regularization methods that could help your model.

- Implement dropout and see it work on data.

- Recognize that a model without regularization gives you a better accuracy on the training set but nor necessarily on the test set.

- Understand that you could use both dropout and regularization on your model.

# File Description
- `.ipynb` file is the solution of Week 1 program assignment 2
  - Regularization.ipynb
- `.html` file is the html version of `.ipynb` file.
  - Regularization.html
- file
  - Regularization.md
  
# Snapshot
- computer view. open .html file via brower for quick look.
- **Recommend** brower view. Regularization.md


# Implementation
- Non-regularized model
- L2 Regularization
- Dropout
  - Forward propagation with dropout
  - Backward propagation with dropout
  
# Conclusion
## What you should remember -- the implications of L2-regularization on:
- The cost computation:
  - A regularization term is added to the cost
- The backpropagation function:
  - There are extra terms in the gradients with respect to weight matrices
- Weights end up smaller ("weight decay"):
  - Weights are pushed to smaller values.
  
## What you should remember about dropout:
- Dropout is a regularization technique.
- You only use dropout during training. Don't use dropout (randomly eliminate nodes) during test time.
- Apply dropout both during forward and backward propagation.
- During training time, divide each dropout layer by keep_prob to keep the same expected value for the activations. For example, if keep_prob is 0.5, then we will on average shut down half the nodes, so the output will be scaled by 0.5 since only the remaining half are contributing to the solution. Dividing by 0.5 is equivalent to multiplying by 2. Hence, the output now has the same expected value. You can check that this works even when keep_prob is other values than 0.5.
  
## What we want you to remember from this notebook:
- Regularization will help you reduce overfitting.
- Regularization will drive your weights to lower values.
- L2 regularization and Dropout are two very effective regularization techniques.  

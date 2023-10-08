# Regularized Logistic Regression - Gradient Descent

## Files on the Repository
`Regularized LR.ipynb` - MAIN file.

`mnist_2_vs_9.gz` - MNIST Dataset for digits 2 & 9.

## Objectives

  * Build a Logistic Regression classifier based on Gradient Descent.
  * Apply L2/Ridge Regularization to deal with Overfitting.
  * Find optimal values for parameters:
    - Learning rate, for which a significant decrease in Training loss is observed.
    - Lambda, which performs better with unseen data *(validation set)*, at the same time do not underfit train data.
  * Try to find a sweet spot by using different set of values for the parameters on the development *(validation)* set.
  * Construct plots for Accuracy & Cross-Entropy Loss vs Step-size on training and validation sets.
  * After fixing the optimal parameters, predict test data and notedown test loss.

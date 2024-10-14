# Optimizers 
1) Description:
    The project evaluates various optimizers for binary classification using logistic regression on a subset of the MNIST dataset (class 0 vs. class 1).

2) Key Features:
  L1 Regularization:
    Lambda = 1: 99.96% accuracy
    Lambda = 1000: 99.53% accuracy
  Mini-Batch Gradient Descent:
    Batch size = 10: 98.50% accuracy
    Batch size = 50: 99.29% accuracy
    Batch size = 100: 99.64% accuracy
  RMSProp Optimizer: 99.76% accuracy
    Adam Optimizer: 99.84% accuracy
  
3) Conclusion:
Regularization helps prevent overfitting.
Smaller batch sizes improve accuracy.
RMSProp and Adam optimizers adaptively adjust learning rates, leading to faster convergence and higher accuracy.

4) Programming Tools:
   Python, NumPy ,Keras and Scikit-learn.

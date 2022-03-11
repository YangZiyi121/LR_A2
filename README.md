This is the solution of question 2 of CS229 homework2
In this experiment, I used logistic regression to perform {0,1} classification on *digitspreprocess.npy* data. 
For parameter setting, lambda (factor of regular term) are set to 0, 0.0001, 0.001, 0.005, 0.01, 0.05, 0.1 respectively with fixed learning rate eta = 0.01. The maximum interations is 10^4 and the training is terminated if the magnitude of gradient if less than 10^-5.
For the camparision, the error rates of different lambdas are compared.
The file description is shown below.

File Name|Description
:----:|:----:
LogisticRegression.ipynb|Use logistic regression for training and compare error rate on testing set
digitsoreprocess.npy|The processed dataset provided for training and testing


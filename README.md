# Linear-Regression-ML-model
this is linear regression for ml model. that i make for python 


Explain what is in the code:

learning_rate and no_of_iteration is both for to get global minimum in graf of loss function and parameter.
learning rate usually use 0.01 or 0.1 while no of iteration use 100 or 1000.
for no of iteration is so that it will repeat again until it hit the number we set.

for fit function is need to have X-axis and Y-axis in the function.
self.m is number of training while self.n is number of features.

the reason self.w use np.zeros(self.n) because sometimes there are data have many of features. np.zeros() help make all the features became 0 

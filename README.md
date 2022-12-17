# Polynomial-Solver-using-SGD-in-TinyGrad

The solver will use data_train.csv to estimate the degree and coefficients of a polynomial. 

To test the generalization of the learned function, it should have small test error on data_test.csv.

TinyGrad was installed manually, the installation guide in the github link did not work.


Update:

Tensor did not work, but I created a code that might work if the device was installed with Tensor

Degree was initialized at 10

x and y arrays are initialized


Update:

Tried to create a code without the usage of Tensor and SGD, because it does not work on my computer. Will only serve as a final choice if was not able to submit a code that uses SGD

Learning Rate and Epoch set to 0.001 and 100

Degree was set to 2


Update:

Made a code the way I think it is supposed to work. (Included SGD even though it doesn't work in my device)

Epoch increased to 1000

Degree increased to 9, reasoning being that higher degrees can have coefficients of zero, so it's okay to be high.


Final Update:

Instead of hoping that SGD enables the program to learn the best degree, I would make it so that it iterates to a degree from 1 to 11 (because anything higher than 11 seems too much). Because of this, i'll split the training data so that one can act as a pseudo-test data to test the best degree.

Other parts of the code would be improved to make it look better

Noise would not be added though

# MNISTTensorflow
In this project we will run experiments using tensorflow. The experiments are closely related to the online example available at:
https://www.tensorow.org/get/started/mnist/pros.

The code in the example takes about 30 minutes to train, and achieves over 99% accuracy.
In this project I tired to solve the exact same problem with two constraints on the network being created that are intended to shorten the training time:
1. The first layer in the network must be a 4*4 maxpooling layer.
2. There is a limit on the number of batches and the batch size. If n1 is the number of bathes and n2 is the batch size, your program must satisfy n1*n2<20000.

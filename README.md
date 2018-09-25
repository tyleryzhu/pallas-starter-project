# Pallas Starter Project #3: Robustness to Noise

* Dataset: MNIST
* __Objective 1__: Train a simple neural network with 3 layers - 1 convolutional layer and 2 fully-connected layers on MNIST. Denote this predictor ![equation](http://latex.codecogs.com/gif.latex?%24%24f%24%24). Compute ![equation](http://latex.codecogs.com/gif.latex?%24%24var%28Y%29%20%3D%20var%28f%28X%29%29%20%24%24) (variance over the samples). Then, apply Gaussian noise ![equation](http://latex.codecogs.com/gif.latex?%24%24%20%5Cepsilon%20%5Csim%20%5Cmathcal%7BN%7D%280%2C%5Csigma%5E2I%29%24%24) to the samples ![equation](http://latex.codecogs.com/gif.latex?%24%24%20X&plus;%5Cepsilon%20%24%24), and compute the variance of the output ![equation](http://latex.codecogs.com/gif.latex?%24%24%20var%28Y%29%20%3D%20var%28f%28X&plus;%5Cepsilon%29%29%24%24). Repeat for increasing variance in the Gaussian. Plot ![equation](http://latex.codecogs.com/gif.latex?%24%24%20var%28Y%29%24%24) w.r.t. variance in the noise ![equation](http://latex.codecogs.com/gif.latex?%24%24%20%5Csigma%20%24%24).

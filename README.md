# QRBM
Implementation of Quantum Restricted Boltzmann Machine using quantum annealing on D-wave's QPU.

_In collaboration with [Mateusz Slysz](https://github.com/Matek1731)_

**NOTE:** previous repository utilizing IBM's QPU moved to [QRBM-qiskit](https://github.com/mareksubocz/QRBM-qiskit)

## Demo

To run demo, click on the badge below:

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/mareksubocz/QRBM/HEAD?urlpath=voila%2Frender%2FDemo.ipynb)

## Dataset
To download the default dataset, click here: [MNIST - a dataset of pictures of handwritten digits with 28x28 pixel resolution](https://www.kaggle.com/oddrationale/mnist-in-csv)

## Train the RBM yourself
The best way to run this code is to download the dataset and run all cells in the [jupyter notebook](qrbm_reconstruct_img.ipynb).

## Some results
A plot showing how the generated digit zero changes for different number of digits trained by the quantum RBM with respect to the chain strength parameter.
![alt text](https://github.com/mareksubocz/QRBM/blob/master/plots/animation.gif "Visualization of generated images based on changing chain strength and number of digits in the dataset")

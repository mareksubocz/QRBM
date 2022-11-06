# QRBM
Implementation of Quantum Restricted Boltzmann Machine using quantum annealing on D-wave's QPU.

Publication available at:
https://cmst.eu/articles/applying-a-quantum-annealing-based-restricted-boltzmann-machine-for-mnist-handwritten-digit-classification/

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

![alt text](https://github.com/mareksubocz/QRBM/blob/master/plots/new_animation.gif "Visualization of generated images based on changing chain strength and number of digits in the dataset")

## How to cite
```
@article{krzysztof2021applying,
  title={Applying a Quantum Annealing Based Restricted Boltzmann Machine for MNIST Handwritten Digit Classification},
  author={Krzysztof, Kurowski and Mateusz, Slysz and Marek, Subocz and Rafa{\l}, R{\'o}{\.z}ycki},
  journal={CMST},
  volume={27},
  number={3},
  pages={99--107},
  year={2021},
  publisher={PSNC, Poznan Supercomputing and Networking Center}
}
```

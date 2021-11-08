# NetVLAD-Pytorch Implementation
This repository consists of Pytorch implementation of NetVLAD & Online Hardest Triplet Loss. 

NetVLAD paper: https://arxiv.org/abs/1511.07247

## Installation

This repo was tested with Python 3.8.6 with CUDA 10.2. 
```shell
python setup.py develop # OR python setup.py install
```
# Setup

## Dependencies

1. [PyTorch](https://pytorch.org/get-started/locally/) - Version used: 1.10.0
2. [numpy](http://www.numpy.org/) - Version used: 1.19.5
3. [matplotlib](https://matplotlib.org/) - Version used: 3.3.4
4. [OpenSSL](https://pypi.org/project/pyOpenSSL/)
5. [Path](https://pypi.org/project/path/)

## Data

This code has been run with sample datasets in folder "data" present in the repo.

# References

[1] R. Arandjelović, P. Gronat, A. Torii, T. Pajdla, J. Sivic. "NetVLAD: CNN architecture for weakly supervised place recognition", CoRR, abs/1511.07247, 2015

## Important Installation Notes

1. Code may give URL errors if openSSL is installed incorrectly. A fresh installation is required in this case.
2. Code may give "Cuda not enabled" error for Cuda installation errors. Version check and fresh installation are required in this case.
3. Code may give "DLL load failed" error when the code is unable to import numpy due to version mismatch, installation errors, or path errors, especially when using conda env. This may be resolved by doing a fresh installation of all dependencies using pip in Terminal. 


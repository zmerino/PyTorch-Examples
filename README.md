# PyTorch Tutorial

This repository contains code/notebooks used to follow the tutorial [Deep Learning with PyTorch: A 60 Minute Blitz](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html)


## Chcek GPU for CUDA Campatibility

Run `sudo lshw -C display` from terminal on linux.

## Environment Setup

Create an anaconda environment called `nnbasics`:

1) Check list of existing environments `conda env list`
2) Create new environment `conda create -n nnbasics python=3.10.9 anaconda`

## Install PyTorch Packages

1) `conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia`
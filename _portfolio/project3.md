---
title: Deep Learning in Julia
subtitle: Various ML-related projects in Julia
image: assets/img/projects/julia_dl.png
alt: 

caption:
  title: Deep Learning in Julia
  subtitle: Various ML-related projects in Julia
  thumbnail: assets/img/projects/julia_dl.png
---

While I was taking *Deep Learning* course in Koc University, we were asked to implement a deep learning paper as a term project. Additionally, we had to use [Julia Language](https://julialang.org/) and [Knet Deep Learning Framework](https://denizyuret.github.io/Knet.jl/latest/) as a language and framework, respectively. Below, you can find the codes that I have implemented as a utility for the code.

## [HapticFCN](https://github.com/vaydingul/HapticFCN.jl)
Julia implementation of the [paper](https://ieeexplore.ieee.org/document/7530831) called *Deep learning for surface material classification using haptic and visual information*

## [FCN](https://github.com/vaydingul/FCN.jl)
A convolutional neural network library that allows you to construct arbitrary shaped CNNS. It is based on [Knet](https://denizyuret.github.io/Knet.jl/latest/) deep learning framework. It automatically calculates the intermediate layer sizes and determines the output dimension. It can also work with multi layer perceptrons (MLPs). 

## [GDH](https://github.com/vaydingul/GDH.jl)
A generalized data holder (i.e., dataloader in [PyTorch](https://pytorch.org/)). It allows you to load and iterate over your data in a batched manner. It can work with in both **online** and **offline** setup. 


## [FunctionLib](https://github.com/vaydingul/FunctionLib.jl)
A helper class that allows you to create *function prototypes* that you can pass to another objects in order to use it later.


 
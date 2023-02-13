<a target="_blank" href="https://colab.research.google.com/github/GiorgiaRistich/Project-Neural-Networks/blob/main/Gradients_without_Backpropagation.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Project-Neural-Networks
This repository contains the project for the exam of Neural Networks. 

## Description
The project consists of implementing the paper [Gradients without Backpropagation](https://arxiv.org/pdf/2202.08587.pdf). 
In particular, the paper introduces a new method to compute the gradient of an objective function for optimization that is based on forward mode instead of reverse mode (backpropagation). So, the key idea is to evaluate the gradient in a single forward run of the function eliminating the need of backpropagation. 
The final algorithm to implement is the following: 


![alt text](https://github.com/GiorgiaRistich/Project-Neural-Networks/blob/main/images/final_algorithm.png)

## Installation
The code is implemented in Python3 using Pytorch. To run the code it is necessary to have the packages that are imported at the beginning of the notebook in the first cell: Matplotlib, Numpy, Pytorch, Statistics.

## Authors
Giorgia Ristich

Martina Sgnaolin


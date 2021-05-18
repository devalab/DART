# DART: Deep Learning Enabled Topological Interaction Model For Identifying Ground State Clusters
DART model predicts metallic cluster's energy using Topological atomic descriptor (TAD). Further, it can be used to identify/filter low energy structures generated using molecular dynamics simulations.

In the conventional approach, for identifying unique low energy structures, Quantum Mechanics (QM) geometry optimization is a bottleneck. In this work, we have introduced a model called DART. DART can predict a given cluster's energy in a fraction of computational time compared to QM with accuracy comparable to QM. DART can identify/filter a few hundred low-energy structures from thousands of structures obtained from MD simulations. The advantage of using DART is that one can avoid the need to perform geometry optimization of all the thousands of structures obtained from MD simulations.

![new_workflow](https://user-images.githubusercontent.com/24433906/118666801-1454f900-b811-11eb-874a-191470243fed.png)

This repository contains code for training the DART model using a small subset of the dataset described in the paper.

# Installation
All the codes have been tested on Linux (ubuntu)

## Requirements:
```
Python 3.7
Pytorch 1.2
Matplotlib
Jupyter Notebook
```
## Source code:
The code is writen in Jupyter notebooks. 


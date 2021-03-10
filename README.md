# DART: Deep Learning Enabled Topological Interaction Model For Identifying Ground State Clusters
DART model predicts metallic cluster's energy using Topological atomic descriptor (TAD). Further, it can be used to identify/filter low energy structures generated using molecular dynamics simulations.

In the conventional approach, for identifying unique low energy structures, QM geometry optimization is a bottleneck. In this work, we have introduced a model called DART. DART can predict a given cluster's energy in a fraction of computational time compared to QM with similar accuracy. We can filter a few hundred possible low-energy structures out of thousands of structures obtained from MD simulations.

![new_workflow](https://user-images.githubusercontent.com/24433906/110602836-5f68e500-81ac-11eb-8806-1f1f270861b7.png)

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


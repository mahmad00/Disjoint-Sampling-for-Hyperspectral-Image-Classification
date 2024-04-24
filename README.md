# Importance of Disjoint Sampling

# This demo is associated with: [Importance of Disjoint Sampling in Conventional and Transformer Models for Hyperspectral Image Classification]() Submitted for possible publication. The Paper is also available on ArXiv and can be accessed at "https://arxiv.org/abs/2404.14944"

## Models implemented in this work:
# 2D CNN
# 3D CNN
# Hybrid CNN
# 2D Inception Net
# 3D Inception Net
# Hybrid Inception Net
# Attention Graph CNN
# Spatial-Spectral Transformer

## Requirements

This tool is compatible with Python 2.7 and Python 3.5+ and executed over Colab.

## Hyperspectral datasets

Several public hyperspectral datasets are available on the [EHU]([http://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes](https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes)). Users can download those beforehand. 

An example dataset folder has the following structure:
```
Datasets
├── University of Houston
│   ├── UH.mat
│   └── UG_gt.mat
├── IndianPines
│   ├── Indian_pines_corrected.mat
│   ├── Indian_pines_gt.mat
├── Pavia University
│   ├── PU.mat
│   └── PU_gt.mat
├── Botswana
│   ├── BS.mat
│   └── BS_gt.mat
├── Salinas
│   ├── SA.mat
│   └── SA_gt.mat
```

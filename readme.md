# Repository for Semantic Segmentation using Deep Learning for [MoNuSeg](https://monuseg.grand-challenge.org/Data/) Dataset

In this repository, we work with already created ground truth segmentation masks.

# Pre-requistes

 - Keras 2.2.3
 - Tensorflow 1.15.0
More details can be found in respective notebooks.

# Features
 - [x] Preprocessing
 - [x] Data set Visualizations
 - [x] Networks summaries
 - [x] Training
 - [x] Inference
 - [x] Predicted result visualized
 

# Models

This repository contains three different semantic segmentation models:
 - UNet
 - SegNet (supports indices pooling)
 - DeepLabv3

You can find trained models in respective folders. 

## Dataset directory format

    -->Training
    -----Images
    -----Masks
    -->Validation
    -----Images
    -----Masks





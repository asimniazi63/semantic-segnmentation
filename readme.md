# Repository for Semantic Segmentation using Deep Learning for [MoNuSeg](https://monuseg.grand-challenge.org/Data/) Dataset

In this repository, we work with already created ground truth segmentation masks.

# What is Segmentation Segmentation?
The goal of semantic image segmentation is to label each pixel of an image with a corresponding class of what is being represented.
Because we’re predicting for every pixel in the image, this task is commonly referred to as dense prediction. The major applications of semantic segmentation
are bio-medical diagnosis, Geo-Sensing, automous vehicles etc.

# Diagrams

## UNet
![Image of Yaktocat](Images/UNet.png)
## SegNet
![Image of Yaktocat](Images/SegNetNet.png)
## DeepLabv3
![Image of Yaktocat](Images/DeepLabv3.png)

# Pre-processing
MonuSeg datset contains 30 images for training and 14 images for testing each size of 1000x1000. 
To facilitate the training process, patches i.e. 256x256 for every images along with their corresponding masks can be generated using
`view_as_windows`. More details can be found in `patch_generator.ipinb`. Each image in the example generates 36 patches, thus overall 1584 patches.

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
 - UNet (Training + inference)
 - SegNet (Training + inference)
	- supports indices pooling)
 - DeepLabv3 (Training + inference)
	- supports MobileNetv2 and Xception backbone

You can find trained models in respective folders. 





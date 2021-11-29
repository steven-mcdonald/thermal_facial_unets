# U-Net Based Network for Thermal Facial Landmark Detection

A U-Net based neural network developed to annotate thermal facial images with landmarks. The network architecture is adapted from the approach proposed by Chu et al. [IEEE link](https://ieeexplore.ieee.org/abstract/document/8901710) [pdf link](http://mmcv.csie.ncku.edu.tw/~wtchu/papers/2019MMSP-chu2.pdf). 

Training is in two stages. Initially the U-Net is trained alone to predict a probability heatmap of where landmarks may be on an image. Then fully connected layers are added and training is continued to predict exact x, y image coordinates for each facial landmark.

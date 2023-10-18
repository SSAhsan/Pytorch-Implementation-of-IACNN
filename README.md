# Pytorch-Implementation-of-IACNN
Pytorch Implementation of the Paper "A Pseudo-Blind Convolutional Neural Network for the Removal of Artifacts in Compressed Image and Video (IEEE CSVT 2019)"
This repo contains the Jupyter notebook for training IACNN (https://ieeexplore.ieee.org/document/8653951). The code is written for JPEG image deblocking for gray-scale images but it can easily be modified to use for denoised images and RGB images.
To use the netwrok for RGB images, the initial channels and the final output channels have to be set to 3 instead of 1. This implementation provides performance very close to the values reported in the paper. 
This following repo helped a lot to write functions for the jupyter notebook. Do check it out at https://github.com/cszn/KAIR/tree/master!  

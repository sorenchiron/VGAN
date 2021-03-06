# VGAN

Official implementation of paper Spectral Image Visualization Using Generative Adversarial Networks

# How to setup

## Prerequisites

Linux

Python 

numpy

scipy

NVIDIA GPU + CUDA 8.0 + CuDNNv5.1

TensorFlow 1.0



# Getting Started

Clone this repo

Train the model:

python3 main.py --phase train --modeltype cyclegan --gtype pixnet_resnet --epoch 2 --image-size 128 --niter 2 --glr 0.0001 --lr 0.00001 --lambda-A 50 --lambda-B 50 --d-queue-len 100 

Test the model:

python3 main.py --phase test --modeltype cyclegan --gtype pixnet_resnet --epoch 2 --image-size 128 --niter 2 --glr 0.0001 --lr 0.00001 --lambda-A 50 --lambda-B 50 --d-queue-len 100 




# A portion of Datasets are available from:

facades: http://cmp.felk.cvut.cz/~tylecr1/facade/

sketch: http://mmlab.ie.cuhk.edu.hk/archive/cufsf/

maps: https://mega.nz/#!r8xwCBCD!lNBrY_2QO6pyUJziGj7ikPheUL_yXA8xGXFlM3GPL3c

oil-chinese:  http://www.cs.mun.ca/~yz7241/, jump to http://www.cs.mun.ca/~yz7241/dataset/

material-transfer: http://www.cs.mun.ca/~yz7241/dataset/

day-night: http://www.cs.mun.ca/~yz7241/dataset/



# Acknowledgments

Codes are built on the top of Cycle-GAN. Thanks for their precedent contributions!

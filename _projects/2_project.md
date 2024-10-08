---
layout: page
title: Learning to denoise
description: 
img: assets/img/proj_5/project_background.png
importance: 4
category: Graduate
---

Denoising is the process of removing noise from images, audio, or video, which can arise from various intrinsic and extrinsic conditions. This project focuses on the well-known MNIST dataset, eliminating the need for additional data processing and download. Our objective was to develop an Autoencoder architecture capable of effectively capturing key features from input images. The encoder compresses high-dimensional data into a lower-dimensional representation, with essential features extracted at the bottleneck layer. These features are subsequently passed to the decoder, which reconstructs an output closely resembling the original input. To evaluate the performance of the denoising network, we analyze the reconstructed images using a Fully Connected Linear Network classifier, independently trained on clean MNIST images devoid of noise. This approach demonstrates the effectiveness of our Autoencoder in learning to denoise and reconstruct images for enhanced classification accuracy. The details of the project can be found [here](https://sites.google.com/uw.edu/cse455finalpjtsdam/home).
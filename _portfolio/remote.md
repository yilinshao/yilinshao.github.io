---
title: "Remote Sensing Data Interpretation System"
excerpt: "Developed a system that can perform land cover mapping, object detection, and etc. <br/><img src='/images/remote.png' width = '250'>"
collection: portfolio
---

Provides technical support to the bureau of land management and the department of environmental protection. It monitors the land use situation via land cover mapping, water area segmentation, object detection, and change detection on remote sensing images.

<img src="http://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=FFFFFF"> <img src="http://img.shields.io/badge/-Pytorch-EE4C2C?style=flat&logo=pytorch&logoColor=FFFFFF">

## R&D Experience

Implemented water area segmentation. Unlike color images in the real-world, remote sensing images have more than three channels. Therefore, simply feeding the raw data into the model produce redundant features. To solve this problem, I first analyze the sensitivity of different bands to the waters and then augment the original image. I use a multi-resolution deep neural network to learn and extract the features and perform water area segmentation while taking into consideration the large size of the image. However, the waters' contours are usually irregular and, thus, are easy to misalign in the results. I reallocated more computational resources to the classification near the edge using information entropy, resulting in improved compact results.


## Duration 
Sept, 2020 - Jun, 2021

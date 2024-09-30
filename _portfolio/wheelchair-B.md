---
title: "Eye-controlled Wheelchair for Patients with ALS (Phase B)"
excerpt: "Designed and implemented carer-following function to the eye-controlled wheelchair. <br/><img src='/images/wheelchair-B.png' width = '250'>"
collection: portfolio
---

Designed and implemented software and control circuits that enable patients with ALS to use eye motions to command their wheelchair and online household appliances.

<img src="http://img.shields.io/badge/-C++-00599C?style=flat&logo=cplusplus&logoColor=FFFFFF"> <img src="http://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=FFFFFF">

## R&D Experience

At first, I tried to deploy the deep learning-based object tracking methods on the wheelchair. However, these methods typically consume large amounts of computing resources to ensure real-time video processing. Limited by the capacity and power of the battery on the electric wheelchair, I finally chose a shallow feature-based approach, specifically Kernel Correlation Filter. I implement the algorithm in C++ instead of the less efficient Python to achieve higher frame rates. My next task was to identify the carer at the beginning. After a trade-off between speed and accuracy, I finally chose the YOLOv3 object detection algorithm.  

## Duration 
Jun, 2019 - Dec, 2019

## Awards

* The 5th China International College Students Innovation and Entrepreneurship Competition: Silver Award
  <br/><img src='/images/Internet+.jpg' width = '500'>

* 2019 China Good Design: Innovative Award
  <br/><img src='/images/good_design.jpg' width = '300'>



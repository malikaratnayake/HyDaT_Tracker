# HyDaT_Tracker

![](/images/tracks.png)

## Introduction

HyDaT Tracker is designed to track insect pollinators in complex dynamic environments. It uses a combination of foreground-background segmentation and deep learning-based detection for tracking. HyDaT uses YOLOv2 as the deep learning-based object detection model and KNN background subtractor as the foreground-background segmentation model. 

Related Publication: Malika Nisal Ratnayake, Adrian G Dyer, Alan Dorin. "Tracking individual honeybees among wildflower clusters with computer vision-facilitated pollinator monitoring".

## Content

HyDaT_Tracker repository contains the following tracking and data analysis tools.
* HyDaT_Tracker.ipynb and related dependencies - Insect tracking program (Setup to track honeybees foraging in a Scaevola ground cover)
* Scaevola_analysis.ipynb and related tracks - An analysis of honeybee foraging behaviour in a Scaevola ground cover.
* Lamb's-ear_analysis.ipynb and related tracks - An analysis of honeybee foraging behaviour in Lamb's-ear ground cover.

 
## Setup

Test video files and pretrained YOLOv2 detection models are available [here](https://doi.org/10.26180/5f4c8d5815940) [1]

This version of HyDaT_Tracker is programmed to track honeybees foraging in a Scaevola ground cover. Related pre-trained models and dependencies are available at [Training_Dataset-Scaevola-Pretrained_model_YOLO.zip"](https://doi.org/10.26180/5f4c8d5815940) [1] Unzip and copy the contents to the directory of the HyDaT Tracker before use.

Pretrained YOLOv2 model and related dependencies for honeybees foraging in Lamb's-ear ground cover are available at  ["Training_Dataset-Lambs_ear-Pretrained_model_YOLO.zip"](https://doi.org/10.26180/5f4c8d5815940) [1].

To train a custom dataset please follow instructions given [here](https://github.com/deep-diver/Soccer-Ball-Detection-YOLOv2) [2]

## Dependencies

* Python 3.7.1
* [Darkflow](https://github.com/thtrieu/darkflow) [3] 
* OpenCV 3.4.1
* Tensorflow 1.13.1
* Numpy 1.16.2
* Pandas 0.24.2 
* Matplotlib 3.0.3.

## References

[1] Ratnayake, Malika Nisal; Dyer, Adrian; Dorin, Alan (2020): Honeybee video tracking data. Monash University. Dataset. https://doi.org/10.26180/5f4c8d5815940

[2] Park C. Soccer-Ball-Detection-YOLOv2. 2018. Available: https://github.com/deep-diver/Soccer-Ball-Detection-YOLOv2

[3] Trieu. Darkflow. 2018. GitHub Repository. Available online: https://github. com/thtrieu/darkflow (accessed on 14 February 2019)


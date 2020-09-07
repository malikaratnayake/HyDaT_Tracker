# HyDaT_Tracker

## Introduction

HyDaT Tracker is designed to track insect pollinators in complex dynamic environments. It uses a combination of foreground background segmentation and deep learning-based detection for tracking. HyDaT uses YOLOv2 as the deep learning-based object detection model and KNN background subtractor is used for foreground-background segmentation. 

More information on functionality of the HyDaT_Tracker can be found in the related publication: Malika Nisal Ratnayake, Adrian G Dyer, Alan Dorin. "Tracking individual honeybees among wildflower clusters with computer vision-facilitated pollinator monitoring".

## Content

HyDaT_Tracker repository contains following tracking and data analysis tools.
* HyDaT_Tracker.ipynb and related dependancies - Insect tracking program (Setup to track honeybees foraging in a Scaevola ground cover)
* Scaevola_analysis.ipynb and related tracks - An analysis of honeybee foraging behaviour in a Scaevola ground cover.
* Lamb's-ear_analysis.ipynb and related tracks - An analysis of honeybee foraging behaviour in Lamb's-ear ground cover.
 
## Setup

Test video files and pretrained YOLOv2 detection models are available at data repository xxx.

This version of HyDaT_Tracker is setup to track honeybees foraging in Scaevola ground cover. Related pretrained models and dependancies are available in "Training_Dataset-Scaevola-Pretrained_model_YOLO" folder in data repository. (PATH:  Honeybee_Video_Tracking_Data/Training_Datasets/Training_Datasets-Scaevola/Training_Dataset-Scaevola-Pretrained_model_YOLO.zip). Unzip and copy the contents to the directory of HyDaT Tracker before use.

Pretrained YOLOv2 model and related dependancies for honeybees foraging in Lamb's-ear ground cover is available at "Honeybee_Video_Tracking_Data/Training_Datasets/Training_Datasets-Lambs_ear/Training_Dataset-Lambs_ear-Pretrained_model_YOLO.zip" in the data repository.

To train a custom dataset please follow the instructions given here. https://towardsdatascience.com/yolov2-to-detect-your-own-objects-soccer-ball-using-darkflow-a4f98d5ce5bf






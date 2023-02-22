# ZF-4DRadar-Dataset                 

This repository provides a ZF FRGen21 4D radar dataset for autonomous driving object detection.

## Overview
* Introduction
* Sensor and Data
* Demos
* Data Release


---

## Introduction
This data set contains 7,000 frames of 4D millimeter-wave radar data, and camera and lidar data are also collected and calibrated synchro-nously.Scenarios for this dataset include 4 typical scenes:Urban complex traffic scene, parking lot scene, tunnel scene, highway scene.And The category of object detection includes four classes:Car,Bycicle,Pedesrian and Truck_Bus.

## Sensor and Data
The 4D radar used for our data is ZF FRGEN21 4D radar,It offers high detection performance in four dimensions (range, velocity, azimuth and elevation),can cover the object up to the distance of 200m.  

Our annoated format similiar with kitti dataset,contains the time stamp of the multi-sensor, calibration parameters, and the category of object detection and the position and size of the detection bounding box.We divided the data set containing 7000 frames into 5000 frames of train set, 1000 frames for validation set and test set separately.


## Demos
The demos below shows the object detection effect on the test set in four scenarios.

- urban  
![Alt Text](https://media.giphy.com/media/a6uwOANOrGBgjMoXTo/giphy.gif)

- parking lot  
![Alt Text](https://media.giphy.com/media/vRHKGnzb7yXHi0EV2l/giphy.gif)

- tunnel  
![Alt Text](https://media.giphy.com/media/94vT6yzqhOep57Cq4O/giphy.gif)

- highway  
![Alt Text](https://media.giphy.com/media/MLM7xI2DhawvC5lRdG/giphy.gif)

## Data release
Due to policy, We will make the dataset publicly available in this year.TR

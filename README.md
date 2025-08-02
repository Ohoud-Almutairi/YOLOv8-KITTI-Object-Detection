# 🚘 Autonomous Driving Object Detection Using YOLOv8

This project implements an object detection system for autonomous driving using the **KITTI dataset** and **YOLOv8**. 

## 📌 Overview

- 🧠 Model: YOLOv8 (Ultralytics)
- 🗂️ Dataset: KITTI Vision Benchmark
- 🏷️ Detected Classes:
  - Car
  - Pedestrian
  - Van
  - Cyclist
  - Truck
  - Misc
  - Tram
  - Person Sitting
  - DontCare (optional)

## 🧪 Features

- Downloads and unpacks KITTI dataset
- Converts KITTI labels into YOLO format
- Splits data into training/validation
- Creates YOLO config YAML file
- Trains a YOLOv8 model with custom settings
- Evaluates the model using confusion matrix and results plot
- Runs prediction on test images and displays output

## 📁 Files Included

- Full code for dataset processing, training, and testing.




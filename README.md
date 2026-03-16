## YOLOv4 Real-Time Object Detection
### Overview

This project implements real-time object detection using YOLOv4 and OpenCV in Python. The system captures live video from a webcam and detects objects using the pretrained YOLOv4 model trained on the COCO dataset. Detected objects are displayed with bounding boxes, labels, and confidence scores.

### Features

Real-time object detection using webcam

Detects 80 object classes from the COCO dataset

Bounding boxes with object labels and confidence values

Uses OpenCV DNN module for deep learning inference

Visualization using Matplotlib

### Technologies Used

Python

OpenCV

NumPy

Matplotlib

YOLOv4

COCO Dataset

### Features

Real-time object detection using webcam

YOLOv4 deep learning model integration

Detection of 80 object categories from the COCO dataset

Bounding boxes around detected objects

Display of object labels and confidence scores

Non-Maximum Suppression (NMS) to remove duplicate detections

Simple Python implementation using OpenCV DNN module

Visualization using Matplotlib


### Installation

Install the required libraries:

pip install opencv-python numpy matplotlib

How to Run

Download the YOLOv4 model files (yolov4.cfg, yolov4.weights, coco.names).

Place them in the project folder.

Run the program:

python object_detection.py

The webcam will start and detect objects in real time.

### Applications

Smart surveillance systems

Security monitoring

Robotics vision

Autonomous vehicles

Smart retail analytics

### Conclusion

This project demonstrates how YOLOv4 and OpenCV can be used for real-time object detection. It provides a simple implementation for detecting multiple objects from a live webcam stream using deep learning.

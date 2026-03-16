
This project implements **real-time object detection using YOLOv4, OpenCV, and Python**.  
It captures video from the webcam and detects objects using the **YOLOv4 deep learning model trained on the COCO dataset**.

The detected objects are displayed with **bounding boxes, labels, and confidence scores** in real time.

---

## Features

- Real-time object detection using webcam
- Uses YOLOv4 deep learning model
- Detects 80 common objects from the COCO dataset
- Displays bounding boxes and confidence scores
- Implemented using OpenCV DNN module
- Visualization using Matplotlib

---

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- YOLOv4
- COCO Dataset

## Project Structure


YOLOv4-Webcam-Object-Detection
│
├── yolov4.cfg
├── yolov4.weights
├── coco.names
├── object_detection.py
└── README.md


---

## Requirements

Install the required libraries:

```bash
pip install opencv-python numpy matplotlib

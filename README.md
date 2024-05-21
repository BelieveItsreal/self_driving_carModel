# self_driving_carModel
This project integrates a YOLOv8-based car detection model and a custom road detection model to create a self-driving car system capable of detecting cars and identifying lane lines on the road.

## Main Code for Self-Driving Car Implementation

This repository contains the main codebase for implementing a self-driving car system. The code integrates two key components: the road detection model and the car detection model combined together to implement a realtime self driving car model. 

Due to the proprietary nature of the code and the sensitive algorithms involved, it has not been uploaded publically to GitHub or made publicly available. The primary reason for keeping the code private is to protect intellectual property and ensure that the technology is not misused or replicated without proper authorization.

For inquiries regarding access to the code or collaboration opportunities, please contact [malatiexe@gmail.com].

## Description

The system combines two components:
1. **Car Detection**: Uses YOLOv8 to detect cars.
2. **Road Detection**: Uses image processing techniques to identify lane lines.

## Steps

### Importing Libraries
- Libraries used: Pandas, OpenCV, Matplotlib, NumPy, and more.

### Adding the Dataset
- Loaded and shuffled the dataset from "labels_train.csv".

### Labeling the Objects
- Identified unique classes and assigned labels for better understanding.

### Labeling the Objects in Images
- Loaded images and displayed bounding boxes with labels.

### Road Detection Preprocessing
- Converted images to grayscale, applied Gaussian blur, and detected edges with Canny.

### Training the Car Detection Model
- Utilized YOLOv8, made predictions, and displayed results with bounding boxes and probabilities.

### Training the Road Detection Model
- Implemented functions for edge detection, region of interest extraction, and lane line detection using Hough Transform.

### Testing the Models
- Tested both models on new images, saved bounding box information, and visualized the results.

### Road Detection on Video
- Processed video frames in real-time, detected lane lines, and displayed the results.

### Running the Complete System
- Combined both models to simultaneously detect cars and lane lines in images and videos.

## Output Files
- `bounding_boxes_car.txt`: Contains coordinates of detected cars.
- `bounding_boxes_road.txt`: Contains coordinates of detected lane lines.



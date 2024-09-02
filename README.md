# Vehicle Detection and Counting System

This project is a computer vision application that detects, tracks, and counts vehicles crossing a defined boundary line in a video feed. The main components and workflow of the project are as follows:
![image](https://github.com/user-attachments/assets/5d61d2e8-4095-44aa-b193-0541db56c986)

## 1. Video Processing with OpenCV
The project reads frames from a video file (cars.mp4). 

The frames are combined with a mask (mask.png) to enhance vehicle detection.
## 2. Object Detection with YOLO Model
The YOLOv8 model is used to detect objects such as cars, trucks, and buses.

Detected objects are labeled with their class names and confidence scores.
## 3. Object Tracking with SORT Algorithm
The Sort algorithm tracks detected objects and assigns a unique ID to each one.

The positions of the objects are updated in each frame.
## 4. Boundary Line and Counting Mechanism
A specific boundary line is defined on the image (limits = [400,297,673,297]).

Objects crossing this line are counted, and each crossing event is recorded.
## 5. Drawing and Displaying Information on the Image
The system detects whether the objects have crossed the boundary line; when crossed, the line changes color to green.

Each tracked object's ID and the count information are displayed on the image.
## Use Case
This project simulates a vehicle tracking and counting system that can be used in scenarios such as traffic monitoring, security applications, and data analysis.



Note: I do not own the copyrights of this project.(youtube @murtazasworkshop) It is for learning purposes only.

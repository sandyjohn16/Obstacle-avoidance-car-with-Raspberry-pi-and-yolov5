# Obstacle Avoidance Raspberry Pi Car using YOLOv5

## Project Overview
This project develops a real-time indoor obstacle avoidance system using the YOLOv5 Nano model integrated with ultrasonic sensors.  
The system runs on a Freenove 4WD Smart Car Kit powered by a Raspberry Pi 4 running Debian 12 (Bookworm).

## Key Features
- Uses YOLOv5 Nano for object detection
- Combines vision-based detection with ultrasonic sensor data for reliable obstacle avoidance
- Real-time processing and decision-making
- Remote monitoring and control via RealVNC

## Hardware Used
- Raspberry Pi 4
- Freenove 4WD Smart Car Kit
- Ultrasonic Sensors
- Raspberry Pi Camera Module

## Software & Tools
- Python
- Picamera2 Library
- OpenCV
- PyTorch for YOLOv5 Model Inference

## System Architecture
The system continuously collects sensor data and camera frames, processes them using YOLOv5 Nano, and makes real-time navigation decisions to avoid obstacles.

## Project Outcomes
- Smooth and reliable navigation in indoor environments
- Effective obstacle detection combining vision and sensor data
- Demonstrated the feasibility of deploying YOLOv5 Nano on a Raspberry Pi for real-time applications

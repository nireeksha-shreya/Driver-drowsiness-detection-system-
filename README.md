# Driver Drowsiness Detection System

## Overview
This project is a Driver Drowsiness Detection System that uses computer vision and machine learning to monitor eye movement and detect signs of fatigue in real time. If the system detects that the driver's eyes are closed for too long, it triggers an alert to prevent accidents.

## Features
- Real-time face detection
- Eye tracking and blink detection
- Drowsiness alert system
- Computer vision using OpenCV
- Machine learning based detection

## Technologies Used
- Python
- OpenCV
- NumPy
- Machine Learning
- Computer Vision

## How It Works
1. The camera captures live video.
2. The system detects the face and eyes.
3. Eye aspect ratio / eye closure is monitored.
4. If eyes remain closed for a certain time, an alert is triggered.

## Installation
```bash
git clone https://github.com/your-username/driver-drowsiness-detection.git
cd driver-drowsiness-detection
pip install -r requirements.txt
python main.py

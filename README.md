# Human-Activity-Recognition-with-OpenCV-and-Deep-Learning

Overview
This project involves the development of a real-time Human Activity Recognition (HAR) system that classifies various human activities from video streams using a pre-trained 3D ResNet deep learning model. The system processes spatiotemporal data from video inputs, recognizes activities, and triggers real-time alerts for specific activities. It is built using Python, OpenCV, and NumPy, with the Winsound API providing auditory alerts.

Features
Real-Time Activity Recognition: Classifies over 400 different activities from live video feeds or video files.
Spatiotemporal Data Processing: Utilizes a 3D ResNet model to analyze both spatial and temporal aspects of video frames.
Immediate Alerts: Generates sound alerts using the Winsound API when specific abnormal activities are detected.
Flexible Input Handling: Supports video input from files or live camera feeds.
Visual Output: Displays the recognized activity directly on the video feed in real-time.

Technologies and Tools
Programming Language: Python
Computer Vision Library: OpenCV
Numerical Computation Library: NumPy
Deep Learning Model: Pre-trained 3D ResNet (trained on the Kinetics 400 dataset)
Alert System: Winsound API
Video Processing Tools: argparse for command-line arguments, imutils for image manipulation

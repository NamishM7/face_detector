# Real-Time Face Detection with OpenCV

This project implements real-time face detection using OpenCV's Haar Cascade Classifier. It captures video from the webcam, detects faces in real-time, and displays the video feed with bounding boxes around detected faces.

## Features

- Real-time face detection using Haar Cascade Classifier.
- Displays bounding boxes around detected faces in a video stream.
- Press `q` to quit the program.

## Prerequisites

Before running the project, ensure you have the following installed:

1. Python 3.6 or above
2. OpenCV library

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/face-detection-opencv.git
   cd face-detection-opencv
2. Install the required dependencies
   ```
   pip install opencv-python
   ```
   If you encounter issues with GUI functionality, install the full version of OpenCV:
   ```
   pip install opencv-python-headless
3. Verify that your camera is working and accessible.

## Usage

1. Run the script:
   ```
   python main.py
2. The program will open your webcam and display the video feed with detected faces outlined by rectangles.
3. Press the q key to quit the program.

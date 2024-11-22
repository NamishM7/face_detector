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

## Code Overview

The main functionality is implemented in main.py:
1. Haar Cascade Classifier: The pre-trained ```haarcascade_frontalface_default.xml``` is used to detect faces.
2. Frame Processing: Each frame from the webcam is converted to grayscale for efficient face detection.
3. Real-Time Detection: The detectMultiScale() function detects faces, and rectangles are drawn around them

## Troubleshooting
1. Camera not accessible: Ensure no other program is using the webcam and that the drivers are installed correctly.
2. cv2.imshow error: If you encounter an error related to GUI functionality, reinstall OpenCV with the following command:
   ```pip install opencv-python ```

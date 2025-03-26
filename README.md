# Face Detection using OpenCV

## Overview
This project implements real-time face detection using OpenCV and Python. It utilizes Haar Cascade classifiers and Deep Learning-based models for detecting faces in images, videos, or live webcam streams.

## Features
- Real-time face detection using OpenCV.
- Supports Haar Cascade and Deep Learning-based methods.
- Works with images, video files, and live webcam feed.
- Can detect multiple faces in a single frame.
- Simple and efficient implementation.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- OpenCV
- NumPy

### Install Dependencies
```sh
pip install opencv-python numpy
```

## Usage
### Run Face Detection on Webcam
```sh
python face_detection.py
```

### Run Face Detection on an Image
```sh
python face_detection.py --image path/to/image.jpg
```

### Run Face Detection on a Video
```sh
python face_detection.py --video path/to/video.mp4
```

## Code Explanation
1. Load the Haar Cascade classifier for face detection.
2. Read frames from the webcam or input image/video.
3. Convert frames to grayscale for better accuracy.
4. Detect faces and draw bounding boxes around them.
5. Display the output with detected faces.

## Customization
- Change the Haar Cascade XML file for different feature detections (e.g., eyes, smiles).
- Adjust parameters like scale factor and min neighbors for better accuracy.

## License
This project is open-source and available under the MIT License.

## Author
Gourav Bhatia


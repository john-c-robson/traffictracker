# Object Detection and Tracking using OpenCV

This Python script demonstrates object detection and tracking in a video using OpenCV. It applies a background subtraction method for object detection and utilizes the Euclidean distance-based tracking algorithm for tracking objects.

## Requirements

Python 3.x
OpenCV (cv2)
tracker.py file containing the EuclideanDistTracker class
Video file named highway.mp4 (or provide the correct file path)

## Installation

You can install the required Python packages using pip:

```bash
pip install opencv-python
```

## Usage

Ensure you have the necessary requirements installed and the video file in the same directory or provide the correct file path.

The script will open the video and start detecting and tracking objects.

Press the 'Esc' key (key code 27) to exit the script.

## Code Explanation

The script starts by importing the necessary libraries and initializing the object tracker.

It opens the video file for processing and creates a background subtractor for object detection.

The script then enters a loop to process each frame of the video.

A region of interest (ROI) is extracted from each frame.

Object detection is performed on the ROI using the background subtractor.

Detected objects are filtered based on their area.

Object tracking is carried out using the EuclideanDistTracker class.

Tracked objects are labeled with IDs and displayed on the frame.

The ROI, original frame, and object detection mask are displayed.

Pressing the 'Esc' key exits the script.

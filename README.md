# Object Tracking Using OpenCV

This project implements real-time object tracking using OpenCV and Python. It detects a specific color (yellow in this case) in a video stream from a webcam and draws a bounding box around the detected object.

## Features
- Captures video from a webcam
- Converts the video frames from BGR to HSV color space
- Detects objects of a specified color (yellow in this case)
- Draws a bounding box around the detected object
- Displays the processed video feed in real-time

## Requirements
Ensure you have the following dependencies installed before running the script:

## Usage
1. Clone this repository or download the script.
2. Run the script using:

   ```bash
   python color_detection.py
   ```
4. The webcam feed will open, and objects matching the yellow color will be detected and highlighted.
5. Press `q` to exit the application.

## Customization
- To track a different color, modify the `yellow` variable in the script to the corresponding BGR values of the desired color.

## License
This project is open-source and available under the MIT License.


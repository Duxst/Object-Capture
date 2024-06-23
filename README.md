# Real-Time Video Processing with OpenCV
This project captures video from the default camera on your laptop, applies background subtraction and Canny edge detection, displays the processed frames in real-time, and saves the output video to a file.

## Requirements
Python 3.x
OpenCV
## Installation
Install Python 3.x: If you don't have Python installed, you can download it from python.org.
Install OpenCV: Install OpenCV using pip.

## Features
Video Capture: Captures video from the default camera.
Background Subtraction: Uses the MOG2 background subtractor to create a mask of moving objects.
Edge Detection: Applies Canny edge detection on the mask.
Real-Time Display: Displays the original frame, mask, and edges in real-time.
Video Saving: Saves the processed video to an output file (output.avi).
Customization
Background Subtraction Parameters: Modify the parameters of the MOG2 background subtractor to adjust the background subtraction sensitivity.
Canny Edge Detection Parameters: Adjust the thresholds in the Canny edge detection function to change the edge detection sensitivity.
Output File: Change the output file name or format by modifying the VideoWriter parameters.
Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request.

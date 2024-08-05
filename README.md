This project implements an eye-controlled mouse using Python, OpenCV, MediaPipe, and PyAutoGUI. The application uses your webcam to track your eye movements and controls the mouse pointer on the screen. A blink can simulate a mouse click.

Features:-

Real-time eye tracking using a webcam.
Control the mouse pointer based on eye movements.
Simulate mouse clicks with a blink.
Requirements
Python 3.x
OpenCV
MediaPipe
PyAutoGUI


How It Works:- 

Webcam Capture: The webcam captures video frames using OpenCV.
Face Mesh Detection: MediaPipe detects facial landmarks, focusing on the eyes.
Mouse Control: PyAutoGUI moves the mouse pointer based on eye movements and simulates clicks when a blink is detected.

Customization:-
Sensitivity Adjustment: Modify the sensitivity of eye tracking and blink detection by changing the threshold values in the script.

Different Actions: Customize the actions performed (e.g., right-click, double-click) by modifying the corresponding PyAutoGUI functions.

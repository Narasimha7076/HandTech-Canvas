# Hand Gesture Painter
Hand Gesture Painter is a Python application that allows users to paint on a digital canvas using hand gestures captured through a webcam. The application detects hand gestures using the MediaPipe library and interprets them to perform various painting actions, such as selecting colors, drawing lines, and clearing the canvas.

Features
Gesture-based Painting: Users can paint on a digital canvas by making hand gestures in front of a webcam.

Color Selection: Different colors can be selected for painting by hovering over corresponding color buttons on the interface.

Clear Canvas: The canvas can be cleared by selecting the clear button, providing a fresh space for painting.

Real-time Visualization: The painting process is visualized in real-time, providing immediate feedback to the user.

How to Use
Installation:

Ensure you have Python installed on your system.
Install the required libraries by running pip install -r requirements.txt.
Running the Application:

Execute the hand_gesture_painter.py script.
Ensure that your webcam is connected and properly configured.
Painting:

Place your hand in front of the webcam.
Make gestures to draw on the canvas. Use your fingers to paint lines.
Color Selection:

Hover over the color buttons on the interface to select the desired color for painting.
Clearing the Canvas:

Select the clear button to erase all the drawn content on the canvas.
Exiting the Application:

Press the 'q' key to exit the application.
Dependencies
OpenCV
NumPy
MediaPipe
TensorFlow
Keras
Acknowledgments
This project utilizes the MediaPipe library for hand detection and gesture recognition. Special thanks to the contributors of MediaPipe for providing a powerful tool for computer vision applications.

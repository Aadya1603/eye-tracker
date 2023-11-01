# Eye Tracker using OpenCV, MediaPipe, and PyAutoGUI

## Introduction

This project demonstrates a basic Eye Tracker program that allows you to control your mouse cursor using your eyes. It uses computer vision techniques, including facial landmark detection provided by MediaPipe, and automation with PyAutoGUI to move and click the mouse cursor.

## Requirements

To run this program, you'll need the following libraries and tools:

- OpenCV (cv2)
- MediaPipe (mediapipe)
- PyAutoGUI
- A webcam or camera

You can install these libraries using pip:

```bash
pip install opencv-python mediapipe pyautogui
```


## Usage
Clone the repository or create a Python file with the code.
Ensure you have the required libraries installed.
Run the program.
A webcam window will open, and your camera will start capturing your face.
It will detect your eye movements and move the mouse cursor accordingly.
Blinking both eyes quickly will simulate a mouse click.
How it Works
The program captures video frames from your camera and processes them in real-time using MediaPipe's facial landmark detection. It identifies key facial landmarks, including eye position.

The program tracks the position of your eyes and moves the mouse cursor to match the eye's position.
A quick blink of both eyes simulates a mouse click using PyAutoGUI.
Note
For better performance and accuracy, you may need to adjust the code parameters, such as landmark points, screen resolution, and sleep times.
This is a simple demonstration of eye tracking. More advanced eye tracking solutions may require specialized hardware or software.
Contributing
Feel free to contribute to this project by improving the code, adding features, or fixing issues. Follow the standard GitHub workflow:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes.
Submit a pull request with a clear description of your changes.
License
This project is open-source and available under the MIT License. You can find the full license details in the LICENSE file.

Enjoy experimenting with your eye tracker program and feel free to reach out with any questions or suggestions!

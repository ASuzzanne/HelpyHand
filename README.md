# Helpy-Hand
# Description: 
Certainly, here's a description that you can add to your GitHub repository for the provided code:

---

## Eye-Controlled Mouse using FaceMesh and PyAutoGUI

This repository contains a Python script that demonstrates the creation of an eye-controlled mouse application using the FaceMesh model from the Mediapipe library and the PyAutoGUI library for cursor control and interactions.

### Features:

- **Real-time Eye Tracking:** The script utilizes the FaceMesh model from Mediapipe to detect and track facial landmarks, specifically focusing on the eye regions for eye gaze control.

- **Mouse Cursor Control:** The application maps the movement of the user's eyes to the movement of the mouse cursor on the screen, allowing for intuitive control of the cursor's position.

- **Left Eye Closure Interaction:** The code includes an interaction that detects the closure of the user's left eye. When the left eye is closed, the script triggers a mouse click action.

- **User-Friendly Interface:** The application uses speech synthesis (text-to-speech) to provide voice prompts and feedback to the user throughout the interaction.

### How to Use:

1. Make sure you have the required libraries installed:
   - OpenCV (`cv2`)
   - Mediapipe (`mediapipe`)
   - PyAutoGUI (`pyautogui`)

2. Clone this repository to your local machine.

3. Run the `eye_controlled_mouse.py` script using a Python interpreter.

4. The webcam feed will open, and you can start controlling the mouse cursor by moving your eyes. Closing the left eye triggers a mouse click.

5. To exit the application, press the 'q' key.

### Dependencies:

- [OpenCV](https://opencv.org/): Open Source Computer Vision Library
- [Mediapipe](https://mediapipe.dev/): A Cross-Platform Framework for Building Multimodal Applied ML Pipelines
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/): Cross-platform GUI automation Python module

### Note:

This project is intended for educational and demonstration purposes. It showcases how facial landmark detection can be used to create innovative and interactive applications.

---

Feel free to modify and customize this description to suit your GitHub repository's style and content.

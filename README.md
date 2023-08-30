# Helpy-Hand
# Description: 
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

## Voice-Controlled Web Search with Python

This repository hosts a Python script that demonstrates the creation of a voice-controlled web search tool. The script integrates several powerful libraries, allowing users to perform web searches using only their voice commands. By employing speech recognition, text-to-speech conversion, and web browsing capabilities, this project showcases how modern technologies can be seamlessly combined to enhance user interaction.

### Features:

- **Voice Interaction:** The script utilizes the `speech_recognition` library to capture and recognize the user's voice commands. This enables users to speak their search queries naturally.

- **Text-to-Speech Feedback:** The application employs the `pyttsx3` library to provide audible feedback to users. The tool vocalizes the recognized search query and welcomes users upon startup.

- **Web Search Integration:** The project integrates the `googlesearch` and `webbrowser` libraries, allowing users to perform web searches based on their voice input. The first search result is automatically opened in a new browser tab.

- **User-Friendly Interaction:** Users are guided throughout the interaction with spoken prompts, enhancing the user experience and accessibility.

### How to Use:

1. Ensure you have the necessary libraries installed:
   - `speech_recognition`
   - `googlesearch`
   - `webbrowser`
   - `pyttsx3`

2. Clone this repository to your local machine.

3. Run the `voice_controlled_search.py` script using a Python interpreter.

4. The application will prompt you with a welcome message and wait for your voice command.

5. Speak your search query clearly into the microphone. The application will vocalize your query and perform the search.

6. To exit the application, simply say "exit terminal."

### Dependencies:

- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/): Library for performing speech recognition
- [googlesearch-python](https://pypi.org/project/googlesearch-python/): A Python wrapper for the Google Search API
- [webbrowser](https://docs.python.org/3/library/webbrowser.html): Python's built-in web browsing module
- [pyttsx3](https://pypi.org/project/pyttsx3/): Text-to-speech conversion library

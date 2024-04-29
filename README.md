# Hand-Controlled-AI-Virtual-Mouse 🖱

## Version: 1.0.0.1

Hand-Controlled-AI-Virtual-Mouse is an AI-based virtual mouse controlled by hand gestures and hand detection.

**The mouse is one of the wonderful inventions of Human-Computer Interaction (HCI) Technology.** 

Currently, we use wired or wireless mice. In some real-time cases, some computers may not support a physical mouse, or some users may have hand problems or handicaps that prevent them from using a physical mouse. This Hand-Controlled AI Virtual Mouse can be used to overcome these problems, allowing users to control the mouse by reducing the need for direct computer-human interaction.

## Functionalities:

- Built using OpenCV-python and Mediapipe for detecting and processing images. Mediapipe is an open-source cross-platform developed by Google for media processing and ready-to-use ML solutions for computer vision tasks.
- Hand-controlled virtual mouse can move the mouse anywhere on the screen and perform click operations.
- Index finger can be used to move the mouse over the screen.
- Click operation is performed when the index finger and thumb come close to each other or touch.
- Uses PyAutoGUI for programmatically controlling the mouse and keyboard.

## Installation:

Libraries required for installation are listed in the `requirements.txt` file:

```text
opencv-python - 4.6.0.66
numpy - 1.23.1
matplotlib - 3.5.2
mediapipe - 0.8.10.1
pyautogui - 0.9.53
pillow - 9.2.0

## Run the Code:

To install the necessary dependencies, run the following command:pip install -r requirements.txt


## Hand Landmarks:
The actual working of the mouse is based on hand landmarks, which can be viewed and controlled by OpenCV and Mediapipe. The hand contains a total of 21 landmarks.


## Smoothening:
At first, the mouse pointer movement may appear erratic. To improve this, a smoothening factor is implemented to make the mouse pointer move smoothly.

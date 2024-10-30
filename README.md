# Hand Detector

This project uses OpenCV and MediaPipe to create a real-time hand detection application. The application detects and tracks hand landmarks from a webcam feed, allowing for various interactions based on hand movements.

## Features

- Real-time hand detection and tracking
- Display of hand landmarks
- Calculation of frames per second (FPS) for performance monitoring
- Supports multiple hands (up to 2)

## Requirements

To run this project, you need to have the following libraries installed:

- `opencv-python`
- `mediapipe`
- `numpy` (if needed for any additional processing)

You can install these dependencies using pip:

```bash
pip install opencv-python mediapipe

Getting Started
1. Clone the repository:

git clone https://github.com/yourusername/hand-detector.git
cd hand-detector

2. Run the application:

python hand_detector.py

Code Overview
The main components of the code are:

HandDetector Class: Initializes the hand detection model and contains methods for finding hands and their positions.

findHands(img, draw=True): Processes the image to detect hands and optionally draws landmarks.
findPosition(img, handNo=0, draw=True): Retrieves the positions of hand landmarks.
Main Loop: Captures video from the webcam, processes each frame to detect hands, and displays the results.

Example Output
The application will display your webcam feed with detected hands and their landmarks. The FPS is also displayed in the top-left corner of the window.

Contributing
Feel free to contribute to this project! You can fork the repository, make your changes, and submit a pull request.

Acknowledgments
OpenCV
MediaPipe

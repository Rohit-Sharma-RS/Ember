# AI Ember

AI Ember is an interactive AI-based application that integrates computer vision, natural language processing, and gesture recognition to enable dynamic interactions with a user. The application features emotion detection, gesture-based controls, and voice-command functionalities, creating an engaging and intuitive user experience.

## Features

1. **Gesture Recognition**:
   - Detects various hand gestures to perform actions like:
     - Scrolling
     - Zooming
     - Mouse movement
     - Volume control
     - Switching applications

2. **Emotion Detection**:
   - Identifies user emotions using DeepFace and provides real-time feedback based on dominant emotions.

3. **Speech Recognition**:
   - Executes voice commands for:
     - Sending messages on Instagram
     - Searching Google
     - Playing music on Spotify or YouTube
     - Sentiment analysis of spoken content

4. **Dynamic Volume Control**:
   - Adjusts system volume based on hand gestures.

5. **Customizable Actions**:
   - Modify gestures and commands for personalized usage.

## Technologies Used

- **Libraries**:
  - `cv2` (OpenCV): For image capture and gesture recognition.
  - `pyautogui`: For simulating mouse and keyboard actions.
  - `pycaw`: For controlling audio volume.
  - `DeepFace`: For emotion analysis.
  - `speech_recognition`: For recognizing voice commands.
  - `simple_colors`: For terminal text styling.
  - `numpy`: For numerical operations.
  - `selenium`: For automation.

- **Custom Modules**:
  - `gesture`: Includes the `handDetector` class for gesture detection.
  - `helper_functions`: Contains helper functions for sending messages, searching Google, playing music, sentiment analysis, and even AI-based recommendations.

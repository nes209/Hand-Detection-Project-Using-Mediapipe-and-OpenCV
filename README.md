# Hand Detection Project Using Mediapipe and OpenCV:
This project aims to use Google's Mediapipe library to detect and recognize hands in live video from the camera.
Using OpenCV, the video is displayed in real time with the user using one or both hands,
as well as the right or left hand


## Main functions:

### Hand detection:
* Hands in the video are identified using Mediapipe's specialized hand detection model.
Right and left hand discrimination:

* When hands are detected in the video, the software determines whether it is the right or left
* hand based on the Mediapipe classification.
  
### Text display:
* The software displays the appropriate text on the video in real time such as "Both Hands" if both hands are present or "Left Hand" and "Right Hand" for each hand separately.
Real-time interaction:

* The video is displayed in real time with continuous updates on the status of the hands.
The user can exit the video by pressing the "q" key


## Libraries used:

* OpenCV: An open source library for image and video processing.
* Mediapipe: A library from Google used for recognizing hands, facial features, and many other features.
* google.protobuf.json_format: Converts protobuf messages to dictionary format, making them easier to handle.


## How to use:

* Connect your webcam and run the program.
* The program will start displaying the live video from the camera.
* If a hand or hands are detected in the video, the program will display the appropriate text ("Both Hands", "Left Hand", "Right Hand").
* Press 'q' to exit the application.


The choice of application - Real time through web application using Gaze tracking
At the moment, this work creates a fundamental real-time gaze detection web application using Python Flask, OpenCV, and Dlib. This application feature entails framing of the captured live video from a webcam, landmarks detection on the face and deciding if the eyes are focused.

Features
Real-time Video Capture: Adopts webcam to capture live streams or feeds.
Face Detection: Biometric identification of employees begins with the identification of faces in the video stream from the facial recognition terminal using the Dlib frontal face detector.
Facial Landmarks Detection: Employ Dlib facial landmark detector which is a machine learning model that is used to predict facial shapes, this one does it of 68 facial landmarks with an initial shape predictor model.
Gaze Detection: Since the eyes are then identified to be open, the laptop proceeds in identifying the position of the eyes to tell if the user is in focus or not.
Web Interface: Provides a simple web user interface to display the composed video stream on a web page with the gaze information overlayed.

Technologies Used
Python: Languages utilized while implementing the application is software development languages or programming languages.
Flask: Python Web framework for creating the web-based human interfaces-widgets with the help of as many lines of the HTML code as possible.
OpenCV: A software utility that allows managing the analyzed video and its processing and that has an open-source license.
Dlib: An implementation process for the task of applying machine learning and data analysis to detect the face and facial features.
Numpy: An example of a library in Python that encompasses numerical transactions will also be good for an array transaction.

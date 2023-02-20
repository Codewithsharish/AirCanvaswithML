# AirCanvaswithML
Computer vision project implemented with OpenCV with Machine learning using the Mediapipe. 

Ever wanted to draw your imagination by just waiving your finger in air. In this project I learn to build an Air Canvas which can draw anything on it by just motion of our hands and noticing the landmark on the hand knuckels. I'm using the computer vision techniques of OpenCV to build this project. The preferred language is python due to its exhaustive libraries and easy to use syntax but understanding the basics it can be implemented in any OpenCV supported language.

Here Hand landmarks detection and tracking is used in order to achieve the objective.

Requirements: python3 , Numpy , openCV, Mediapipe installed in system.

1. Start reading the frames and convert the captured frames to HSV color space.(Easy for color detection)
2. Prepare the canvas frame and put the respective ink buttons on it.
3. Adjust the values of the Mediapipe initialization to detect one hand only.
4. Detect the landmarks by passing the RGB frame to the Mediapipe hand detector. 
5. Detect the landmarks, find the forefinger coordinates and keep storing them in the array for successive frames .
6. Finally draw the points stored in array on the frames and canvas .

Summary: Body Measurement from Face Video

This Python script utilizes OpenCV to analyze a video stream, estimating body measurements based on facial features. The main functionalities include face and eye detection, calculating reference metrics, and predicting height using a pre-trained machine learning model.

Key Components:
Face and Eye Detection:
Utilizes Haar cascades for face and eye detection.
Draws rectangles around detected faces and eyes, measuring the distance between eyes.

Reference Measurements:
Defines a reference eye distance and a typical eye-to-height ratio for calibration.

Real-time Plotting:
Uses Matplotlib for real-time plotting of RGB signals from the video frames.

Data Collection:
Gathers additional information (Name, Subject ID, Age, Gender) and RGB values during the video capture.

Height Estimation:
Estimates height based on the eye distance and predefined ratios.
Computes the mode height and R value from collected data.

Data Output:
Saves the collected data (Name, Subject ID, Age, Gender, Height, R Value) to an Excel file.

Height Prediction (Optional):
Utilizes a pre-trained machine learning model for predicting height based on the R value.

Usage:
Loads a video file from the specified path.
Captures video frames and performs face and eye detection.
Calculates reference metrics, estimates height, and records RGB signals.
Displays real-time plots of the RGB signals.
Outputs a summary of the mode height and R value.
Optionally predicts height using a pre-trained machine learning model.

Requirements:
OpenCV
NumPy
pandas
Matplotlib
scikit-learn
Note:

Ensure the availability of the required XML files for Haar cascades.
Modify the video path and file locations accordingly.
Feel free to customize and extend this script based on specific project requirements.







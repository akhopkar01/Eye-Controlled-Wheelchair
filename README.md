# Eye Tracking System for Electric Wheelchair Control          			             
This is a real-time eye tracking framework that renders any electric wheelchair driven by eye movements.
<p align="center">
  <img src="https://github.com/dahhmani/Eye-Controlled-Wheelchair/blob/master/Demo/WholeSystem.gif?raw=true">
</p>

## Overview
The framework consists of four applications:
1. ```EyeTracker_Calibrate``` acquire and label user-specific eye images automatically, then learn a gaze classifier from them.
2. ```EyeTracker_Test``` test the learned model's performance in gaze estimation, and output all the necessary results.
3. ```EyeTracker_Deploy``` deploy the tested model to infer the user's gaze direction in real-time, and communicate it to a microcontroller which takes the appropriate action.
4. ```CNN_HyperparametersSearch``` implement cross-validation which is used to select the model architecture.

## Setup
1. Clone this repository
2. Run ```Setup.bat```

## Note 
If you need the source codes, please email Mahmoud Dahmani at dahhmani@hotmail.com
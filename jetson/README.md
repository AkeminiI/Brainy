# Jetson Nano – AI & Control System

This folder contains all Jetson Nano scripts and modules used to control the Brainy autonomous rover.

## Purpose
The Jetson Nano acts as the rover’s high-level AI brain, responsible for:
- Running neural networks for object detection and perception  
- Handling offline voice commands (Vosk/Whisper)  
- Performing computer vision tasks with onboard cameras  
- Sending navigation and mode-change commands to the Pixhawk via MAVLink  
- Processing sensor data from the Arduino hub  
- Executing autonomous decision-making logic  

## Subfolders
- **voice_commands/** – offline speech recognition scripts  
- **vision_ai/** – object detection, tracking, and CV modules  
- **mavlink_control/** – Python scripts to communicate with Pixhawk  

## Notes
All Jetson code will be written in Python.  
Model files, checkpoints, and large assets will be excluded using `.gitignore`.

# Pixhawk Control System

This folder contains all Pixhawk-related configuration files for the Brainy autonomous rover.

## Purpose
Pixhawk serves as the rover’s pilot, responsible for:
- Motor control and steering output  
- Executing navigation modes (MANUAL, HOLD, AUTO, GUIDED, etc.)  
- Reading telemetry data  
- Running built-in failsafes for safety  
- Following high-level commands sent from the Jetson Nano via MAVLink  

## Subfolders
- **parameters/** – Pixhawk/ArduRover parameter (.param) files  
- **mission_files/** – waypoint missions and plans  

## Notes
Parameter files stored here are version-controlled so changes to the rover’s behavior can be tracked over time.
